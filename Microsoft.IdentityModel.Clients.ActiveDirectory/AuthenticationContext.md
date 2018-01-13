<Type Name="AuthenticationContext" FullName="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext">
  <TypeSignature Language="C#" Value="public sealed class AuthenticationContext" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit AuthenticationContext extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class AuthenticationContext" />
  <TypeSignature Language="F#" Value="type AuthenticationContext = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
    <AssemblyVersion>3.16.0.14</AssemblyVersion>
    <AssemblyVersion>3.17.3.35304</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            AuthenticationContext クラスは、Azure Active Directory と ad FS のサービスから認証トークンを取得します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AuthenticationContext (string authority);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string authority) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (authority As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext : string -&gt; Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" Usage="new Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authority" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="authority" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="authority">トークンの発行する機関のアドレス。</param>
        <summary>
            機関のアドレスを持つコンテキストを作成するコンス トラクターです。
            このコンス トラクターを使用して、機関の URL の検証既定でオンに機関アドレスの検証がサポートされている場合。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AuthenticationContext (string authority, Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache tokenCache);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string authority, class Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache tokenCache) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.#ctor(System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache)" />
      <MemberSignature Language="F#" Value="new Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext : string * Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache -&gt; Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" Usage="new Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext (authority, tokenCache)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="authority" Type="System.String" />
        <Parameter Name="tokenCache" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache" />
      </Parameters>
      <Docs>
        <param name="authority">トークンの発行する機関のアドレス。</param>
        <param name="tokenCache">AcquireToken への呼び出しでキャッシュされたトークンの参照に使用されたトークンのキャッシュ</param>
        <summary>
            機関のアドレスを持つコンテキストを作成するコンス トラクターです。
            このコンス トラクターを使用して、機関の URL の検証既定でオンに機関アドレスの検証がサポートされている場合。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AuthenticationContext (string authority, bool validateAuthority);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string authority, bool validateAuthority) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.#ctor(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (authority As String, validateAuthority As Boolean)" />
      <MemberSignature Language="F#" Value="new Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext : string * bool -&gt; Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" Usage="new Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext (authority, validateAuthority)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="authority" Type="System.String" />
        <Parameter Name="validateAuthority" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="authority">トークンの発行する機関のアドレス。</param>
        <param name="validateAuthority">アドレスの検証を有効または無効にするフラグを設定します。</param>
        <summary>
            アドレスの検証を無効にするには、証明機関とフラグのアドレスでコンテキストを作成するコンス トラクターです。
            このコンス トラクターを使用して、アドレスの検証は、オフにすることができます。 アドレスを検証しないセキュリティ暗黙的認識していることを確認してください。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AuthenticationContext (string authority, bool validateAuthority, Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache tokenCache);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string authority, bool validateAuthority, class Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache tokenCache) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.#ctor(System.String,System.Boolean,Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache)" />
      <MemberSignature Language="F#" Value="new Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext : string * bool * Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache -&gt; Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" Usage="new Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext (authority, validateAuthority, tokenCache)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="authority" Type="System.String" />
        <Parameter Name="validateAuthority" Type="System.Boolean" />
        <Parameter Name="tokenCache" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache" />
      </Parameters>
      <Docs>
        <param name="authority">トークンの発行する機関のアドレス。</param>
        <param name="validateAuthority">アドレスの検証を有効または無効にするフラグを設定します。</param>
        <param name="tokenCache">AcquireToken への呼び出しでキャッシュされたトークンの参照に使用されたトークンのキャッシュ</param>
        <summary>
            アドレスの検証を無効にするには、証明機関とフラグのアドレスでコンテキストを作成するコンス トラクターです。
            このコンス トラクターを使用して、アドレスの検証は、オフにすることができます。 アドレスを検証しないセキュリティ暗黙的認識していることを確認してください。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireDeviceCodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult&gt; AcquireDeviceCodeAsync (string resource, string clientId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult&gt; AcquireDeviceCodeAsync(string resource, string clientId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireDeviceCodeAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireDeviceCodeAsync (resource As String, clientId As String) As Task(Of DeviceCodeResult)" />
      <MemberSignature Language="F#" Value="member this.AcquireDeviceCodeAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult&gt;" Usage="authenticationContext.AcquireDeviceCodeAsync (resource, clientId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireDeviceCodeAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resource">要求されたトークンの受信者は、ターゲット リソースの識別子。</param>
        <param name="clientId">トークンを要求したクライアントの識別子。</param>
        <summary>
            デバイスの機関からのコードを取得します。
            </summary>
        <returns>デバイスのコード、その有効期限が含まれています時間、ユーザー コードです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireDeviceCodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult&gt; AcquireDeviceCodeAsync (string resource, string clientId, string extraQueryParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult&gt; AcquireDeviceCodeAsync(string resource, string clientId, string extraQueryParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireDeviceCodeAsync(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireDeviceCodeAsync (resource As String, clientId As String, extraQueryParameters As String) As Task(Of DeviceCodeResult)" />
      <MemberSignature Language="F#" Value="member this.AcquireDeviceCodeAsync : string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult&gt;" Usage="authenticationContext.AcquireDeviceCodeAsync (resource, clientId, extraQueryParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireDeviceCodeAsync&gt;d__22))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resource">要求されたトークンの受信者は、ターゲット リソースの識別子。</param>
        <param name="clientId">トークンを要求したクライアントの識別子。</param>
        <param name="extraQueryParameters">証明機関に HTTP 認証要求のクエリ文字列には、このパラメーターが追加されます。 パラメーターを null にすることができます。</param>
        <summary>
            デバイスの機関からのコードを取得します。
            </summary>
        <returns>デバイスのコード、その有効期限が含まれています時間、ユーザー コードです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync (string resource, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion clientAssertion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync(string resource, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion clientAssertion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenAsync(System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenAsync : string * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenAsync (resource, clientAssertion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenAsync&gt;d__57))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientAssertion" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion" />
      </Parameters>
      <Docs>
        <param name="resource">要求されたトークンの受信者は、ターゲット リソースの識別子。</param>
        <param name="clientAssertion">トークンの取得に使用するクライアントのアサーションです。</param>
        <summary>
            機関からセキュリティ トークンを取得します。
            </summary>
        <returns>アクセス トークンとアクセス トークンの有効期限が含まれています。 更新トークンのプロパティは、このオーバー ロードを null になります。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync (string resource, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync(string resource, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenAsync(System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenAsync : string * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenAsync (resource, clientCredential)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenAsync&gt;d__58))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientCredential" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential" />
      </Parameters>
      <Docs>
        <param name="resource">要求されたトークンの受信者は、ターゲット リソースの識別子。</param>
        <param name="clientCredential">トークンの取得に使用するクライアントの資格情報です。</param>
        <summary>
            機関からセキュリティ トークンを取得します。
            </summary>
        <returns>アクセス トークンとアクセス トークンの有効期限が含まれています。 更新トークンのプロパティは、このオーバー ロードを null になります。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync (string resource, Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate clientCertificate);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync(string resource, class Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate clientCertificate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenAsync(System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (resource As String, clientCertificate As IClientAssertionCertificate) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenAsync : string * Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenAsync (resource, clientCertificate)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenAsync&gt;d__56))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientCertificate" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate" />
      </Parameters>
      <Docs>
        <param name="resource">要求されたトークンの受信者は、ターゲット リソースの識別子。</param>
        <param name="clientCertificate">トークンの取得に使用するクライアント証明書。</param>
        <summary>
            機関からセキュリティ トークンを取得します。
            </summary>
        <returns>アクセス トークンとアクセス トークンの有効期限が含まれています。 更新トークンのプロパティは、このオーバー ロードを null になります。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync (string resource, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion clientAssertion, Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion userAssertion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync(string resource, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion clientAssertion, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion userAssertion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenAsync(System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion,Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenAsync : string * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion * Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenAsync (resource, clientAssertion, userAssertion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenAsync&gt;d__54))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientAssertion" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion" />
        <Parameter Name="userAssertion" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion" />
      </Parameters>
      <Docs>
        <param name="resource">要求されたトークンの受信者は、ターゲット リソースの識別子。</param>
        <param name="clientAssertion">トークンの取得に使用するクライアントのアサーションです。</param>
        <param name="userAssertion">トークンの取得に使用するユーザー アサーション (トークン) です。</param>
        <summary>
            ユーザーの代理として、権限からアクセス トークンを取得します。 以前に受信したユーザー トークンを使用する必要があります。
            </summary>
        <returns>アクセス トークンとアクセス トークンの有効期限が含まれています。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync (string resource, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential, Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion userAssertion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync(string resource, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion userAssertion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenAsync(System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential,Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenAsync : string * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential * Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenAsync (resource, clientCredential, userAssertion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenAsync&gt;d__52))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientCredential" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential" />
        <Parameter Name="userAssertion" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion" />
      </Parameters>
      <Docs>
        <param name="resource">要求されたトークンの受信者は、ターゲット リソースの識別子。</param>
        <param name="clientCredential">トークンの取得に使用するクライアントの資格情報です。</param>
        <param name="userAssertion">トークンの取得に使用するユーザー アサーション (トークン) です。</param>
        <summary>
            ユーザーの代理として、権限からアクセス トークンを取得します。 以前に受信したユーザー トークンを使用する必要があります。
            </summary>
        <returns>アクセス トークンとアクセス トークンの有効期限が含まれています。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync (string resource, Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate clientCertificate, Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion userAssertion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync(string resource, class Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate clientCertificate, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion userAssertion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenAsync(System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate,Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenAsync : string * Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate * Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenAsync (resource, clientCertificate, userAssertion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenAsync&gt;d__53))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientCertificate" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate" />
        <Parameter Name="userAssertion" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion" />
      </Parameters>
      <Docs>
        <param name="resource">要求されたトークンの受信者は、ターゲット リソースの識別子。</param>
        <param name="clientCertificate">トークンの取得に使用するクライアント証明書。</param>
        <param name="userAssertion">トークンの取得に使用するユーザー アサーション (トークン) です。</param>
        <summary>
            ユーザーの代理として、権限からアクセス トークンを取得します。 以前に受信したユーザー トークンを使用する必要があります。
            </summary>
        <returns>アクセス トークンとアクセス トークンの有効期限が含まれています。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync (string resource, string clientId, Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion userAssertion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync(string resource, string clientId, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion userAssertion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenAsync(System.String,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenAsync : string * string * Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenAsync (resource, clientId, userAssertion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenAsync&gt;d__55))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="userAssertion" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion" />
      </Parameters>
      <Docs>
        <param name="resource">要求されたトークンの受信者は、ターゲット リソースの識別子。</param>
        <param name="clientId">トークンを要求したクライアントの識別子。</param>
        <param name="userAssertion">トークンの取得に使用するアサーションです。</param>
        <summary>
            機関からセキュリティ トークンを取得します。
            </summary>
        <returns>アクセス トークンとアクセス トークンの有効期限が含まれています。 更新トークンのプロパティは、このオーバー ロードを null になります。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync (string resource, string clientId, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync(string resource, string clientId, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenAsync(System.String,System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (resource As String, clientId As String, redirectUri As Uri, parameters As IPlatformParameters) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenAsync : string * string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenAsync (resource, clientId, redirectUri, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenAsync&gt;d__28))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.Uri" />
        <Parameter Name="parameters" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters" />
      </Parameters>
      <Docs>
        <param name="resource">要求されたトークンの受信者は、ターゲット リソースの識別子。</param>
        <param name="clientId">トークンを要求したクライアントの識別子。</param>
        <param name="redirectUri">機関からの応答を受信したときに戻るにはアドレスです。</param>
        <param name="parameters">承認に使用される追加のパラメーターを渡すことがあります PlatformParameters の種類のオブジェクトです。</param>
        <summary>
            機関からセキュリティ トークンを取得します。
            </summary>
        <returns>アクセス トークン、その有効期限、ユーザー情報が含まれています。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync (string resource, string clientId, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters parameters, Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync(string resource, string clientId, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters parameters, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenAsync(System.String,System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (resource As String, clientId As String, redirectUri As Uri, parameters As IPlatformParameters, userId As UserIdentifier) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenAsync : string * string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters * Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenAsync (resource, clientId, redirectUri, parameters, userId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.Uri" />
        <Parameter Name="parameters" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters" />
        <Parameter Name="userId" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />
      </Parameters>
      <Docs>
        <param name="resource">要求されたトークンの受信者は、ターゲット リソースの識別子。</param>
        <param name="clientId">トークンを要求したクライアントの識別子。</param>
        <param name="redirectUri">機関からの応答を受信したときに戻るにはアドレスです。</param>
        <param name="parameters">承認に使用される追加のパラメーターを渡すことがあります PlatformParameters の種類のオブジェクトです。</param>
        <param name="userId">ユーザー トークンの識別子が要求されます。 DisplayableId から作成する場合、このパラメーターは事前認証のフォームのユーザー名フィールドに設定を使用します。 エンドユーザーのユーザー名 フィールドを編集して、別のユーザーとして認証ことができますも注意してください。
            例外では、このような変更の通知を受信する場合は、型 RequiredDisplayableId UserIdentifier を作成します。 このパラメーターを指定できます<see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />です。任意です。</param>
        <summary>
            機関からセキュリティ トークンを取得します。
            </summary>
        <returns>アクセス トークン、その有効期限、ユーザー情報が含まれています。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync (string resource, string clientId, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters parameters, Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId, string extraQueryParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync(string resource, string clientId, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters parameters, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId, string extraQueryParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenAsync(System.String,System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (resource As String, clientId As String, redirectUri As Uri, parameters As IPlatformParameters, userId As UserIdentifier, extraQueryParameters As String) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenAsync : string * string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters * Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenAsync (resource, clientId, redirectUri, parameters, userId, extraQueryParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenAsync&gt;d__30))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.Uri" />
        <Parameter Name="parameters" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters" />
        <Parameter Name="userId" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resource">要求されたトークンの受信者は、ターゲット リソースの識別子。</param>
        <param name="clientId">トークンを要求したクライアントの識別子。</param>
        <param name="redirectUri">機関からの応答を受信したときに戻るにはアドレスです。</param>
        <param name="parameters">承認コードを要求する対話型のフローに必要なパラメーターです。 PlatformParameters のインスタンスを渡します。</param>
        <param name="userId">ユーザー トークンの識別子が要求されます。 DisplayableId から作成する場合、このパラメーターは事前認証のフォームのユーザー名フィールドに設定を使用します。 エンドユーザーのユーザー名 フィールドを編集して、別のユーザーとして認証ことができますも注意してください。
            例外では、このような変更の通知を受信する場合は、型 RequiredDisplayableId UserIdentifier を作成します。 このパラメーターを指定できます<see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />です。任意です。</param>
        <param name="extraQueryParameters">証明機関に HTTP 認証要求のクエリ文字列には、このパラメーターが追加されます。 パラメーターを null にすることができます。</param>
        <summary>
            機関からセキュリティ トークンを取得します。
            </summary>
        <returns>アクセス トークン、その有効期限、ユーザー情報が含まれています。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync (string resource, string clientId, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters parameters, Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId, string extraQueryParameters, string claims);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync(string resource, string clientId, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters parameters, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId, string extraQueryParameters, string claims) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenAsync(System.String,System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (resource As String, clientId As String, redirectUri As Uri, parameters As IPlatformParameters, userId As UserIdentifier, extraQueryParameters As String, claims As String) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenAsync : string * string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters * Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenAsync (resource, clientId, redirectUri, parameters, userId, extraQueryParameters, claims)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenAsync&gt;d__24))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.Uri" />
        <Parameter Name="parameters" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters" />
        <Parameter Name="userId" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
        <Parameter Name="claims" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resource">要求されたトークンの受信者は、ターゲット リソースの識別子。</param>
        <param name="clientId">トークンを要求したクライアントの識別子。</param>
        <param name="redirectUri">機関からの応答を受信したときに戻るにはアドレスです。</param>
        <param name="parameters">プラットフォームの特定の引数と情報を含む PlatformParameters のインスタンス。</param>
        <param name="userId">ユーザー トークンの識別子が要求されます。 このパラメーターを指定できます<see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />です。任意です。</param>
        <param name="extraQueryParameters">証明機関に HTTP 認証要求のクエリ文字列には、このパラメーターが追加されます。 パラメーターを null にすることができます。</param>
        <param name="claims">認証のために必要な追加のクレーム。 AdalClaimChallengeException から取得しました。</param>
        <summary>
            認証のために必要なクレームを渡して、ユーザーに代わって、権限からアクセス トークンを取得します。 以前に受信したユーザー トークンを使用する必要があります。
            </summary>
        <returns>アクセス トークンとアクセス トークンの有効期限が含まれています。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenByAuthorizationCodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenByAuthorizationCodeAsync (string authorizationCode, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion clientAssertion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenByAuthorizationCodeAsync(string authorizationCode, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion clientAssertion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenByAuthorizationCodeAsync(System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenByAuthorizationCodeAsync : string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenByAuthorizationCodeAsync (authorizationCode, redirectUri, clientAssertion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenByAuthorizationCodeAsync&gt;d__48))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="authorizationCode" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.Uri" />
        <Parameter Name="clientAssertion" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion" />
      </Parameters>
      <Docs>
        <param name="authorizationCode">サービスの認証エンドポイントから受信した認証コードです。</param>
        <param name="redirectUri">リダイレクト先アドレスは、認証コードを取得するために使用します。</param>
        <param name="clientAssertion">トークンの取得に使用するクライアントのアサーションです。</param>
        <summary>
            以前に受信した認証コードを使用して、機関からセキュリティ トークンを取得します。
            このメソッドは、トークンのキャッシュを参照できませんが、結果を格納し、それを検索できますなどの他のメソッドを使用して、<see cref="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenSilentAsync(System.String,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier)" />です。
            </summary>
        <returns>アクセス トークン、その有効期限、ユーザー情報が含まれています。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenByAuthorizationCodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenByAuthorizationCodeAsync (string authorizationCode, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenByAuthorizationCodeAsync(string authorizationCode, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenByAuthorizationCodeAsync(System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenByAuthorizationCodeAsync : string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenByAuthorizationCodeAsync (authorizationCode, redirectUri, clientCredential)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenByAuthorizationCodeAsync&gt;d__46))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="authorizationCode" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.Uri" />
        <Parameter Name="clientCredential" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential" />
      </Parameters>
      <Docs>
        <param name="authorizationCode">サービスの認証エンドポイントから受信した認証コードです。</param>
        <param name="redirectUri">機関からの応答を受信したときに戻るにはアドレスです。</param>
        <param name="clientCredential">トークンの取得に使用する資格情報です。</param>
        <summary>
            以前に受信した認証コードを使用して、機関からセキュリティ トークンを取得します。
            このメソッドは、トークンのキャッシュを参照できませんが、結果を格納し、それを検索できますなどの他のメソッドを使用して、<see cref="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenSilentAsync(System.String,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier)" />です。
            </summary>
        <returns>アクセス トークン、その有効期限、ユーザー情報が含まれています。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenByAuthorizationCodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenByAuthorizationCodeAsync (string authorizationCode, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate clientCertificate);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenByAuthorizationCodeAsync(string authorizationCode, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate clientCertificate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenByAuthorizationCodeAsync(System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenByAuthorizationCodeAsync (authorizationCode As String, redirectUri As Uri, clientCertificate As IClientAssertionCertificate) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenByAuthorizationCodeAsync : string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenByAuthorizationCodeAsync (authorizationCode, redirectUri, clientCertificate)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenByAuthorizationCodeAsync&gt;d__50))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="authorizationCode" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.Uri" />
        <Parameter Name="clientCertificate" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate" />
      </Parameters>
      <Docs>
        <param name="authorizationCode">サービスの認証エンドポイントから受信した認証コードです。</param>
        <param name="redirectUri">リダイレクト先アドレスは、認証コードを取得するために使用します。</param>
        <param name="clientCertificate">トークンの取得に使用するクライアント証明書。</param>
        <summary>
            以前に受信した認証コードを使用して、機関からセキュリティ トークンを取得します。
            このメソッドは、トークンのキャッシュを参照できませんが、結果を格納し、それを検索できますなどの他のメソッドを使用して、<see cref="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenSilentAsync(System.String,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier)" />です。
            </summary>
        <returns>アクセス トークン、その有効期限、ユーザー情報が含まれています。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenByAuthorizationCodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenByAuthorizationCodeAsync (string authorizationCode, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion clientAssertion, string resource);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenByAuthorizationCodeAsync(string authorizationCode, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion clientAssertion, string resource) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenByAuthorizationCodeAsync(System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion,System.String)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenByAuthorizationCodeAsync : string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenByAuthorizationCodeAsync (authorizationCode, redirectUri, clientAssertion, resource)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenByAuthorizationCodeAsync&gt;d__49))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="authorizationCode" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.Uri" />
        <Parameter Name="clientAssertion" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion" />
        <Parameter Name="resource" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="authorizationCode">サービスの認証エンドポイントから受信した認証コードです。</param>
        <param name="redirectUri">リダイレクト先アドレスは、認証コードを取得するために使用します。</param>
        <param name="clientAssertion">トークンの取得に使用するクライアントのアサーションです。</param>
        <param name="resource">要求されたトークンの受信者は、ターゲット リソースの識別子。 AuthorizationCode の取得を先に指定した場合は null になります。</param>
        <summary>
            以前に受信した認証コードを使用して、機関からセキュリティ トークンを取得します。
            このメソッドは、トークンのキャッシュを参照できませんが、結果を格納し、それを検索できますなどの他のメソッドを使用して、<see cref="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenSilentAsync(System.String,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier)" />です。
            </summary>
        <returns>アクセス トークン、その有効期限、ユーザー情報が含まれています。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenByAuthorizationCodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenByAuthorizationCodeAsync (string authorizationCode, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential, string resource);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenByAuthorizationCodeAsync(string authorizationCode, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential, string resource) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenByAuthorizationCodeAsync(System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential,System.String)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenByAuthorizationCodeAsync : string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenByAuthorizationCodeAsync (authorizationCode, redirectUri, clientCredential, resource)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenByAuthorizationCodeAsync&gt;d__47))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="authorizationCode" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.Uri" />
        <Parameter Name="clientCredential" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential" />
        <Parameter Name="resource" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="authorizationCode">サービスの認証エンドポイントから受信した認証コードです。</param>
        <param name="redirectUri">機関からの応答を受信したときに戻るにはアドレスです。</param>
        <param name="clientCredential">トークンの取得に使用する資格情報です。</param>
        <param name="resource">要求されたトークンの受信者は、ターゲット リソースの識別子。 AuthorizationCode の取得を先に指定した場合は null になります。</param>
        <summary>
            以前に受信した認証コードを使用して、機関からセキュリティ トークンを取得します。
            このメソッドは、トークンのキャッシュを参照できませんが、結果を格納し、それを検索できますなどの他のメソッドを使用して、<see cref="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenSilentAsync(System.String,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier)" />です。
            </summary>
        <returns>アクセス トークン、その有効期限、ユーザー情報が含まれています。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenByAuthorizationCodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenByAuthorizationCodeAsync (string authorizationCode, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate clientCertificate, string resource);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenByAuthorizationCodeAsync(string authorizationCode, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate clientCertificate, string resource) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenByAuthorizationCodeAsync(System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenByAuthorizationCodeAsync (authorizationCode As String, redirectUri As Uri, clientCertificate As IClientAssertionCertificate, resource As String) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenByAuthorizationCodeAsync : string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenByAuthorizationCodeAsync (authorizationCode, redirectUri, clientCertificate, resource)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenByAuthorizationCodeAsync&gt;d__51))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="authorizationCode" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.Uri" />
        <Parameter Name="clientCertificate" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate" />
        <Parameter Name="resource" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="authorizationCode">サービスの認証エンドポイントから受信した認証コードです。</param>
        <param name="redirectUri">リダイレクト先アドレスは、認証コードを取得するために使用します。</param>
        <param name="clientCertificate">トークンの取得に使用するクライアント証明書。</param>
        <param name="resource">要求されたトークンの受信者は、ターゲット リソースの識別子。 AuthorizationCode の取得を先に指定した場合は null になります。</param>
        <summary>
            以前に受信した認証コードを使用して、機関からセキュリティ トークンを取得します。
            このメソッドは、トークンのキャッシュを参照できませんが、結果を格納し、それを検索できますなどの他のメソッドを使用して、<see cref="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenSilentAsync(System.String,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier)" />です。
            </summary>
        <returns>アクセス トークン、その有効期限、ユーザー情報が含まれています。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenByDeviceCodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenByDeviceCodeAsync (Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult deviceCodeResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenByDeviceCodeAsync(class Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult deviceCodeResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenByDeviceCodeAsync(Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenByDeviceCodeAsync : Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenByDeviceCodeAsync deviceCodeResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenByDeviceCodeAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceCodeResult" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult" />
      </Parameters>
      <Docs>
        <param name="deviceCodeResult">呼び出し元の AcquireDeviceCodeAsync から受信したデバイス コード結果。</param>
        <summary>
            以前に受信したデバイス コードを使用して、機関からセキュリティ トークンを取得します。
            このメソッドは、トークンのキャッシュを参照できませんが、結果を格納し、それを検索できますなどの他のメソッドを使用して、<see cref="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenSilentAsync(System.String,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier)" />です。
            </summary>
        <returns>アクセス トークン、その有効期限、ユーザー情報が含まれています。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenSilentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenSilentAsync (string resource, string clientId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenSilentAsync(string resource, string clientId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenSilentAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenSilentAsync (resource As String, clientId As String) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenSilentAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenSilentAsync (resource, clientId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenSilentAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resource">要求されたトークンの受信者は、ターゲット リソースの識別子。</param>
        <param name="clientId">トークンを要求したクライアントの識別子。</param>
        <summary>
            ユーザーの資格情報を求めることがなく、セキュリティ トークンを取得します。
            </summary>
        <returns>アクセス トークン、その有効期限、ユーザー情報が含まれています。 ユーザーの資格情報はないトークンの取得、メソッドは AdalException をスローします。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenSilentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenSilentAsync (string resource, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion clientAssertion, Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenSilentAsync(string resource, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion clientAssertion, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenSilentAsync(System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenSilentAsync : string * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion * Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenSilentAsync (resource, clientAssertion, userId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenSilentAsync&gt;d__45))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientAssertion" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion" />
        <Parameter Name="userId" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />
      </Parameters>
      <Docs>
        <param name="resource">要求されたトークンの受信者は、ターゲット リソースの識別子。</param>
        <param name="clientAssertion">トークンの取得に使用するクライアントのアサーションです。</param>
        <param name="userId">ユーザー トークンの識別子が要求されます。 このパラメーターを指定できます<see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />です。任意です。</param>
        <summary>
            ユーザーの資格情報を求めることがなく、セキュリティ トークンを取得します。
            </summary>
        <returns>アクセス トークン、その有効期限、ユーザー情報が含まれています。 ユーザーの資格情報はないトークンの取得、メソッドは AdalException をスローします。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenSilentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenSilentAsync (string resource, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential, Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenSilentAsync(string resource, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenSilentAsync(System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenSilentAsync : string * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential * Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenSilentAsync (resource, clientCredential, userId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenSilentAsync&gt;d__43))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientCredential" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential" />
        <Parameter Name="userId" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />
      </Parameters>
      <Docs>
        <param name="resource">要求されたトークンの受信者は、ターゲット リソースの識別子。</param>
        <param name="clientCredential">トークンの取得に使用するクライアントの資格情報です。</param>
        <param name="userId">ユーザー トークンの識別子が要求されます。 このパラメーターを指定できます<see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />です。任意です。</param>
        <summary>
            ユーザーの資格情報を求めることがなく、セキュリティ トークンを取得します。
            </summary>
        <returns>アクセス トークン、その有効期限、ユーザー情報が含まれています。 ユーザーの資格情報はないトークンの取得、メソッドは AdalException をスローします。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenSilentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenSilentAsync (string resource, Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate clientCertificate, Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenSilentAsync(string resource, class Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate clientCertificate, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenSilentAsync(System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenSilentAsync (resource As String, clientCertificate As IClientAssertionCertificate, userId As UserIdentifier) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenSilentAsync : string * Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate * Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenSilentAsync (resource, clientCertificate, userId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenSilentAsync&gt;d__44))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientCertificate" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate" />
        <Parameter Name="userId" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />
      </Parameters>
      <Docs>
        <param name="resource">要求されたトークンの受信者は、ターゲット リソースの識別子。</param>
        <param name="clientCertificate">トークンの取得に使用するクライアント証明書。</param>
        <param name="userId">ユーザー トークンの識別子が要求されます。 このパラメーターを指定できます<see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />です。任意です。</param>
        <summary>
            ユーザーの資格情報を求めることがなく、セキュリティ トークンを取得します。
            </summary>
        <returns>アクセス トークン、その有効期限、ユーザー情報が含まれています。 ユーザーの資格情報はないトークンの取得、メソッドは AdalException をスローします。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenSilentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenSilentAsync (string resource, string clientId, Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenSilentAsync(string resource, string clientId, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenSilentAsync(System.String,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenSilentAsync (resource As String, clientId As String, userId As UserIdentifier) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenSilentAsync : string * string * Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenSilentAsync (resource, clientId, userId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenSilentAsync&gt;d__26))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="userId" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />
      </Parameters>
      <Docs>
        <param name="resource">要求されたトークンの受信者は、ターゲット リソースの識別子。</param>
        <param name="clientId">トークンを要求したクライアントの識別子。</param>
        <param name="userId">ユーザー トークンの識別子が要求されます。 このパラメーターを指定できます<see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />です。任意です。</param>
        <summary>
            ユーザーの資格情報を求めることがなく、セキュリティ トークンを取得します。
            </summary>
        <returns>アクセス トークン、その有効期限、ユーザー情報が含まれています。 ユーザーの資格情報はないトークンの取得、メソッドは AdalException をスローします。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenSilentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenSilentAsync (string resource, string clientId, Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId, Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenSilentAsync(string resource, string clientId, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId, class Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenSilentAsync(System.String,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier,Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenSilentAsync (resource As String, clientId As String, userId As UserIdentifier, parameters As IPlatformParameters) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenSilentAsync : string * string * Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier * Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenSilentAsync (resource, clientId, userId, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenSilentAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="userId" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />
        <Parameter Name="parameters" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters" />
      </Parameters>
      <Docs>
        <param name="resource">要求されたトークンの受信者は、ターゲット リソースの識別子。</param>
        <param name="clientId">トークンを要求したクライアントの識別子。</param>
        <param name="userId">ユーザー トークンの識別子が要求されます。 このパラメーターを指定できます<see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />です。任意です。</param>
        <param name="parameters">プラットフォームの特定の引数と情報を含む PlatformParameters のインスタンス。</param>
        <summary>
            ユーザーの資格情報を求めることがなく、セキュリティ トークンを取得します。
            </summary>
        <returns>アクセス トークン、その有効期限、ユーザー情報が含まれています。 ユーザーの資格情報はないトークンの取得、メソッドは AdalException をスローします。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Authority">
      <MemberSignature Language="C#" Value="public string Authority { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Authority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.Authority" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Authority As String" />
      <MemberSignature Language="F#" Value="member this.Authority : string" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.Authority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            トークンの発行する機関のアドレスを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CorrelationId">
      <MemberSignature Language="C#" Value="public Guid CorrelationId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid CorrelationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.CorrelationId" />
      <MemberSignature Language="VB.NET" Value="Public Property CorrelationId As Guid" />
      <MemberSignature Language="F#" Value="member this.CorrelationId : Guid with get, set" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.CorrelationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の相関 Id とは、次の要求をサービスに送信されます。
            相関 Id では、診断目的で使用します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExtendedLifeTimeEnabled">
      <MemberSignature Language="C#" Value="public bool ExtendedLifeTimeEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ExtendedLifeTimeEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.ExtendedLifeTimeEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property ExtendedLifeTimeEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.ExtendedLifeTimeEnabled : bool with get, set" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.ExtendedLifeTimeEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            AAD の有効期間の延長のフラグを設定するために使用
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAuthorizationRequestUrlAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Uri&gt; GetAuthorizationRequestUrlAsync (string resource, string clientId, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId, string extraQueryParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Uri&gt; GetAuthorizationRequestUrlAsync(string resource, string clientId, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId, string extraQueryParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.GetAuthorizationRequestUrlAsync(System.String,System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetAuthorizationRequestUrlAsync (resource As String, clientId As String, redirectUri As Uri, userId As UserIdentifier, extraQueryParameters As String) As Task(Of Uri)" />
      <MemberSignature Language="F#" Value="member this.GetAuthorizationRequestUrlAsync : string * string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier * string -&gt; System.Threading.Tasks.Task&lt;Uri&gt;" Usage="authenticationContext.GetAuthorizationRequestUrlAsync (resource, clientId, redirectUri, userId, extraQueryParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;GetAuthorizationRequestUrlAsync&gt;d__41))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Uri&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.Uri" />
        <Parameter Name="userId" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resource">要求されたトークンの受信者は、ターゲット リソースの識別子。</param>
        <param name="clientId">トークンを要求したクライアントの識別子。</param>
        <param name="redirectUri">機関からの応答を受信したときに戻るにはアドレスです。</param>
        <param name="userId">ユーザー トークンの識別子が要求されます。 このパラメーターを指定できます<see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />です。任意です。</param>
        <param name="extraQueryParameters">証明機関に HTTP 認証要求のクエリ文字列には、このパラメーターが追加されます。 パラメーターを null にすることができます。</param>
        <summary>
            クエリ パラメーターを含む、authorize エンドポイントの URL を取得します。
            </summary>
        <returns>クエリ パラメーターを含む authorize エンドポイントの URL です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAuthorizationRequestUrlAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Uri&gt; GetAuthorizationRequestUrlAsync (string resource, string clientId, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId, string extraQueryParameters, string claims);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Uri&gt; GetAuthorizationRequestUrlAsync(string resource, string clientId, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId, string extraQueryParameters, string claims) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.GetAuthorizationRequestUrlAsync(System.String,System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetAuthorizationRequestUrlAsync (resource As String, clientId As String, redirectUri As Uri, userId As UserIdentifier, extraQueryParameters As String, claims As String) As Task(Of Uri)" />
      <MemberSignature Language="F#" Value="member this.GetAuthorizationRequestUrlAsync : string * string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier * string * string -&gt; System.Threading.Tasks.Task&lt;Uri&gt;" Usage="authenticationContext.GetAuthorizationRequestUrlAsync (resource, clientId, redirectUri, userId, extraQueryParameters, claims)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;GetAuthorizationRequestUrlAsync&gt;d__42))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Uri&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.Uri" />
        <Parameter Name="userId" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
        <Parameter Name="claims" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resource">要求されたトークンの受信者は、ターゲット リソースの識別子。</param>
        <param name="clientId">トークンを要求したクライアントの識別子。</param>
        <param name="redirectUri">機関からの応答を受信したときに戻るにはアドレスです。</param>
        <param name="userId">ユーザー トークンの識別子が要求されます。 このパラメーターを指定できます<see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />です。任意です。</param>
        <param name="extraQueryParameters">証明機関に HTTP 認証要求のクエリ文字列には、このパラメーターが追加されます。 パラメーターを null にすることができます。</param>
        <param name="claims">認証のために必要な追加のクレーム。 AdalClaimChallengeException から取得します。 このパラメーターには、null を指定できます。</param>
        <summary>
            クエリ パラメーターを含む、authorize エンドポイントの URL を取得します。
            </summary>
        <returns>クエリ パラメーターを含む authorize エンドポイントの URL です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenCache">
      <MemberSignature Language="C#" Value="public Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache TokenCache { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache TokenCache" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.TokenCache" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TokenCache As TokenCache" />
      <MemberSignature Language="F#" Value="member this.TokenCache : Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.TokenCache" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ADAL のトークンのキャッシュを提供するプロパティです。 プラットフォームによって TokenCache はか既定の永続的なキャッシュがあります。
            それらを取得するたびにライブラリは既定の TokenCache に自動的にトークンを保存します。 キャッシュされたトークンはそれらを保存するアプリケーションでのみ使用可能になります。
            キャッシュが永続的な場合に格納されているトークンは、アプリケーションの実行はよりも長くし、が後続の実行で使用できます。
            トークン キャッシュを無効にするには、TokenCache を null に設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateAuthority">
      <MemberSignature Language="C#" Value="public bool ValidateAuthority { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ValidateAuthority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.ValidateAuthority" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ValidateAuthority As Boolean" />
      <MemberSignature Language="F#" Value="member this.ValidateAuthority : bool" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.ValidateAuthority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
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