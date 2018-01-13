<Type Name="TokenProvider" FullName="Microsoft.ServiceBus.TokenProvider">
  <TypeSignature Language="C#" Value="public abstract class TokenProvider" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit TokenProvider extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.TokenProvider" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class TokenProvider" />
  <TypeSignature Language="F#" Value="type TokenProvider = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>セキュリティ トークン プロバイダーをいくつかのよく知られているトークン プロバイダーを返す組み込みのファクトリ メソッドを表します。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected TokenProvider (bool cacheTokens, bool supportHttpAuthToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(bool cacheTokens, bool supportHttpAuthToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.#ctor(System.Boolean,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (cacheTokens As Boolean, supportHttpAuthToken As Boolean)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.TokenProvider : bool * bool -&gt; Microsoft.ServiceBus.TokenProvider" Usage="new Microsoft.ServiceBus.TokenProvider (cacheTokens, supportHttpAuthToken)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="cacheTokens" Type="System.Boolean" />
        <Parameter Name="supportHttpAuthToken" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="cacheTokens">新しいセキュリティ トークンはキャッシュされている場合は true。それ以外の場合は false です。</param>
        <param name="supportHttpAuthToken">web トークンが; このプロバイダーでサポートされている場合は true。それ以外の場合は false です。</param>
        <summary><see cref="T:Microsoft.ServiceBus.TokenProvider" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected TokenProvider (bool cacheTokens, bool supportHttpAuthToken, Microsoft.ServiceBus.TokenScope tokenScope);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(bool cacheTokens, bool supportHttpAuthToken, valuetype Microsoft.ServiceBus.TokenScope tokenScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.#ctor(System.Boolean,System.Boolean,Microsoft.ServiceBus.TokenScope)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.TokenProvider : bool * bool * Microsoft.ServiceBus.TokenScope -&gt; Microsoft.ServiceBus.TokenProvider" Usage="new Microsoft.ServiceBus.TokenProvider (cacheTokens, supportHttpAuthToken, tokenScope)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="cacheTokens" Type="System.Boolean" />
        <Parameter Name="supportHttpAuthToken" Type="System.Boolean" />
        <Parameter Name="tokenScope" Type="Microsoft.ServiceBus.TokenScope" />
      </Parameters>
      <Docs>
        <param name="cacheTokens">新しいセキュリティ トークンはキャッシュされている場合は true。それ以外の場合は false です。</param>
        <param name="supportHttpAuthToken">web トークンが; このプロバイダーでサポートされている場合は true。それ以外の場合は false です。</param>
        <param name="tokenScope">プロバイダーに関連付けられているトークンのスコープです。</param>
        <summary><see cref="T:Microsoft.ServiceBus.TokenProvider" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected TokenProvider (bool cacheTokens, bool supportHttpAuthToken, int cacheSize, Microsoft.ServiceBus.TokenScope tokenScope);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(bool cacheTokens, bool supportHttpAuthToken, int32 cacheSize, valuetype Microsoft.ServiceBus.TokenScope tokenScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.#ctor(System.Boolean,System.Boolean,System.Int32,Microsoft.ServiceBus.TokenScope)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.TokenProvider : bool * bool * int * Microsoft.ServiceBus.TokenScope -&gt; Microsoft.ServiceBus.TokenProvider" Usage="new Microsoft.ServiceBus.TokenProvider (cacheTokens, supportHttpAuthToken, cacheSize, tokenScope)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="cacheTokens" Type="System.Boolean" />
        <Parameter Name="supportHttpAuthToken" Type="System.Boolean" />
        <Parameter Name="cacheSize" Type="System.Int32" />
        <Parameter Name="tokenScope" Type="Microsoft.ServiceBus.TokenScope" />
      </Parameters>
      <Docs>
        <param name="cacheTokens">新しいセキュリティ トークンはキャッシュされている場合は true。それ以外の場合は false です。</param>
        <param name="supportHttpAuthToken">web トークンが; このプロバイダーでサポートされている場合は true。それ以外の場合は false です。</param>
        <param name="cacheSize">キャッシュのサイズ。</param>
        <param name="tokenScope">プロバイダーに関連付けられているトークンのスコープです。</param>
        <summary><see cref="T:Microsoft.ServiceBus.TokenProvider" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetToken">
      <MemberSignature Language="C#" Value="public IAsyncResult BeginGetToken (string appliesTo, string action, bool bypassCache, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.IAsyncResult BeginGetToken(string appliesTo, string action, bool bypassCache, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.BeginGetToken(System.String,System.String,System.Boolean,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function BeginGetToken (appliesTo As String, action As String, bypassCache As Boolean, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="member this.BeginGetToken : string * string * bool * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="tokenProvider.BeginGetToken (appliesTo, action, bypassCache, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appliesTo" Type="System.String" />
        <Parameter Name="action" Type="System.String" />
        <Parameter Name="bypassCache" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="appliesTo">アクセス トークンが適用される URI。</param>
        <param name="action">要求された操作。</param>
        <param name="bypassCache">キャッシュ内の既存のトークン情報を無視する場合は trueキャッシュのトークンの情報を使用する場合は false。</param>
        <param name="timeout">セキュリティ トークンを取得するメッセージのタイムアウト値を指定する時間間隔。</param>
        <param name="callback">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</param>
        <param name="state">非同期操作に関する状態情報を含むユーザー定義のオブジェクト。 </param>
        <summary>非同期の操作によるセキュリティ トークンの取得を開始します。</summary>
        <returns><see cref="T:System.IAsyncResult" />トークンを取得する非同期操作を参照するオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetWebToken">
      <MemberSignature Language="C#" Value="public IAsyncResult BeginGetWebToken (string appliesTo, string action, bool bypassCache, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.IAsyncResult BeginGetWebToken(string appliesTo, string action, bool bypassCache, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.BeginGetWebToken(System.String,System.String,System.Boolean,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function BeginGetWebToken (appliesTo As String, action As String, bypassCache As Boolean, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="member this.BeginGetWebToken : string * string * bool * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="tokenProvider.BeginGetWebToken (appliesTo, action, bypassCache, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appliesTo" Type="System.String" />
        <Parameter Name="action" Type="System.String" />
        <Parameter Name="bypassCache" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="appliesTo">トークンが適用される URI。</param>
        <param name="action">要求された操作。</param>
        <param name="bypassCache">キャッシュ内の既存のトークン情報を無視する場合は trueキャッシュのトークンの情報を使用する場合は false。</param>
        <param name="timeout">セキュリティ トークンを取得するメッセージのタイムアウト値を指定する時間間隔。</param>
        <param name="callback">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</param>
        <param name="state">非同期操作に関する状態情報を含むユーザー定義のオブジェクト。 </param>
        <summary>Web トークンを取得する非同期操作を開始します。</summary>
        <returns><see cref="T:System.IAsyncResult" /> Web トークンを取得する非同期操作を参照するオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BuildKey">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.ServiceBus.TokenProvider.Key BuildKey (string appliesTo, string action);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.TokenProvider/Key BuildKey(string appliesTo, string action) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.BuildKey(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function BuildKey (appliesTo As String, action As String) As TokenProvider.Key" />
      <MemberSignature Language="F#" Value="abstract member BuildKey : string * string -&gt; Microsoft.ServiceBus.TokenProvider.Key&#xA;override this.BuildKey : string * string -&gt; Microsoft.ServiceBus.TokenProvider.Key" Usage="tokenProvider.BuildKey (appliesTo, action)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider+Key</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appliesTo" Type="System.String" />
        <Parameter Name="action" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="appliesTo">アクセス トークンが適用される URI。</param>
        <param name="action">要求された操作。</param>
        <summary>トークン プロバイダーをキーを生成します。</summary>
        <returns>トークン プロバイダー用に生成されたキー。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CacheSize">
      <MemberSignature Language="C#" Value="public int CacheSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 CacheSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.TokenProvider.CacheSize" />
      <MemberSignature Language="VB.NET" Value="Public Property CacheSize As Integer" />
      <MemberSignature Language="F#" Value="member this.CacheSize : int with get, set" Usage="Microsoft.ServiceBus.TokenProvider.CacheSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはキャッシュのサイズを設定します。</summary>
        <value>キャッシュのサイズ。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CacheTokens">
      <MemberSignature Language="C#" Value="public bool CacheTokens { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool CacheTokens" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.TokenProvider.CacheTokens" />
      <MemberSignature Language="VB.NET" Value="Public Property CacheTokens As Boolean" />
      <MemberSignature Language="F#" Value="member this.CacheTokens : bool with get, set" Usage="Microsoft.ServiceBus.TokenProvider.CacheTokens" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または新しいセキュリティ トークンがキャッシュされているかどうかを示す値を設定します。</summary>
        <value>新しいセキュリティ トークンはキャッシュされている場合は true。それ以外の場合は false です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clear">
      <MemberSignature Language="C#" Value="public void Clear ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Clear() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.Clear" />
      <MemberSignature Language="VB.NET" Value="Public Sub Clear ()" />
      <MemberSignature Language="F#" Value="member this.Clear : unit -&gt; unit" Usage="tokenProvider.Clear " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>トークン プロバイダーをクリアします。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAadTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateAadTokenProvider (Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate clientAssertionCertificate, Uri audience);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateAadTokenProvider(class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate clientAssertionCertificate, class System.Uri audience) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateAadTokenProvider(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate,System.Uri)" />
      <MemberSignature Language="F#" Value="static member CreateAadTokenProvider : Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate * Uri -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateAadTokenProvider (authContext, clientAssertionCertificate, audience)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientAssertionCertificate" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate" />
        <Parameter Name="audience" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="authContext">AAD の AuthenticationContext します。</param>
        <param name="clientAssertionCertificate">アサーションの証明書のクライアント資格情報でします。</param>
        <param name="audience">トークンの取得のサービス リソース URI。</param>
        <summary>Azure Active Directory のトークン プロバイダーを作成します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.TokenProvider" /> Json web トークンを返すためです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAadTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateAadTokenProvider (Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential, Uri audience);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateAadTokenProvider(class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential, class System.Uri audience) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateAadTokenProvider(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential,System.Uri)" />
      <MemberSignature Language="F#" Value="static member CreateAadTokenProvider : Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential * Uri -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateAadTokenProvider (authContext, clientCredential, audience)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientCredential" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential" />
        <Parameter Name="audience" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="authContext">AAD の AuthenticationContext します。</param>
        <param name="clientCredential">アプリの資格情報。</param>
        <param name="audience">トークンの取得のサービス リソース URI。</param>
        <summary>Azure Active Directory のトークン プロバイダーを作成します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.TokenProvider" /> Json web トークンを返すためです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAadTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateAadTokenProvider (Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential userPasswordCredential, Uri audience);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateAadTokenProvider(class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential userPasswordCredential, class System.Uri audience) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateAadTokenProvider(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential,System.Uri)" />
      <MemberSignature Language="F#" Value="static member CreateAadTokenProvider : Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * string * Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential * Uri -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateAadTokenProvider (authContext, clientId, userPasswordCredential, audience)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="userPasswordCredential" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential" />
        <Parameter Name="audience" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="authContext">AAD の AuthenticationContext します。</param>
        <param name="clientId">AAD の ClientId です。</param>
        <param name="userPasswordCredential">ユーザーのパスワード資格情報です。</param>
        <param name="audience">トークンの取得のサービス リソース URI。</param>
        <summary>Azure Active Directory のトークン プロバイダーを作成します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.TokenProvider" /> Json web トークンを返すためです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAadTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateAadTokenProvider (Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters platformParameters, Uri audience);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateAadTokenProvider(class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters platformParameters, class System.Uri audience) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateAadTokenProvider(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateAadTokenProvider (authContext As AuthenticationContext, clientId As String, redirectUri As Uri, platformParameters As IPlatformParameters, audience As Uri) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateAadTokenProvider : Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters * Uri -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateAadTokenProvider (authContext, clientId, redirectUri, platformParameters, audience)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.Uri" />
        <Parameter Name="platformParameters" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters" />
        <Parameter Name="audience" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="authContext">AAD の AuthenticationContext します。</param>
        <param name="clientId">AAD の ClientId です。</param>
        <param name="redirectUri">クライアント アプリで redrectUri です。</param>
        <param name="platformParameters">プラットフォームのパラメーター</param>
        <param name="audience">トークンの取得のサービス リソース URI。</param>
        <summary>Azure Active Directory のトークン プロバイダーを作成します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.TokenProvider" /> Json web トークンを返すためです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAadTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateAadTokenProvider (Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters platformParameters, Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userIdentifier, Uri audience);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateAadTokenProvider(class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters platformParameters, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userIdentifier, class System.Uri audience) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateAadTokenProvider(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier,System.Uri)" />
      <MemberSignature Language="F#" Value="static member CreateAadTokenProvider : Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters * Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier * Uri -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateAadTokenProvider (authContext, clientId, redirectUri, platformParameters, userIdentifier, audience)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.Uri" />
        <Parameter Name="platformParameters" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters" />
        <Parameter Name="userIdentifier" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />
        <Parameter Name="audience" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="authContext">AAD の AuthenticationContext します。</param>
        <param name="clientId">AAD の ClientId です。</param>
        <param name="redirectUri">クライアント アプリで redrectUri です。</param>
        <param name="platformParameters">プラットフォームのパラメーター</param>
        <param name="userIdentifier">ユーザーの識別子</param>
        <param name="audience">トークンの取得のサービス リソース URI。</param>
        <summary>Azure Active Directory のトークン プロバイダーを作成します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.TokenProvider" /> Json web トークンを返すためです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateManagedServiceIdentityTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateManagedServiceIdentityTokenProvider (Uri audience);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateManagedServiceIdentityTokenProvider(class System.Uri audience) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateManagedServiceIdentityTokenProvider(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateManagedServiceIdentityTokenProvider (audience As Uri) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateManagedServiceIdentityTokenProvider : Uri -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateManagedServiceIdentityTokenProvider audience" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="audience" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="audience">トークンの取得のサービス リソース URI。</param>
        <summary>Azure 管理サービス Id のトークン プロバイダーを作成します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.TokenProvider" /> Json web トークンを返すためです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOAuthTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateOAuthTokenProvider (System.Collections.Generic.IEnumerable&lt;Uri&gt; stsUris, System.Net.NetworkCredential credential);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateOAuthTokenProvider(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; stsUris, class System.Net.NetworkCredential credential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateOAuthTokenProvider(System.Collections.Generic.IEnumerable{System.Uri},System.Net.NetworkCredential)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateOAuthTokenProvider (stsUris As IEnumerable(Of Uri), credential As NetworkCredential) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateOAuthTokenProvider : seq&lt;Uri&gt; * System.Net.NetworkCredential -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateOAuthTokenProvider (stsUris, credential)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="stsUris" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="credential" Type="System.Net.NetworkCredential" />
      </Parameters>
      <Docs>
        <param name="stsUris">セキュリティ トークン サービス (STS) の Uri。</param>
        <param name="credential">ユーザーの資格情報。</param>
        <summary>OAuth (承認のオープン標準) トークン プロバイダーを作成します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.TokenProvider" /> OAuth トークンを返すためです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSamlTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateSamlTokenProvider (string samlToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateSamlTokenProvider(string samlToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateSamlTokenProvider(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSamlTokenProvider (samlToken As String) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSamlTokenProvider : string -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateSamlTokenProvider samlToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="samlToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="samlToken">SAML トークンを表す文字列。</param>
        <summary>指定した SAML トークンには、SAML トークン プロバイダーを作成します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.TokenProvider" /> SAML トークンを返すためです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSamlTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateSamlTokenProvider (string samlToken, Microsoft.ServiceBus.TokenScope tokenScope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateSamlTokenProvider(string samlToken, valuetype Microsoft.ServiceBus.TokenScope tokenScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateSamlTokenProvider(System.String,Microsoft.ServiceBus.TokenScope)" />
      <MemberSignature Language="F#" Value="static member CreateSamlTokenProvider : string * Microsoft.ServiceBus.TokenScope -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateSamlTokenProvider (samlToken, tokenScope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="samlToken" Type="System.String" />
        <Parameter Name="tokenScope" Type="Microsoft.ServiceBus.TokenScope" />
      </Parameters>
      <Docs>
        <param name="samlToken">SAML トークンを表す文字列。</param>
        <param name="tokenScope">プロバイダーに関連付けられているトークンのスコープです。</param>
        <summary>指定した SAML トークンおよびスコープを持つ SAML トークン プロバイダーを作成します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.TokenProvider" /> SAML トークンを返すためです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSamlTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateSamlTokenProvider (string samlToken, Uri stsUri);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateSamlTokenProvider(string samlToken, class System.Uri stsUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateSamlTokenProvider(System.String,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSamlTokenProvider (samlToken As String, stsUri As Uri) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSamlTokenProvider : string * Uri -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateSamlTokenProvider (samlToken, stsUri)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="samlToken" Type="System.String" />
        <Parameter Name="stsUri" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="samlToken">SAML トークンを表す文字列。</param>
        <param name="stsUri">セキュリティ トークン サービス (STS) の URI。</param>
        <summary>指定した SAML トークンおよびセキュリティ トークン サービス (STS) の URI を使用する SAML トークン プロバイダーを作成します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.TokenProvider" /> SAML トークンを返すためです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSamlTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateSamlTokenProvider (string samlToken, Uri stsUri, Microsoft.ServiceBus.TokenScope tokenScope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateSamlTokenProvider(string samlToken, class System.Uri stsUri, valuetype Microsoft.ServiceBus.TokenScope tokenScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateSamlTokenProvider(System.String,System.Uri,Microsoft.ServiceBus.TokenScope)" />
      <MemberSignature Language="F#" Value="static member CreateSamlTokenProvider : string * Uri * Microsoft.ServiceBus.TokenScope -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateSamlTokenProvider (samlToken, stsUri, tokenScope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="samlToken" Type="System.String" />
        <Parameter Name="stsUri" Type="System.Uri" />
        <Parameter Name="tokenScope" Type="Microsoft.ServiceBus.TokenScope" />
      </Parameters>
      <Docs>
        <param name="samlToken">SAML トークンを表す文字列。</param>
        <param name="stsUri">セキュリティ トークン サービス (STS) の URI。</param>
        <param name="tokenScope">プロバイダーに関連付けられているトークンのスコープです。</param>
        <summary>指定した SAML トークン、セキュリティ トークン サービス (STS) とトークンのスコープの URI を SAML トークン プロバイダーを作成します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.TokenProvider" /> SAML トークンを返すためです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSamlTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateSamlTokenProvider (string samlToken, Uri stsUri, int cacheSize);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateSamlTokenProvider(string samlToken, class System.Uri stsUri, int32 cacheSize) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateSamlTokenProvider(System.String,System.Uri,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSamlTokenProvider (samlToken As String, stsUri As Uri, cacheSize As Integer) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSamlTokenProvider : string * Uri * int -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateSamlTokenProvider (samlToken, stsUri, cacheSize)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="samlToken" Type="System.String" />
        <Parameter Name="stsUri" Type="System.Uri" />
        <Parameter Name="cacheSize" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="samlToken">SAML トークンを表す文字列。</param>
        <param name="stsUri">セキュリティ トークン サービス (STS) の URI。</param>
        <param name="cacheSize">キャッシュのサイズ。</param>
        <summary>指定した SAML トークン、セキュリティ トークン サービス (STS) およびキャッシュのサイズの URI を SAML トークン プロバイダーを作成します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.TokenProvider" /> SAML トークンを返すためです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSamlTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateSamlTokenProvider (string samlToken, Uri stsUri, int cacheSize, Microsoft.ServiceBus.TokenScope tokenScope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateSamlTokenProvider(string samlToken, class System.Uri stsUri, int32 cacheSize, valuetype Microsoft.ServiceBus.TokenScope tokenScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateSamlTokenProvider(System.String,System.Uri,System.Int32,Microsoft.ServiceBus.TokenScope)" />
      <MemberSignature Language="F#" Value="static member CreateSamlTokenProvider : string * Uri * int * Microsoft.ServiceBus.TokenScope -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateSamlTokenProvider (samlToken, stsUri, cacheSize, tokenScope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="samlToken" Type="System.String" />
        <Parameter Name="stsUri" Type="System.Uri" />
        <Parameter Name="cacheSize" Type="System.Int32" />
        <Parameter Name="tokenScope" Type="Microsoft.ServiceBus.TokenScope" />
      </Parameters>
      <Docs>
        <param name="samlToken">SAML トークンを表す文字列。</param>
        <param name="stsUri">セキュリティ トークン サービス (STS) の URI。</param>
        <param name="cacheSize">キャッシュのサイズ。</param>
        <param name="tokenScope">プロバイダーに関連付けられているトークンのスコープです。</param>
        <summary>指定した SAML トークン、セキュリティ トークン サービス (STS)、キャッシュのサイズとトークンのスコープの URI を SAML トークン プロバイダーを作成します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.TokenProvider" /> SAML トークンを返すためです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedAccessSignatureTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateSharedAccessSignatureTokenProvider (string sharedAccessSignature);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateSharedAccessSignatureTokenProvider(string sharedAccessSignature) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateSharedAccessSignatureTokenProvider(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSharedAccessSignatureTokenProvider (sharedAccessSignature As String) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSharedAccessSignatureTokenProvider : string -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateSharedAccessSignatureTokenProvider sharedAccessSignature" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sharedAccessSignature" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sharedAccessSignature">共有アクセス署名します。</param>
        <summary>指定した shared access signature を使用してトークン プロバイダーにアクセスを許可する URL を作成します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.TokenProvider" /> を返します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedAccessSignatureTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateSharedAccessSignatureTokenProvider (string keyName, string sharedAccessKey);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateSharedAccessSignatureTokenProvider(string keyName, string sharedAccessKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateSharedAccessSignatureTokenProvider(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSharedAccessSignatureTokenProvider (keyName As String, sharedAccessKey As String) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSharedAccessSignatureTokenProvider : string * string -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateSharedAccessSignatureTokenProvider (keyName, sharedAccessKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="sharedAccessKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="keyName">キー名。</param>
        <param name="sharedAccessKey">共有アクセス キー。</param>
        <summary>指定したキー名と共有アクセス キーを持つトークン プロバイダーへのアクセスを許可する URL を作成します。</summary>
        <returns>トークン プロバイダーへのアクセスを許可する作成された URL です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedAccessSignatureTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateSharedAccessSignatureTokenProvider (string keyName, string sharedAccessKey, Microsoft.ServiceBus.TokenScope tokenScope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateSharedAccessSignatureTokenProvider(string keyName, string sharedAccessKey, valuetype Microsoft.ServiceBus.TokenScope tokenScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateSharedAccessSignatureTokenProvider(System.String,System.String,Microsoft.ServiceBus.TokenScope)" />
      <MemberSignature Language="F#" Value="static member CreateSharedAccessSignatureTokenProvider : string * string * Microsoft.ServiceBus.TokenScope -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateSharedAccessSignatureTokenProvider (keyName, sharedAccessKey, tokenScope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="sharedAccessKey" Type="System.String" />
        <Parameter Name="tokenScope" Type="Microsoft.ServiceBus.TokenScope" />
      </Parameters>
      <Docs>
        <param name="keyName">キー名。</param>
        <param name="sharedAccessKey">共有アクセス キー。</param>
        <param name="tokenScope">プロバイダーに関連付けられているトークンのスコープです。</param>
        <summary>指定したキー名、共有アクセス キー トークンのスコープとトークン プロバイダーへのアクセスを許可する URL を作成します。</summary>
        <returns>トークン プロバイダーへのアクセスを許可する作成された URL です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedAccessSignatureTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateSharedAccessSignatureTokenProvider (string keyName, string sharedAccessKey, TimeSpan tokenTimeToLive);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateSharedAccessSignatureTokenProvider(string keyName, string sharedAccessKey, valuetype System.TimeSpan tokenTimeToLive) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateSharedAccessSignatureTokenProvider(System.String,System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSharedAccessSignatureTokenProvider (keyName As String, sharedAccessKey As String, tokenTimeToLive As TimeSpan) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSharedAccessSignatureTokenProvider : string * string * TimeSpan -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateSharedAccessSignatureTokenProvider (keyName, sharedAccessKey, tokenTimeToLive)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="sharedAccessKey" Type="System.String" />
        <Parameter Name="tokenTimeToLive" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="keyName">キー名。</param>
        <param name="sharedAccessKey">共有アクセス キー。</param>
        <param name="tokenTimeToLive">操作が有効である時間。</param>
        <summary>指定したキー名、共有アクセス キー トークンの時間と有効期限のトークン プロバイダーにアクセスを許可する URL を作成します。</summary>
        <returns>トークン プロバイダーへのアクセスを許可する作成された URL です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedAccessSignatureTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateSharedAccessSignatureTokenProvider (string keyName, string sharedAccessKey, TimeSpan tokenTimeToLive, Microsoft.ServiceBus.TokenScope tokenScope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateSharedAccessSignatureTokenProvider(string keyName, string sharedAccessKey, valuetype System.TimeSpan tokenTimeToLive, valuetype Microsoft.ServiceBus.TokenScope tokenScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateSharedAccessSignatureTokenProvider(System.String,System.String,System.TimeSpan,Microsoft.ServiceBus.TokenScope)" />
      <MemberSignature Language="F#" Value="static member CreateSharedAccessSignatureTokenProvider : string * string * TimeSpan * Microsoft.ServiceBus.TokenScope -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateSharedAccessSignatureTokenProvider (keyName, sharedAccessKey, tokenTimeToLive, tokenScope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="sharedAccessKey" Type="System.String" />
        <Parameter Name="tokenTimeToLive" Type="System.TimeSpan" />
        <Parameter Name="tokenScope" Type="Microsoft.ServiceBus.TokenScope" />
      </Parameters>
      <Docs>
        <param name="keyName">キー名。</param>
        <param name="sharedAccessKey">共有アクセス キー。</param>
        <param name="tokenTimeToLive">操作が有効である時間。</param>
        <param name="tokenScope">プロバイダーに関連付けられているトークンのスコープです。</param>
        <summary>トークン プロバイダーへのアクセスを許可する URL を作成します。</summary>
        <returns>トークン プロバイダーへのアクセスを許可する作成された URL です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedSecretTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateSharedSecretTokenProvider (string issuerName, byte[] issuerSecret);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateSharedSecretTokenProvider(string issuerName, unsigned int8[] issuerSecret) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateSharedSecretTokenProvider(System.String,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSharedSecretTokenProvider (issuerName As String, issuerSecret As Byte()) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSharedSecretTokenProvider : string * byte[] -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateSharedSecretTokenProvider (issuerName, issuerSecret)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="issuerSecret" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="issuerName">発行者の名前。</param>
        <param name="issuerSecret">発行者のシークレット。</param>
        <summary>共有シークレット トークン プロバイダーを作成します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.TokenProvider" />共有シークレット トークンを返すためです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedSecretTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateSharedSecretTokenProvider (string issuerName, string issuerSecret);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateSharedSecretTokenProvider(string issuerName, string issuerSecret) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateSharedSecretTokenProvider(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSharedSecretTokenProvider (issuerName As String, issuerSecret As String) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSharedSecretTokenProvider : string * string -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateSharedSecretTokenProvider (issuerName, issuerSecret)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="issuerSecret" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="issuerName">発行者の名前。</param>
        <param name="issuerSecret">発行者のシークレット。</param>
        <summary>共有シークレット トークン プロバイダーを作成します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.TokenProvider" />共有シークレット トークンを返すためです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedSecretTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateSharedSecretTokenProvider (string issuerName, byte[] issuerSecret, Microsoft.ServiceBus.TokenScope tokenScope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateSharedSecretTokenProvider(string issuerName, unsigned int8[] issuerSecret, valuetype Microsoft.ServiceBus.TokenScope tokenScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateSharedSecretTokenProvider(System.String,System.Byte[],Microsoft.ServiceBus.TokenScope)" />
      <MemberSignature Language="F#" Value="static member CreateSharedSecretTokenProvider : string * byte[] * Microsoft.ServiceBus.TokenScope -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateSharedSecretTokenProvider (issuerName, issuerSecret, tokenScope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="issuerSecret" Type="System.Byte[]" />
        <Parameter Name="tokenScope" Type="Microsoft.ServiceBus.TokenScope" />
      </Parameters>
      <Docs>
        <param name="issuerName">発行者の名前です。</param>
        <param name="issuerSecret">発行者のシークレットのセット。</param>
        <param name="tokenScope">プロバイダーに関連付けられているトークンのスコープです。</param>
        <summary>共有シークレット トークン プロバイダーを作成します。</summary>
        <returns>作成されたトークン プロバイダー。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedSecretTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateSharedSecretTokenProvider (string issuerName, byte[] issuerSecret, Uri stsUri);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateSharedSecretTokenProvider(string issuerName, unsigned int8[] issuerSecret, class System.Uri stsUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateSharedSecretTokenProvider(System.String,System.Byte[],System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSharedSecretTokenProvider (issuerName As String, issuerSecret As Byte(), stsUri As Uri) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSharedSecretTokenProvider : string * byte[] * Uri -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateSharedSecretTokenProvider (issuerName, issuerSecret, stsUri)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="issuerSecret" Type="System.Byte[]" />
        <Parameter Name="stsUri" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="issuerName">発行者の名前。</param>
        <param name="issuerSecret">発行者のシークレットのセット。</param>
        <param name="stsUri">セキュリティ トークン サービス (STS) の URI。</param>
        <summary>共有シークレット トークン プロバイダーを作成します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.TokenProvider" />共有シークレット トークンを返すためです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedSecretTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateSharedSecretTokenProvider (string issuerName, string issuerSecret, Microsoft.ServiceBus.TokenScope tokenScope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateSharedSecretTokenProvider(string issuerName, string issuerSecret, valuetype Microsoft.ServiceBus.TokenScope tokenScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateSharedSecretTokenProvider(System.String,System.String,Microsoft.ServiceBus.TokenScope)" />
      <MemberSignature Language="F#" Value="static member CreateSharedSecretTokenProvider : string * string * Microsoft.ServiceBus.TokenScope -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateSharedSecretTokenProvider (issuerName, issuerSecret, tokenScope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="issuerSecret" Type="System.String" />
        <Parameter Name="tokenScope" Type="Microsoft.ServiceBus.TokenScope" />
      </Parameters>
      <Docs>
        <param name="issuerName">発行者の名前。</param>
        <param name="issuerSecret">発行者のシークレット。</param>
        <param name="tokenScope">プロバイダーに関連付けられているトークンのスコープです。</param>
        <summary>共有シークレット トークン プロバイダーを作成します。</summary>
        <returns>作成されたトークン プロバイダー。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedSecretTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateSharedSecretTokenProvider (string issuerName, string issuerSecret, Uri stsUri);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateSharedSecretTokenProvider(string issuerName, string issuerSecret, class System.Uri stsUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateSharedSecretTokenProvider(System.String,System.String,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSharedSecretTokenProvider (issuerName As String, issuerSecret As String, stsUri As Uri) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSharedSecretTokenProvider : string * string * Uri -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateSharedSecretTokenProvider (issuerName, issuerSecret, stsUri)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="issuerSecret" Type="System.String" />
        <Parameter Name="stsUri" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="issuerName">発行者の名前。</param>
        <param name="issuerSecret">発行者のシークレット。</param>
        <param name="stsUri">セキュリティ トークン サービス (STS) の URI。</param>
        <summary>共有シークレット トークン プロバイダーを作成します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.TokenProvider" />共有シークレット トークンを返すためです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedSecretTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateSharedSecretTokenProvider (string issuerName, byte[] issuerSecret, Uri stsUri, Microsoft.ServiceBus.TokenScope tokenScope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateSharedSecretTokenProvider(string issuerName, unsigned int8[] issuerSecret, class System.Uri stsUri, valuetype Microsoft.ServiceBus.TokenScope tokenScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateSharedSecretTokenProvider(System.String,System.Byte[],System.Uri,Microsoft.ServiceBus.TokenScope)" />
      <MemberSignature Language="F#" Value="static member CreateSharedSecretTokenProvider : string * byte[] * Uri * Microsoft.ServiceBus.TokenScope -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateSharedSecretTokenProvider (issuerName, issuerSecret, stsUri, tokenScope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="issuerSecret" Type="System.Byte[]" />
        <Parameter Name="stsUri" Type="System.Uri" />
        <Parameter Name="tokenScope" Type="Microsoft.ServiceBus.TokenScope" />
      </Parameters>
      <Docs>
        <param name="issuerName">発行者の名前。</param>
        <param name="issuerSecret">発行者のシークレットのセット。</param>
        <param name="stsUri">セキュリティ トークン サービスのエンドポイントの Uri。</param>
        <param name="tokenScope">プロバイダーに関連付けられているトークンのスコープです。</param>
        <summary>共有シークレット トークン プロバイダーを作成します。</summary>
        <returns>作成されたトークン プロバイダー。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedSecretTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateSharedSecretTokenProvider (string issuerName, string issuerSecret, Uri stsUri, Microsoft.ServiceBus.TokenScope tokenScope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateSharedSecretTokenProvider(string issuerName, string issuerSecret, class System.Uri stsUri, valuetype Microsoft.ServiceBus.TokenScope tokenScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateSharedSecretTokenProvider(System.String,System.String,System.Uri,Microsoft.ServiceBus.TokenScope)" />
      <MemberSignature Language="F#" Value="static member CreateSharedSecretTokenProvider : string * string * Uri * Microsoft.ServiceBus.TokenScope -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateSharedSecretTokenProvider (issuerName, issuerSecret, stsUri, tokenScope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="issuerSecret" Type="System.String" />
        <Parameter Name="stsUri" Type="System.Uri" />
        <Parameter Name="tokenScope" Type="Microsoft.ServiceBus.TokenScope" />
      </Parameters>
      <Docs>
        <param name="issuerName">発行者の名前。</param>
        <param name="issuerSecret">発行者のシークレット。</param>
        <param name="stsUri">セキュリティ トークン サービス (STS) の URI。</param>
        <param name="tokenScope">プロバイダーに関連付けられているトークンのスコープです。</param>
        <summary>共有シークレット トークン プロバイダーを作成します。</summary>
        <returns>作成されたトークン プロバイダー。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSimpleWebTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateSimpleWebTokenProvider (string token);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateSimpleWebTokenProvider(string token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateSimpleWebTokenProvider(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSimpleWebTokenProvider (token As String) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSimpleWebTokenProvider : string -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateSimpleWebTokenProvider token" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="token">単純な web トークンを表す文字列。</param>
        <summary>単純な web トークン プロバイダーを作成します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.TokenProvider" />単純な web トークンを返すためです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSimpleWebTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateSimpleWebTokenProvider (string token, Microsoft.ServiceBus.TokenScope tokenScope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateSimpleWebTokenProvider(string token, valuetype Microsoft.ServiceBus.TokenScope tokenScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateSimpleWebTokenProvider(System.String,Microsoft.ServiceBus.TokenScope)" />
      <MemberSignature Language="F#" Value="static member CreateSimpleWebTokenProvider : string * Microsoft.ServiceBus.TokenScope -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateSimpleWebTokenProvider (token, tokenScope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="System.String" />
        <Parameter Name="tokenScope" Type="Microsoft.ServiceBus.TokenScope" />
      </Parameters>
      <Docs>
        <param name="token">単純な web トークンを表す文字列。</param>
        <param name="tokenScope">プロバイダーに関連付けられているトークンのスコープです。</param>
        <summary>単純な web トークン プロバイダーを作成します。</summary>
        <returns>作成された単純な web トークン プロバイダー。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSimpleWebTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateSimpleWebTokenProvider (string token, Uri stsUri);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateSimpleWebTokenProvider(string token, class System.Uri stsUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateSimpleWebTokenProvider(System.String,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSimpleWebTokenProvider (token As String, stsUri As Uri) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSimpleWebTokenProvider : string * Uri -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateSimpleWebTokenProvider (token, stsUri)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="System.String" />
        <Parameter Name="stsUri" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="token">単純な web トークンを表す文字列。</param>
        <param name="stsUri">セキュリティ トークン サービス (STS) の URI。</param>
        <summary>単純な web トークン プロバイダーを作成します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.TokenProvider" />単純な web トークンを返すためです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSimpleWebTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateSimpleWebTokenProvider (string token, Uri stsUri, Microsoft.ServiceBus.TokenScope tokenScope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateSimpleWebTokenProvider(string token, class System.Uri stsUri, valuetype Microsoft.ServiceBus.TokenScope tokenScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateSimpleWebTokenProvider(System.String,System.Uri,Microsoft.ServiceBus.TokenScope)" />
      <MemberSignature Language="F#" Value="static member CreateSimpleWebTokenProvider : string * Uri * Microsoft.ServiceBus.TokenScope -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateSimpleWebTokenProvider (token, stsUri, tokenScope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="System.String" />
        <Parameter Name="stsUri" Type="System.Uri" />
        <Parameter Name="tokenScope" Type="Microsoft.ServiceBus.TokenScope" />
      </Parameters>
      <Docs>
        <param name="token">単純な web トークンを表す文字列。</param>
        <param name="stsUri">セキュリティ トークン サービス (STS) の URI。</param>
        <param name="tokenScope">プロバイダーに関連付けられているトークンのスコープです。</param>
        <summary>単純な web トークン プロバイダーを作成します。</summary>
        <returns>作成された単純な web トークン プロバイダー。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateWindowsTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateWindowsTokenProvider (System.Collections.Generic.IEnumerable&lt;Uri&gt; stsUris);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateWindowsTokenProvider(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; stsUris) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateWindowsTokenProvider(System.Collections.Generic.IEnumerable{System.Uri})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateWindowsTokenProvider (stsUris As IEnumerable(Of Uri)) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateWindowsTokenProvider : seq&lt;Uri&gt; -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateWindowsTokenProvider stsUris" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="stsUris" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
      </Parameters>
      <Docs>
        <param name="stsUris">セキュリティ トークン サービス (STS) の Uri。</param>
        <summary>Windows トークン プロバイダーを作成します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.TokenProvider" /> Windows トークンを返すためです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateWindowsTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateWindowsTokenProvider (System.Collections.Generic.IEnumerable&lt;Uri&gt; stsUris, System.Net.NetworkCredential credential);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateWindowsTokenProvider(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; stsUris, class System.Net.NetworkCredential credential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateWindowsTokenProvider(System.Collections.Generic.IEnumerable{System.Uri},System.Net.NetworkCredential)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateWindowsTokenProvider (stsUris As IEnumerable(Of Uri), credential As NetworkCredential) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateWindowsTokenProvider : seq&lt;Uri&gt; * System.Net.NetworkCredential -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateWindowsTokenProvider (stsUris, credential)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="stsUris" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="credential" Type="System.Net.NetworkCredential" />
      </Parameters>
      <Docs>
        <param name="stsUris">セキュリティ トークン サービス (STS) の Uri。</param>
        <param name="credential">ユーザーの資格情報。</param>
        <summary>Windows トークン プロバイダーを作成します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.TokenProvider" /> Windows トークンを返すためです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndGetToken">
      <MemberSignature Language="C#" Value="public System.IdentityModel.Tokens.SecurityToken EndGetToken (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.IdentityModel.Tokens.SecurityToken EndGetToken(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.EndGetToken(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Function EndGetToken (result As IAsyncResult) As SecurityToken" />
      <MemberSignature Language="F#" Value="member this.EndGetToken : IAsyncResult -&gt; System.IdentityModel.Tokens.SecurityToken" Usage="tokenProvider.EndGetToken result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IdentityModel.Tokens.SecurityToken</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><see cref="T:System.IAsyncResult" />トークンを取得する非同期操作を参照するオブジェクト。</param>
        <summary>非同期の操作によるセキュリティ トークンの取得を完了します。</summary>
        <returns><see cref="T:System.IdentityModel.Tokens.SecurityToken" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndGetWebToken">
      <MemberSignature Language="C#" Value="public string EndGetWebToken (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string EndGetWebToken(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.EndGetWebToken(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Function EndGetWebToken (result As IAsyncResult) As String" />
      <MemberSignature Language="F#" Value="member this.EndGetWebToken : IAsyncResult -&gt; string" Usage="tokenProvider.EndGetWebToken result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><see cref="T:System.IAsyncResult" /> Web トークンを取得する非同期操作を参照するオブジェクト。</param>
        <summary>Web トークンを取得する非同期操作を完了します。</summary>
        <returns><see cref="T:System.String" /> Web トークンを表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.IdentityModel.Tokens.SecurityToken&gt; GetTokenAsync (string appliesTo, string action, bool bypassCache, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.IdentityModel.Tokens.SecurityToken&gt; GetTokenAsync(string appliesTo, string action, bool bypassCache, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.GetTokenAsync(System.String,System.String,System.Boolean,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetTokenAsync (appliesTo As String, action As String, bypassCache As Boolean, timeout As TimeSpan) As Task(Of SecurityToken)" />
      <MemberSignature Language="F#" Value="member this.GetTokenAsync : string * string * bool * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.IdentityModel.Tokens.SecurityToken&gt;" Usage="tokenProvider.GetTokenAsync (appliesTo, action, bypassCache, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.IdentityModel.Tokens.SecurityToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appliesTo" Type="System.String" />
        <Parameter Name="action" Type="System.String" />
        <Parameter Name="bypassCache" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="appliesTo">アクセス トークンが適用される URI。</param>
        <param name="action">要求された操作。</param>
        <param name="bypassCache">キャッシュ内の既存のトークン情報を無視する場合は trueキャッシュのトークンの情報を使用する場合は false。</param>
        <param name="timeout">セキュリティ トークンを取得するメッセージのタイムアウト値を指定する時間間隔。</param>
        <summary>非同期的に、プロバイダーのトークンを取得します。</summary>
        <returns>非同期操作の結果。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetWebTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetWebTokenAsync (string appliesTo, string action, bool bypassCache, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; GetWebTokenAsync(string appliesTo, string action, bool bypassCache, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.GetWebTokenAsync(System.String,System.String,System.Boolean,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetWebTokenAsync (appliesTo As String, action As String, bypassCache As Boolean, timeout As TimeSpan) As Task(Of String)" />
      <MemberSignature Language="F#" Value="member this.GetWebTokenAsync : string * string * bool * TimeSpan -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="tokenProvider.GetWebTokenAsync (appliesTo, action, bypassCache, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appliesTo" Type="System.String" />
        <Parameter Name="action" Type="System.String" />
        <Parameter Name="bypassCache" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="appliesTo">アクセス トークンが適用される URI。</param>
        <param name="action">要求された操作。</param>
        <param name="bypassCache">キャッシュ内の既存のトークン情報を無視する場合は trueキャッシュのトークンの情報を使用する場合は false。</param>
        <param name="timeout">セキュリティ トークンを取得するメッセージのタイムアウト値を指定する時間間隔。</param>
        <summary>非同期的に、プロバイダーの web トークンを取得します。</summary>
        <returns>非同期操作の結果。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsWebTokenSupported">
      <MemberSignature Language="C#" Value="public bool IsWebTokenSupported { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsWebTokenSupported" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.TokenProvider.IsWebTokenSupported" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsWebTokenSupported As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsWebTokenSupported : bool" Usage="Microsoft.ServiceBus.TokenProvider.IsWebTokenSupported" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または web トークンをこのプロバイダーでサポートされているかどうかを示す値を設定します。</summary>
        <value>web トークンが; このプロバイダーでサポートされている場合は true。それ以外の場合は false です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NormalizeAppliesTo">
      <MemberSignature Language="C#" Value="protected virtual string NormalizeAppliesTo (string appliesTo);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance string NormalizeAppliesTo(string appliesTo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.NormalizeAppliesTo(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function NormalizeAppliesTo (appliesTo As String) As String" />
      <MemberSignature Language="F#" Value="abstract member NormalizeAppliesTo : string -&gt; string&#xA;override this.NormalizeAppliesTo : string -&gt; string" Usage="tokenProvider.NormalizeAppliesTo appliesTo" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appliesTo" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="appliesTo">アクセス トークンが適用される URI。</param>
        <summary>値は、トークン プロバイダーと同じオブジェクトを返します。</summary>
        <returns>返されるオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginGetToken">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginGetToken (string appliesTo, string action, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginGetToken(string appliesTo, string action, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.OnBeginGetToken(System.String,System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnBeginGetToken (appliesTo As String, action As String, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member OnBeginGetToken : string * string * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="tokenProvider.OnBeginGetToken (appliesTo, action, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appliesTo" Type="System.String" />
        <Parameter Name="action" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="appliesTo">アクセス トークンが適用される URI。</param>
        <param name="action">要求された操作。</param>
        <param name="timeout">セキュリティ トークンを取得するメッセージのタイムアウト値を指定する時間間隔。</param>
        <param name="callback">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</param>
        <param name="state">非同期操作に関する状態情報を含むユーザー定義のオブジェクト。 </param>
        <summary>BeginGetToken メソッドの呼び出し時に実行します。</summary>
        <returns><see cref="T:System.IAsyncResult" />トークンを取得する非同期操作を参照するオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginGetWebToken">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginGetWebToken (string appliesTo, string action, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginGetWebToken(string appliesTo, string action, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.OnBeginGetWebToken(System.String,System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnBeginGetWebToken (appliesTo As String, action As String, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member OnBeginGetWebToken : string * string * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="tokenProvider.OnBeginGetWebToken (appliesTo, action, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appliesTo" Type="System.String" />
        <Parameter Name="action" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="appliesTo">アクセス トークンが適用される URI。</param>
        <param name="action">要求された操作。</param>
        <param name="timeout">セキュリティ トークンを取得するメッセージのタイムアウト値を指定する時間間隔。</param>
        <param name="callback">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</param>
        <param name="state">非同期操作に関する状態情報を含むユーザー定義のオブジェクト。 </param>
        <summary>BeginGetWebToken メソッドの呼び出し時に実行します。</summary>
        <returns><see cref="T:System.IAsyncResult" /> Web トークンを取得する非同期操作を参照するオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndGetToken">
      <MemberSignature Language="C#" Value="protected abstract System.IdentityModel.Tokens.SecurityToken OnEndGetToken (IAsyncResult result, out DateTime cacheUntil);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IdentityModel.Tokens.SecurityToken OnEndGetToken(class System.IAsyncResult result, [out] valuetype System.DateTime&amp; cacheUntil) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.OnEndGetToken(System.IAsyncResult,System.DateTime@)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndGetToken (result As IAsyncResult, ByRef cacheUntil As DateTime) As SecurityToken" />
      <MemberSignature Language="F#" Value="abstract member OnEndGetToken : IAsyncResult *  -&gt; System.IdentityModel.Tokens.SecurityToken" Usage="tokenProvider.OnEndGetToken (result, cacheUntil)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IdentityModel.Tokens.SecurityToken</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
        <Parameter Name="cacheUntil" Type="System.DateTime&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="result"><see cref="T:System.IAsyncResult" />トークンを取得する非同期操作を参照するオブジェクト。</param>
        <param name="cacheUntil">このメソッドが戻るとき、有効期限の日付と時刻、キャッシュ内のトークンの情報が含まれています。</param>
        <summary>EndGetToken メソッドの呼び出し時に実行します。</summary>
        <returns><see cref="T:System.IdentityModel.Tokens.SecurityToken" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndGetWebToken">
      <MemberSignature Language="C#" Value="protected abstract string OnEndGetWebToken (IAsyncResult result, out DateTime cacheUntil);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance string OnEndGetWebToken(class System.IAsyncResult result, [out] valuetype System.DateTime&amp; cacheUntil) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.OnEndGetWebToken(System.IAsyncResult,System.DateTime@)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndGetWebToken (result As IAsyncResult, ByRef cacheUntil As DateTime) As String" />
      <MemberSignature Language="F#" Value="abstract member OnEndGetWebToken : IAsyncResult *  -&gt; string" Usage="tokenProvider.OnEndGetWebToken (result, cacheUntil)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
        <Parameter Name="cacheUntil" Type="System.DateTime&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="result"><see cref="T:System.IAsyncResult" /> Web トークンを取得する非同期操作を参照するオブジェクト。</param>
        <param name="cacheUntil">このメソッドが戻るとき、有効期限の日付と時刻、キャッシュ内のトークンの情報が含まれています。</param>
        <summary>EndGetWebToken メソッドの呼び出し時に実行します。</summary>
        <returns><see cref="T:System.String" /> Web トークンを表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StripQueryParameters">
      <MemberSignature Language="C#" Value="protected virtual bool StripQueryParameters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool StripQueryParameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.TokenProvider.StripQueryParameters" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable ReadOnly Property StripQueryParameters As Boolean" />
      <MemberSignature Language="F#" Value="member this.StripQueryParameters : bool" Usage="Microsoft.ServiceBus.TokenProvider.StripQueryParameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>トークン プロバイダーがクエリ パラメーターを削除するかどうかを取得します。</summary>
        <value>トークン プロバイダーはクエリ パラメーターを削除する場合は true。それ以外の場合は false です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenScope">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.TokenScope TokenScope { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.TokenScope TokenScope" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.TokenProvider.TokenScope" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TokenScope As TokenScope" />
      <MemberSignature Language="F#" Value="member this.TokenScope : Microsoft.ServiceBus.TokenScope" Usage="Microsoft.ServiceBus.TokenProvider.TokenScope" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenScope</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはプロバイダーに関連付けられているトークンのスコープを設定します。</summary>
        <value>プロバイダーに関連付けられているトークンのスコープです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>