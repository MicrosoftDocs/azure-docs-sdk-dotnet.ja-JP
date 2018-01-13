<Type Name="TokenProvider" FullName="Microsoft.Azure.NotificationHubs.TokenProvider">
  <TypeSignature Language="C#" Value="public abstract class TokenProvider" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit TokenProvider extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.TokenProvider" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class TokenProvider" />
  <TypeSignature Language="F#" Value="type TokenProvider = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="ede7e-101">セキュリティ トークン プロバイダーをいくつかのよく知られているトークン プロバイダーを返す組み込みのファクトリ メソッドを表します。</span><span class="sxs-lookup"><span data-stu-id="ede7e-101">Represents a security token provider with built-in factory methods returning some well-known token providers.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected TokenProvider (bool cacheTokens, bool supportHttpAuthToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(bool cacheTokens, bool supportHttpAuthToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.#ctor(System.Boolean,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (cacheTokens As Boolean, supportHttpAuthToken As Boolean)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.TokenProvider : bool * bool -&gt; Microsoft.Azure.NotificationHubs.TokenProvider" Usage="new Microsoft.Azure.NotificationHubs.TokenProvider (cacheTokens, supportHttpAuthToken)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="cacheTokens" Type="System.Boolean" />
        <Parameter Name="supportHttpAuthToken" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="cacheTokens"><span data-ttu-id="ede7e-102">新しいセキュリティ トークンはキャッシュされている場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="ede7e-102">true if new security tokens are being cached; otherwise, false.</span></span></param>
        <param name="supportHttpAuthToken"><span data-ttu-id="ede7e-103">web トークンが; このプロバイダーでサポートされている場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="ede7e-103">true if web token is supported by this provider; otherwise, false.</span></span></param>
        <summary><span data-ttu-id="ede7e-104"><see cref="T:Microsoft.Azure.NotificationHubs.TokenProvider" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ede7e-104">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.TokenProvider" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected TokenProvider (bool cacheTokens, bool supportHttpAuthToken, Microsoft.Azure.NotificationHubs.TokenScope tokenScope);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(bool cacheTokens, bool supportHttpAuthToken, valuetype Microsoft.Azure.NotificationHubs.TokenScope tokenScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.#ctor(System.Boolean,System.Boolean,Microsoft.Azure.NotificationHubs.TokenScope)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.TokenProvider : bool * bool * Microsoft.Azure.NotificationHubs.TokenScope -&gt; Microsoft.Azure.NotificationHubs.TokenProvider" Usage="new Microsoft.Azure.NotificationHubs.TokenProvider (cacheTokens, supportHttpAuthToken, tokenScope)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="cacheTokens" Type="System.Boolean" />
        <Parameter Name="supportHttpAuthToken" Type="System.Boolean" />
        <Parameter Name="tokenScope" Type="Microsoft.Azure.NotificationHubs.TokenScope" />
      </Parameters>
      <Docs>
        <param name="cacheTokens"><span data-ttu-id="ede7e-105">新しいセキュリティ トークンはキャッシュされている場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="ede7e-105">true if new security tokens are being cached; otherwise, false.</span></span></param>
        <param name="supportHttpAuthToken"><span data-ttu-id="ede7e-106">web トークンが; このプロバイダーでサポートされている場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="ede7e-106">true if web token is supported by this provider; otherwise, false.</span></span></param>
        <param name="tokenScope"><span data-ttu-id="ede7e-107">プロバイダーに関連付けられているトークンのスコープです。</span><span class="sxs-lookup"><span data-stu-id="ede7e-107">The token scope associated with the provider.</span></span></param>
        <summary><span data-ttu-id="ede7e-108"><see cref="T:Microsoft.Azure.NotificationHubs.TokenProvider" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ede7e-108">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.TokenProvider" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected TokenProvider (bool cacheTokens, bool supportHttpAuthToken, int cacheSize, Microsoft.Azure.NotificationHubs.TokenScope tokenScope);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(bool cacheTokens, bool supportHttpAuthToken, int32 cacheSize, valuetype Microsoft.Azure.NotificationHubs.TokenScope tokenScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.#ctor(System.Boolean,System.Boolean,System.Int32,Microsoft.Azure.NotificationHubs.TokenScope)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.TokenProvider : bool * bool * int * Microsoft.Azure.NotificationHubs.TokenScope -&gt; Microsoft.Azure.NotificationHubs.TokenProvider" Usage="new Microsoft.Azure.NotificationHubs.TokenProvider (cacheTokens, supportHttpAuthToken, cacheSize, tokenScope)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="cacheTokens" Type="System.Boolean" />
        <Parameter Name="supportHttpAuthToken" Type="System.Boolean" />
        <Parameter Name="cacheSize" Type="System.Int32" />
        <Parameter Name="tokenScope" Type="Microsoft.Azure.NotificationHubs.TokenScope" />
      </Parameters>
      <Docs>
        <param name="cacheTokens"><span data-ttu-id="ede7e-109">新しいセキュリティ トークンはキャッシュされている場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="ede7e-109">true if new security tokens are being cached; otherwise, false.</span></span></param>
        <param name="supportHttpAuthToken"><span data-ttu-id="ede7e-110">web トークンが; このプロバイダーでサポートされている場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="ede7e-110">true if web token is supported by this provider; otherwise, false.</span></span></param>
        <param name="cacheSize"><span data-ttu-id="ede7e-111">キャッシュのサイズ。</span><span class="sxs-lookup"><span data-stu-id="ede7e-111">The size of the cache.</span></span></param>
        <param name="tokenScope"><span data-ttu-id="ede7e-112">プロバイダーに関連付けられているトークンのスコープです。</span><span class="sxs-lookup"><span data-stu-id="ede7e-112">The token scope associated with the provider.</span></span></param>
        <summary><span data-ttu-id="ede7e-113"><see cref="T:Microsoft.Azure.NotificationHubs.TokenProvider" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ede7e-113">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.TokenProvider" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="ede7e-114">cacheSize</span><span class="sxs-lookup"><span data-stu-id="ede7e-114">cacheSize</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="BeginGetToken">
      <MemberSignature Language="C#" Value="public IAsyncResult BeginGetToken (string appliesTo, string action, bool bypassCache, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.IAsyncResult BeginGetToken(string appliesTo, string action, bool bypassCache, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.BeginGetToken(System.String,System.String,System.Boolean,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function BeginGetToken (appliesTo As String, action As String, bypassCache As Boolean, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="member this.BeginGetToken : string * string * bool * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="tokenProvider.BeginGetToken (appliesTo, action, bypassCache, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
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
        <param name="appliesTo"><span data-ttu-id="ede7e-115">アクセス トークンが適用される URI。</span><span class="sxs-lookup"><span data-stu-id="ede7e-115">The URI which the access token applies to.</span></span></param>
        <param name="action"><span data-ttu-id="ede7e-116">要求された操作。</span><span class="sxs-lookup"><span data-stu-id="ede7e-116">The request action.</span></span></param>
        <param name="bypassCache"><span data-ttu-id="ede7e-117">キャッシュ内の既存のトークン情報を無視する場合は trueキャッシュのトークンの情報を使用する場合は false。</span><span class="sxs-lookup"><span data-stu-id="ede7e-117">true to ignore existing token information in the cache; false to use the token information in the cache.</span></span></param>
        <param name="timeout"><span data-ttu-id="ede7e-118">セキュリティ トークンを取得するメッセージのタイムアウト値を指定する時間間隔。</span><span class="sxs-lookup"><span data-stu-id="ede7e-118">The time span that specifies the timeout value for the message that gets the security token.</span></span></param>
        <param name="callback"><span data-ttu-id="ede7e-119">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</span><span class="sxs-lookup"><span data-stu-id="ede7e-119">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="ede7e-120">非同期操作に関する状態情報を含むユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="ede7e-120">A user-defined object that contains state information about the asynchronous operation.</span></span> </param>
        <summary><span data-ttu-id="ede7e-121">非同期の操作によるセキュリティ トークンの取得を開始します。</span><span class="sxs-lookup"><span data-stu-id="ede7e-121">Begins an asynchronous operation to get a security token.</span></span></summary>
        <returns><span data-ttu-id="ede7e-122"><see cref="T:System.IAsyncResult" />トークンを取得する非同期操作を参照するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="ede7e-122">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous operation to get a token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetWebToken">
      <MemberSignature Language="C#" Value="public IAsyncResult BeginGetWebToken (string appliesTo, string action, bool bypassCache, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.IAsyncResult BeginGetWebToken(string appliesTo, string action, bool bypassCache, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.BeginGetWebToken(System.String,System.String,System.Boolean,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function BeginGetWebToken (appliesTo As String, action As String, bypassCache As Boolean, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="member this.BeginGetWebToken : string * string * bool * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="tokenProvider.BeginGetWebToken (appliesTo, action, bypassCache, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
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
        <param name="appliesTo"><span data-ttu-id="ede7e-123">トークンが適用される URI。</span><span class="sxs-lookup"><span data-stu-id="ede7e-123">The URI which the token applies to.</span></span></param>
        <param name="action"><span data-ttu-id="ede7e-124">要求された操作。</span><span class="sxs-lookup"><span data-stu-id="ede7e-124">The request action.</span></span></param>
        <param name="bypassCache"><span data-ttu-id="ede7e-125">キャッシュ内の既存のトークン情報を無視する場合は trueキャッシュのトークンの情報を使用する場合は false。</span><span class="sxs-lookup"><span data-stu-id="ede7e-125">true to ignore existing token information in the cache; false to use the token information in the cache.</span></span></param>
        <param name="timeout"><span data-ttu-id="ede7e-126">セキュリティ トークンを取得するメッセージのタイムアウト値を指定する時間間隔。</span><span class="sxs-lookup"><span data-stu-id="ede7e-126">The time span that specifies the timeout value for the message that gets the security token.</span></span></param>
        <param name="callback"><span data-ttu-id="ede7e-127">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</span><span class="sxs-lookup"><span data-stu-id="ede7e-127">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="ede7e-128">非同期操作に関する状態情報を含むユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="ede7e-128">A user-defined object that contains state information about the asynchronous operation.</span></span> </param>
        <summary><span data-ttu-id="ede7e-129">Web トークンを取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="ede7e-129">Begins an asynchronous operation to get a web token.</span></span></summary>
        <returns><span data-ttu-id="ede7e-130"><see cref="T:System.IAsyncResult" /> Web トークンを取得する非同期操作を参照するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="ede7e-130">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous operation to get a web token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BuildKey">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.Azure.NotificationHubs.TokenProvider.Key BuildKey (string appliesTo, string action);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.Azure.NotificationHubs.TokenProvider/Key BuildKey(string appliesTo, string action) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.BuildKey(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function BuildKey (appliesTo As String, action As String) As TokenProvider.Key" />
      <MemberSignature Language="F#" Value="abstract member BuildKey : string * string -&gt; Microsoft.Azure.NotificationHubs.TokenProvider.Key&#xA;override this.BuildKey : string * string -&gt; Microsoft.Azure.NotificationHubs.TokenProvider.Key" Usage="tokenProvider.BuildKey (appliesTo, action)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.TokenProvider+Key</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appliesTo" Type="System.String" />
        <Parameter Name="action" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="appliesTo"><span data-ttu-id="ede7e-131">アクセス トークンが適用される URI。</span><span class="sxs-lookup"><span data-stu-id="ede7e-131">The URI which the access token applies to.</span></span></param>
        <param name="action"><span data-ttu-id="ede7e-132">要求された操作。</span><span class="sxs-lookup"><span data-stu-id="ede7e-132">The request action.</span></span></param>
        <summary><span data-ttu-id="ede7e-133">トークン プロバイダーをキーを生成します。</span><span class="sxs-lookup"><span data-stu-id="ede7e-133">Generates a key for the token provider.</span></span></summary>
        <returns><span data-ttu-id="ede7e-134">トークン プロバイダー用に生成されたキー。</span><span class="sxs-lookup"><span data-stu-id="ede7e-134">A generated key for the token provider.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CacheSize">
      <MemberSignature Language="C#" Value="public int CacheSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 CacheSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.TokenProvider.CacheSize" />
      <MemberSignature Language="VB.NET" Value="Public Property CacheSize As Integer" />
      <MemberSignature Language="F#" Value="member this.CacheSize : int with get, set" Usage="Microsoft.Azure.NotificationHubs.TokenProvider.CacheSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="ede7e-135">取得またはキャッシュのサイズを設定します。</span><span class="sxs-lookup"><span data-stu-id="ede7e-135">Gets or sets the size of the cache.</span></span></summary>
        <value><span data-ttu-id="ede7e-136">キャッシュのサイズ。</span><span class="sxs-lookup"><span data-stu-id="ede7e-136">The size of the cache.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CacheTokens">
      <MemberSignature Language="C#" Value="public bool CacheTokens { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool CacheTokens" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.TokenProvider.CacheTokens" />
      <MemberSignature Language="VB.NET" Value="Public Property CacheTokens As Boolean" />
      <MemberSignature Language="F#" Value="member this.CacheTokens : bool with get, set" Usage="Microsoft.Azure.NotificationHubs.TokenProvider.CacheTokens" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="ede7e-137">取得または新しいセキュリティ トークンがキャッシュされているかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="ede7e-137">Gets or sets a value that indicates whether new security tokens are being cached.</span></span></summary>
        <value><span data-ttu-id="ede7e-138">新しいセキュリティ トークンはキャッシュされている場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="ede7e-138">true if new security tokens are being cached; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clear">
      <MemberSignature Language="C#" Value="public void Clear ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Clear() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.Clear" />
      <MemberSignature Language="VB.NET" Value="Public Sub Clear ()" />
      <MemberSignature Language="F#" Value="member this.Clear : unit -&gt; unit" Usage="tokenProvider.Clear " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="ede7e-139">トークン プロバイダーをクリアします。</span><span class="sxs-lookup"><span data-stu-id="ede7e-139">Clears the token provider.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOAuthTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.TokenProvider CreateOAuthTokenProvider (System.Collections.Generic.IEnumerable&lt;Uri&gt; stsUris, System.Net.NetworkCredential credential);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.TokenProvider CreateOAuthTokenProvider(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; stsUris, class System.Net.NetworkCredential credential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.CreateOAuthTokenProvider(System.Collections.Generic.IEnumerable{System.Uri},System.Net.NetworkCredential)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateOAuthTokenProvider (stsUris As IEnumerable(Of Uri), credential As NetworkCredential) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateOAuthTokenProvider : seq&lt;Uri&gt; * System.Net.NetworkCredential -&gt; Microsoft.Azure.NotificationHubs.TokenProvider" Usage="Microsoft.Azure.NotificationHubs.TokenProvider.CreateOAuthTokenProvider (stsUris, credential)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="stsUris" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="credential" Type="System.Net.NetworkCredential" />
      </Parameters>
      <Docs>
        <param name="stsUris"><span data-ttu-id="ede7e-140">セキュリティ トークン サービス (STS) の Uri。</span><span class="sxs-lookup"><span data-stu-id="ede7e-140">The URIs of the Security Token Service (STS).</span></span></param>
        <param name="credential"><span data-ttu-id="ede7e-141">ユーザーの資格情報。</span><span class="sxs-lookup"><span data-stu-id="ede7e-141">The user credential.</span></span></param>
        <summary><span data-ttu-id="ede7e-142">OAuth (承認のオープン標準) トークン プロバイダーを作成します。</span><span class="sxs-lookup"><span data-stu-id="ede7e-142">Creates an OAuth (open standard for authorization) token provider.</span></span></summary>
        <returns><span data-ttu-id="ede7e-143"><see cref="T:Microsoft.Azure.NotificationHubs.TokenProvider" /> OAuth トークンを返すためです。</span><span class="sxs-lookup"><span data-stu-id="ede7e-143">The <see cref="T:Microsoft.Azure.NotificationHubs.TokenProvider" /> for returning OAuth token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedAccessSignatureTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.TokenProvider CreateSharedAccessSignatureTokenProvider (string sharedAccessSignature);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.TokenProvider CreateSharedAccessSignatureTokenProvider(string sharedAccessSignature) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.CreateSharedAccessSignatureTokenProvider(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSharedAccessSignatureTokenProvider (sharedAccessSignature As String) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSharedAccessSignatureTokenProvider : string -&gt; Microsoft.Azure.NotificationHubs.TokenProvider" Usage="Microsoft.Azure.NotificationHubs.TokenProvider.CreateSharedAccessSignatureTokenProvider sharedAccessSignature" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sharedAccessSignature" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sharedAccessSignature"><span data-ttu-id="ede7e-144">共有アクセス署名</span><span class="sxs-lookup"><span data-stu-id="ede7e-144">The shared access signature</span></span></param>
        <summary>
            <span data-ttu-id="ede7e-145">SharedAccessSignature に基づいて TokenProvider を構築します。</span><span class="sxs-lookup"><span data-stu-id="ede7e-145">Construct a TokenProvider based on a sharedAccessSignature.</span></span>
            </summary>
        <returns><span data-ttu-id="ede7e-146">共有アクセス署名を使用して初期化 TokenProvider</span><span class="sxs-lookup"><span data-stu-id="ede7e-146">A TokenProvider initialized with the shared access signature</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedAccessSignatureTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.TokenProvider CreateSharedAccessSignatureTokenProvider (string keyName, string sharedAccessKey);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.TokenProvider CreateSharedAccessSignatureTokenProvider(string keyName, string sharedAccessKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.CreateSharedAccessSignatureTokenProvider(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSharedAccessSignatureTokenProvider (keyName As String, sharedAccessKey As String) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSharedAccessSignatureTokenProvider : string * string -&gt; Microsoft.Azure.NotificationHubs.TokenProvider" Usage="Microsoft.Azure.NotificationHubs.TokenProvider.CreateSharedAccessSignatureTokenProvider (keyName, sharedAccessKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="sharedAccessKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="keyName"><span data-ttu-id="ede7e-147">キー名。</span><span class="sxs-lookup"><span data-stu-id="ede7e-147">The key name.</span></span></param>
        <param name="sharedAccessKey"><span data-ttu-id="ede7e-148">共有アクセス キー。</span><span class="sxs-lookup"><span data-stu-id="ede7e-148">The shared access key.</span></span></param>
        <summary><span data-ttu-id="ede7e-149">指定したキー名と共有アクセス キーを持つトークン プロバイダーにアクセスを許可する URL を作成します。</span><span class="sxs-lookup"><span data-stu-id="ede7e-149">Creates a URL that grants access to token provider with specified key name and shared access key.</span></span></summary>
        <returns><span data-ttu-id="ede7e-150">トークン プロバイダーへのアクセスを許可する作成された URL です。</span><span class="sxs-lookup"><span data-stu-id="ede7e-150">The created URL that grants access to token provider.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedAccessSignatureTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.TokenProvider CreateSharedAccessSignatureTokenProvider (string keyName, string sharedAccessKey, Microsoft.Azure.NotificationHubs.TokenScope tokenScope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.TokenProvider CreateSharedAccessSignatureTokenProvider(string keyName, string sharedAccessKey, valuetype Microsoft.Azure.NotificationHubs.TokenScope tokenScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.CreateSharedAccessSignatureTokenProvider(System.String,System.String,Microsoft.Azure.NotificationHubs.TokenScope)" />
      <MemberSignature Language="F#" Value="static member CreateSharedAccessSignatureTokenProvider : string * string * Microsoft.Azure.NotificationHubs.TokenScope -&gt; Microsoft.Azure.NotificationHubs.TokenProvider" Usage="Microsoft.Azure.NotificationHubs.TokenProvider.CreateSharedAccessSignatureTokenProvider (keyName, sharedAccessKey, tokenScope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="sharedAccessKey" Type="System.String" />
        <Parameter Name="tokenScope" Type="Microsoft.Azure.NotificationHubs.TokenScope" />
      </Parameters>
      <Docs>
        <param name="keyName"><span data-ttu-id="ede7e-151">キー名。</span><span class="sxs-lookup"><span data-stu-id="ede7e-151">The key name.</span></span></param>
        <param name="sharedAccessKey"><span data-ttu-id="ede7e-152">共有アクセス キー。</span><span class="sxs-lookup"><span data-stu-id="ede7e-152">The shared access key.</span></span></param>
        <param name="tokenScope"><span data-ttu-id="ede7e-153">プロバイダーに関連付けられているトークンのスコープです。</span><span class="sxs-lookup"><span data-stu-id="ede7e-153">The token scope associated with the provider.</span></span></param>
        <summary><span data-ttu-id="ede7e-154">指定したキー名、共有アクセス キーとトークンのスコープを持つトークン プロバイダーにアクセスを許可する URL を作成します。</span><span class="sxs-lookup"><span data-stu-id="ede7e-154">Creates a URL that grants access to token provider with specified key name, shared access key and token scope.</span></span></summary>
        <returns><span data-ttu-id="ede7e-155">トークン プロバイダーへのアクセスを許可する作成された URL です。</span><span class="sxs-lookup"><span data-stu-id="ede7e-155">The created URL that grants access to token provider.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedAccessSignatureTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.TokenProvider CreateSharedAccessSignatureTokenProvider (string keyName, string sharedAccessKey, TimeSpan tokenTimeToLive);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.TokenProvider CreateSharedAccessSignatureTokenProvider(string keyName, string sharedAccessKey, valuetype System.TimeSpan tokenTimeToLive) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.CreateSharedAccessSignatureTokenProvider(System.String,System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSharedAccessSignatureTokenProvider (keyName As String, sharedAccessKey As String, tokenTimeToLive As TimeSpan) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSharedAccessSignatureTokenProvider : string * string * TimeSpan -&gt; Microsoft.Azure.NotificationHubs.TokenProvider" Usage="Microsoft.Azure.NotificationHubs.TokenProvider.CreateSharedAccessSignatureTokenProvider (keyName, sharedAccessKey, tokenTimeToLive)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="sharedAccessKey" Type="System.String" />
        <Parameter Name="tokenTimeToLive" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="keyName"><span data-ttu-id="ede7e-156">キー名。</span><span class="sxs-lookup"><span data-stu-id="ede7e-156">The key name.</span></span></param>
        <param name="sharedAccessKey"><span data-ttu-id="ede7e-157">共有アクセス キー。</span><span class="sxs-lookup"><span data-stu-id="ede7e-157">The shared access key.</span></span></param>
        <param name="tokenTimeToLive"><span data-ttu-id="ede7e-158">操作が有効である時間。</span><span class="sxs-lookup"><span data-stu-id="ede7e-158">The time for which the operation remains valid.</span></span></param>
        <summary><span data-ttu-id="ede7e-159">指定したキー名、共有アクセス キー トークンの時刻と有効期限のトークン プロバイダーにアクセスを許可する URL を作成します。</span><span class="sxs-lookup"><span data-stu-id="ede7e-159">Creates a URL that grants access to token provider with specified key name, shared access key and token time to live.</span></span></summary>
        <returns><span data-ttu-id="ede7e-160">トークン プロバイダーへのアクセスを許可する作成された URL です。</span><span class="sxs-lookup"><span data-stu-id="ede7e-160">The created URL that grants access to token provider.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedAccessSignatureTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.TokenProvider CreateSharedAccessSignatureTokenProvider (string keyName, string sharedAccessKey, TimeSpan tokenTimeToLive, Microsoft.Azure.NotificationHubs.TokenScope tokenScope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.TokenProvider CreateSharedAccessSignatureTokenProvider(string keyName, string sharedAccessKey, valuetype System.TimeSpan tokenTimeToLive, valuetype Microsoft.Azure.NotificationHubs.TokenScope tokenScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.CreateSharedAccessSignatureTokenProvider(System.String,System.String,System.TimeSpan,Microsoft.Azure.NotificationHubs.TokenScope)" />
      <MemberSignature Language="F#" Value="static member CreateSharedAccessSignatureTokenProvider : string * string * TimeSpan * Microsoft.Azure.NotificationHubs.TokenScope -&gt; Microsoft.Azure.NotificationHubs.TokenProvider" Usage="Microsoft.Azure.NotificationHubs.TokenProvider.CreateSharedAccessSignatureTokenProvider (keyName, sharedAccessKey, tokenTimeToLive, tokenScope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="sharedAccessKey" Type="System.String" />
        <Parameter Name="tokenTimeToLive" Type="System.TimeSpan" />
        <Parameter Name="tokenScope" Type="Microsoft.Azure.NotificationHubs.TokenScope" />
      </Parameters>
      <Docs>
        <param name="keyName"><span data-ttu-id="ede7e-161">キー名。</span><span class="sxs-lookup"><span data-stu-id="ede7e-161">The key name.</span></span></param>
        <param name="sharedAccessKey"><span data-ttu-id="ede7e-162">共有アクセス キー。</span><span class="sxs-lookup"><span data-stu-id="ede7e-162">The shared access key.</span></span></param>
        <param name="tokenTimeToLive"><span data-ttu-id="ede7e-163">操作が有効である時間。</span><span class="sxs-lookup"><span data-stu-id="ede7e-163">The time for which the operation remains valid.</span></span></param>
        <param name="tokenScope"><span data-ttu-id="ede7e-164">プロバイダーに関連付けられているトークンのスコープです。</span><span class="sxs-lookup"><span data-stu-id="ede7e-164">The token scope associated with the provider.</span></span></param>
        <summary><span data-ttu-id="ede7e-165">トークン プロバイダーへのアクセスを許可する URL を作成します。</span><span class="sxs-lookup"><span data-stu-id="ede7e-165">Creates a URL that grants access to token provider.</span></span></summary>
        <returns><span data-ttu-id="ede7e-166">トークン プロバイダーへのアクセスを許可する作成された URL です。</span><span class="sxs-lookup"><span data-stu-id="ede7e-166">The created URL that grants access to token provider.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedSecretTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.TokenProvider CreateSharedSecretTokenProvider (string issuerName, byte[] issuerSecret);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.TokenProvider CreateSharedSecretTokenProvider(string issuerName, unsigned int8[] issuerSecret) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.CreateSharedSecretTokenProvider(System.String,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSharedSecretTokenProvider (issuerName As String, issuerSecret As Byte()) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSharedSecretTokenProvider : string * byte[] -&gt; Microsoft.Azure.NotificationHubs.TokenProvider" Usage="Microsoft.Azure.NotificationHubs.TokenProvider.CreateSharedSecretTokenProvider (issuerName, issuerSecret)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="issuerSecret" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="issuerName"><span data-ttu-id="ede7e-167">発行者の名前。</span><span class="sxs-lookup"><span data-stu-id="ede7e-167">The issuer name.</span></span></param>
        <param name="issuerSecret"><span data-ttu-id="ede7e-168">発行者のシークレット。</span><span class="sxs-lookup"><span data-stu-id="ede7e-168">The issuer secret.</span></span></param>
        <summary><span data-ttu-id="ede7e-169">共有シークレット トークン プロバイダーを作成します。</span><span class="sxs-lookup"><span data-stu-id="ede7e-169">Creates a shared secret token provider.</span></span></summary>
        <returns><span data-ttu-id="ede7e-170"><see cref="T:Microsoft.Azure.NotificationHubs.TokenProvider" />共有シークレット トークンを返すためです。</span><span class="sxs-lookup"><span data-stu-id="ede7e-170">The <see cref="T:Microsoft.Azure.NotificationHubs.TokenProvider" /> for returning shared secret token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedSecretTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.TokenProvider CreateSharedSecretTokenProvider (string issuerName, string issuerSecret);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.TokenProvider CreateSharedSecretTokenProvider(string issuerName, string issuerSecret) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.CreateSharedSecretTokenProvider(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSharedSecretTokenProvider (issuerName As String, issuerSecret As String) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSharedSecretTokenProvider : string * string -&gt; Microsoft.Azure.NotificationHubs.TokenProvider" Usage="Microsoft.Azure.NotificationHubs.TokenProvider.CreateSharedSecretTokenProvider (issuerName, issuerSecret)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="issuerSecret" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="issuerName"><span data-ttu-id="ede7e-171">発行者の名前。</span><span class="sxs-lookup"><span data-stu-id="ede7e-171">The issuer name.</span></span></param>
        <param name="issuerSecret"><span data-ttu-id="ede7e-172">発行者のシークレット。</span><span class="sxs-lookup"><span data-stu-id="ede7e-172">The issuer secret.</span></span></param>
        <summary><span data-ttu-id="ede7e-173">共有シークレット トークン プロバイダーを作成します。</span><span class="sxs-lookup"><span data-stu-id="ede7e-173">Creates a shared secret token provider.</span></span></summary>
        <returns><span data-ttu-id="ede7e-174"><see cref="T:Microsoft.Azure.NotificationHubs.TokenProvider" />共有シークレット トークンを返すためです。</span><span class="sxs-lookup"><span data-stu-id="ede7e-174">The <see cref="T:Microsoft.Azure.NotificationHubs.TokenProvider" /> for returning shared secret token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedSecretTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.TokenProvider CreateSharedSecretTokenProvider (string issuerName, byte[] issuerSecret, Microsoft.Azure.NotificationHubs.TokenScope tokenScope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.TokenProvider CreateSharedSecretTokenProvider(string issuerName, unsigned int8[] issuerSecret, valuetype Microsoft.Azure.NotificationHubs.TokenScope tokenScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.CreateSharedSecretTokenProvider(System.String,System.Byte[],Microsoft.Azure.NotificationHubs.TokenScope)" />
      <MemberSignature Language="F#" Value="static member CreateSharedSecretTokenProvider : string * byte[] * Microsoft.Azure.NotificationHubs.TokenScope -&gt; Microsoft.Azure.NotificationHubs.TokenProvider" Usage="Microsoft.Azure.NotificationHubs.TokenProvider.CreateSharedSecretTokenProvider (issuerName, issuerSecret, tokenScope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="issuerSecret" Type="System.Byte[]" />
        <Parameter Name="tokenScope" Type="Microsoft.Azure.NotificationHubs.TokenScope" />
      </Parameters>
      <Docs>
        <param name="issuerName"><span data-ttu-id="ede7e-175">発行者の名前です。</span><span class="sxs-lookup"><span data-stu-id="ede7e-175">The name of the issuer.</span></span></param>
        <param name="issuerSecret"><span data-ttu-id="ede7e-176">発行者のシークレットのセット。</span><span class="sxs-lookup"><span data-stu-id="ede7e-176">The set of issuer secret.</span></span></param>
        <param name="tokenScope"><span data-ttu-id="ede7e-177">プロバイダーに関連付けられているトークンのスコープです。</span><span class="sxs-lookup"><span data-stu-id="ede7e-177">The token scope associated with the provider.</span></span></param>
        <summary><span data-ttu-id="ede7e-178">共有シークレット トークン プロバイダーを作成します。</span><span class="sxs-lookup"><span data-stu-id="ede7e-178">Creates a shared secret token provider.</span></span></summary>
        <returns><span data-ttu-id="ede7e-179">作成されたトークン プロバイダー。</span><span class="sxs-lookup"><span data-stu-id="ede7e-179">The created token provider.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedSecretTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.TokenProvider CreateSharedSecretTokenProvider (string issuerName, byte[] issuerSecret, Uri stsUri);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.TokenProvider CreateSharedSecretTokenProvider(string issuerName, unsigned int8[] issuerSecret, class System.Uri stsUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.CreateSharedSecretTokenProvider(System.String,System.Byte[],System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSharedSecretTokenProvider (issuerName As String, issuerSecret As Byte(), stsUri As Uri) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSharedSecretTokenProvider : string * byte[] * Uri -&gt; Microsoft.Azure.NotificationHubs.TokenProvider" Usage="Microsoft.Azure.NotificationHubs.TokenProvider.CreateSharedSecretTokenProvider (issuerName, issuerSecret, stsUri)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="issuerSecret" Type="System.Byte[]" />
        <Parameter Name="stsUri" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="issuerName"><span data-ttu-id="ede7e-180">発行者の名前。</span><span class="sxs-lookup"><span data-stu-id="ede7e-180">The issuer name.</span></span></param>
        <param name="issuerSecret"><span data-ttu-id="ede7e-181">発行者のシークレットのセット。</span><span class="sxs-lookup"><span data-stu-id="ede7e-181">The set of issuer secret.</span></span></param>
        <param name="stsUri"><span data-ttu-id="ede7e-182">セキュリティ トークン サービス (STS) の URI。</span><span class="sxs-lookup"><span data-stu-id="ede7e-182">The URI of the Security Token Service (STS).</span></span></param>
        <summary><span data-ttu-id="ede7e-183">共有シークレット トークン プロバイダーを作成します。</span><span class="sxs-lookup"><span data-stu-id="ede7e-183">Creates a shared secret token provider.</span></span></summary>
        <returns><span data-ttu-id="ede7e-184"><see cref="T:Microsoft.Azure.NotificationHubs.TokenProvider" />共有シークレット トークンを返すためです。</span><span class="sxs-lookup"><span data-stu-id="ede7e-184">The <see cref="T:Microsoft.Azure.NotificationHubs.TokenProvider" /> for returning shared secret token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedSecretTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.TokenProvider CreateSharedSecretTokenProvider (string issuerName, string issuerSecret, Microsoft.Azure.NotificationHubs.TokenScope tokenScope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.TokenProvider CreateSharedSecretTokenProvider(string issuerName, string issuerSecret, valuetype Microsoft.Azure.NotificationHubs.TokenScope tokenScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.CreateSharedSecretTokenProvider(System.String,System.String,Microsoft.Azure.NotificationHubs.TokenScope)" />
      <MemberSignature Language="F#" Value="static member CreateSharedSecretTokenProvider : string * string * Microsoft.Azure.NotificationHubs.TokenScope -&gt; Microsoft.Azure.NotificationHubs.TokenProvider" Usage="Microsoft.Azure.NotificationHubs.TokenProvider.CreateSharedSecretTokenProvider (issuerName, issuerSecret, tokenScope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="issuerSecret" Type="System.String" />
        <Parameter Name="tokenScope" Type="Microsoft.Azure.NotificationHubs.TokenScope" />
      </Parameters>
      <Docs>
        <param name="issuerName"><span data-ttu-id="ede7e-185">発行者の名前。</span><span class="sxs-lookup"><span data-stu-id="ede7e-185">The issuer name.</span></span></param>
        <param name="issuerSecret"><span data-ttu-id="ede7e-186">発行者のシークレット。</span><span class="sxs-lookup"><span data-stu-id="ede7e-186">The issuer secret.</span></span></param>
        <param name="tokenScope"><span data-ttu-id="ede7e-187">プロバイダーに関連付けられているトークンのスコープです。</span><span class="sxs-lookup"><span data-stu-id="ede7e-187">The token scope associated with the provider.</span></span></param>
        <summary><span data-ttu-id="ede7e-188">共有シークレット トークン プロバイダーを作成します。</span><span class="sxs-lookup"><span data-stu-id="ede7e-188">Creates a shared secret token provider.</span></span></summary>
        <returns><span data-ttu-id="ede7e-189">作成されたトークン プロバイダー。</span><span class="sxs-lookup"><span data-stu-id="ede7e-189">The created token provider.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedSecretTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.TokenProvider CreateSharedSecretTokenProvider (string issuerName, string issuerSecret, Uri stsUri);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.TokenProvider CreateSharedSecretTokenProvider(string issuerName, string issuerSecret, class System.Uri stsUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.CreateSharedSecretTokenProvider(System.String,System.String,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSharedSecretTokenProvider (issuerName As String, issuerSecret As String, stsUri As Uri) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSharedSecretTokenProvider : string * string * Uri -&gt; Microsoft.Azure.NotificationHubs.TokenProvider" Usage="Microsoft.Azure.NotificationHubs.TokenProvider.CreateSharedSecretTokenProvider (issuerName, issuerSecret, stsUri)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="issuerSecret" Type="System.String" />
        <Parameter Name="stsUri" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="issuerName"><span data-ttu-id="ede7e-190">発行者の名前。</span><span class="sxs-lookup"><span data-stu-id="ede7e-190">The issuer name.</span></span></param>
        <param name="issuerSecret"><span data-ttu-id="ede7e-191">発行者のシークレット。</span><span class="sxs-lookup"><span data-stu-id="ede7e-191">The issuer secret.</span></span></param>
        <param name="stsUri"><span data-ttu-id="ede7e-192">セキュリティ トークン サービス (STS) の URI。</span><span class="sxs-lookup"><span data-stu-id="ede7e-192">The URI of the Security Token Service (STS).</span></span></param>
        <summary><span data-ttu-id="ede7e-193">共有シークレット トークン プロバイダーを作成します。</span><span class="sxs-lookup"><span data-stu-id="ede7e-193">Creates a shared secret token provider.</span></span></summary>
        <returns><span data-ttu-id="ede7e-194"><see cref="T:Microsoft.Azure.NotificationHubs.TokenProvider" />共有シークレット トークンを返すためです。</span><span class="sxs-lookup"><span data-stu-id="ede7e-194">The <see cref="T:Microsoft.Azure.NotificationHubs.TokenProvider" /> for returning shared secret token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedSecretTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.TokenProvider CreateSharedSecretTokenProvider (string issuerName, byte[] issuerSecret, Uri stsUri, Microsoft.Azure.NotificationHubs.TokenScope tokenScope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.TokenProvider CreateSharedSecretTokenProvider(string issuerName, unsigned int8[] issuerSecret, class System.Uri stsUri, valuetype Microsoft.Azure.NotificationHubs.TokenScope tokenScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.CreateSharedSecretTokenProvider(System.String,System.Byte[],System.Uri,Microsoft.Azure.NotificationHubs.TokenScope)" />
      <MemberSignature Language="F#" Value="static member CreateSharedSecretTokenProvider : string * byte[] * Uri * Microsoft.Azure.NotificationHubs.TokenScope -&gt; Microsoft.Azure.NotificationHubs.TokenProvider" Usage="Microsoft.Azure.NotificationHubs.TokenProvider.CreateSharedSecretTokenProvider (issuerName, issuerSecret, stsUri, tokenScope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="issuerSecret" Type="System.Byte[]" />
        <Parameter Name="stsUri" Type="System.Uri" />
        <Parameter Name="tokenScope" Type="Microsoft.Azure.NotificationHubs.TokenScope" />
      </Parameters>
      <Docs>
        <param name="issuerName"><span data-ttu-id="ede7e-195">発行者の名前。</span><span class="sxs-lookup"><span data-stu-id="ede7e-195">The issuer name.</span></span></param>
        <param name="issuerSecret"><span data-ttu-id="ede7e-196">発行者のシークレットのセット。</span><span class="sxs-lookup"><span data-stu-id="ede7e-196">The set of issuer secret.</span></span></param>
        <param name="stsUri"><span data-ttu-id="ede7e-197">セキュリティ トークン サービスのエンドポイントの Uri。</span><span class="sxs-lookup"><span data-stu-id="ede7e-197">The Security Token Service's endpoint Uri.</span></span></param>
        <param name="tokenScope"><span data-ttu-id="ede7e-198">プロバイダーに関連付けられているトークンのスコープです。</span><span class="sxs-lookup"><span data-stu-id="ede7e-198">The token scope associated with the provider.</span></span></param>
        <summary><span data-ttu-id="ede7e-199">共有シークレット トークン プロバイダーを作成します。</span><span class="sxs-lookup"><span data-stu-id="ede7e-199">Creates a shared secret token provider.</span></span></summary>
        <returns><span data-ttu-id="ede7e-200">作成されたトークン プロバイダー。</span><span class="sxs-lookup"><span data-stu-id="ede7e-200">The created token provider.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedSecretTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.TokenProvider CreateSharedSecretTokenProvider (string issuerName, string issuerSecret, Uri stsUri, Microsoft.Azure.NotificationHubs.TokenScope tokenScope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.TokenProvider CreateSharedSecretTokenProvider(string issuerName, string issuerSecret, class System.Uri stsUri, valuetype Microsoft.Azure.NotificationHubs.TokenScope tokenScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.CreateSharedSecretTokenProvider(System.String,System.String,System.Uri,Microsoft.Azure.NotificationHubs.TokenScope)" />
      <MemberSignature Language="F#" Value="static member CreateSharedSecretTokenProvider : string * string * Uri * Microsoft.Azure.NotificationHubs.TokenScope -&gt; Microsoft.Azure.NotificationHubs.TokenProvider" Usage="Microsoft.Azure.NotificationHubs.TokenProvider.CreateSharedSecretTokenProvider (issuerName, issuerSecret, stsUri, tokenScope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="issuerSecret" Type="System.String" />
        <Parameter Name="stsUri" Type="System.Uri" />
        <Parameter Name="tokenScope" Type="Microsoft.Azure.NotificationHubs.TokenScope" />
      </Parameters>
      <Docs>
        <param name="issuerName"><span data-ttu-id="ede7e-201">発行者の名前。</span><span class="sxs-lookup"><span data-stu-id="ede7e-201">The issuer name.</span></span></param>
        <param name="issuerSecret"><span data-ttu-id="ede7e-202">発行者のシークレット。</span><span class="sxs-lookup"><span data-stu-id="ede7e-202">The issuer secret.</span></span></param>
        <param name="stsUri"><span data-ttu-id="ede7e-203">セキュリティ トークン サービス (STS) の URI。</span><span class="sxs-lookup"><span data-stu-id="ede7e-203">The URI of the Security Token Service (STS).</span></span></param>
        <param name="tokenScope"><span data-ttu-id="ede7e-204">プロバイダーに関連付けられているトークンのスコープです。</span><span class="sxs-lookup"><span data-stu-id="ede7e-204">The token scope associated with the provider.</span></span></param>
        <summary><span data-ttu-id="ede7e-205">共有シークレット トークン プロバイダーを作成します。</span><span class="sxs-lookup"><span data-stu-id="ede7e-205">Creates a shared secret token provider.</span></span></summary>
        <returns><span data-ttu-id="ede7e-206">作成されたトークン プロバイダー。</span><span class="sxs-lookup"><span data-stu-id="ede7e-206">The created token provider.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSimpleWebTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.TokenProvider CreateSimpleWebTokenProvider (string token);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.TokenProvider CreateSimpleWebTokenProvider(string token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.CreateSimpleWebTokenProvider(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSimpleWebTokenProvider (token As String) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSimpleWebTokenProvider : string -&gt; Microsoft.Azure.NotificationHubs.TokenProvider" Usage="Microsoft.Azure.NotificationHubs.TokenProvider.CreateSimpleWebTokenProvider token" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="token"><span data-ttu-id="ede7e-207">単純な web トークンを表す文字列。</span><span class="sxs-lookup"><span data-stu-id="ede7e-207">The string that represents the simple web token.</span></span></param>
        <summary><span data-ttu-id="ede7e-208">単純な web トークン プロバイダーを作成します。</span><span class="sxs-lookup"><span data-stu-id="ede7e-208">Creates a simple web token provider.</span></span></summary>
        <returns><span data-ttu-id="ede7e-209"><see cref="T:Microsoft.Azure.NotificationHubs.TokenProvider" />単純な web トークンを返すためです。</span><span class="sxs-lookup"><span data-stu-id="ede7e-209">The <see cref="T:Microsoft.Azure.NotificationHubs.TokenProvider" /> for returning simple web token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSimpleWebTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.TokenProvider CreateSimpleWebTokenProvider (string token, Microsoft.Azure.NotificationHubs.TokenScope tokenScope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.TokenProvider CreateSimpleWebTokenProvider(string token, valuetype Microsoft.Azure.NotificationHubs.TokenScope tokenScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.CreateSimpleWebTokenProvider(System.String,Microsoft.Azure.NotificationHubs.TokenScope)" />
      <MemberSignature Language="F#" Value="static member CreateSimpleWebTokenProvider : string * Microsoft.Azure.NotificationHubs.TokenScope -&gt; Microsoft.Azure.NotificationHubs.TokenProvider" Usage="Microsoft.Azure.NotificationHubs.TokenProvider.CreateSimpleWebTokenProvider (token, tokenScope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="System.String" />
        <Parameter Name="tokenScope" Type="Microsoft.Azure.NotificationHubs.TokenScope" />
      </Parameters>
      <Docs>
        <param name="token"><span data-ttu-id="ede7e-210">単純な web トークンを表す文字列。</span><span class="sxs-lookup"><span data-stu-id="ede7e-210">The string that represents the simple web token.</span></span></param>
        <param name="tokenScope"><span data-ttu-id="ede7e-211">プロバイダーに関連付けられているトークンのスコープです。</span><span class="sxs-lookup"><span data-stu-id="ede7e-211">The token scope associated with the provider.</span></span></param>
        <summary><span data-ttu-id="ede7e-212">単純な web トークン プロバイダーを作成します。</span><span class="sxs-lookup"><span data-stu-id="ede7e-212">Creates a simple web token provider.</span></span></summary>
        <returns><span data-ttu-id="ede7e-213">作成された単純な web トークン プロバイダー。</span><span class="sxs-lookup"><span data-stu-id="ede7e-213">The created simple web token provider.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSimpleWebTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.TokenProvider CreateSimpleWebTokenProvider (string token, Uri stsUri);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.TokenProvider CreateSimpleWebTokenProvider(string token, class System.Uri stsUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.CreateSimpleWebTokenProvider(System.String,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSimpleWebTokenProvider (token As String, stsUri As Uri) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSimpleWebTokenProvider : string * Uri -&gt; Microsoft.Azure.NotificationHubs.TokenProvider" Usage="Microsoft.Azure.NotificationHubs.TokenProvider.CreateSimpleWebTokenProvider (token, stsUri)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="System.String" />
        <Parameter Name="stsUri" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="token"><span data-ttu-id="ede7e-214">単純な web トークンを表す文字列。</span><span class="sxs-lookup"><span data-stu-id="ede7e-214">The string that represents the simple web token.</span></span></param>
        <param name="stsUri"><span data-ttu-id="ede7e-215">セキュリティ トークン サービス (STS) の URI。</span><span class="sxs-lookup"><span data-stu-id="ede7e-215">The URI of the Security Token Service (STS).</span></span></param>
        <summary><span data-ttu-id="ede7e-216">単純な web トークン プロバイダーを作成します。</span><span class="sxs-lookup"><span data-stu-id="ede7e-216">Creates a simple web token provider.</span></span></summary>
        <returns><span data-ttu-id="ede7e-217"><see cref="T:Microsoft.Azure.NotificationHubs.TokenProvider" />単純な web トークンを返すためです。</span><span class="sxs-lookup"><span data-stu-id="ede7e-217">The <see cref="T:Microsoft.Azure.NotificationHubs.TokenProvider" /> for returning simple web token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSimpleWebTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.TokenProvider CreateSimpleWebTokenProvider (string token, Uri stsUri, Microsoft.Azure.NotificationHubs.TokenScope tokenScope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.TokenProvider CreateSimpleWebTokenProvider(string token, class System.Uri stsUri, valuetype Microsoft.Azure.NotificationHubs.TokenScope tokenScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.CreateSimpleWebTokenProvider(System.String,System.Uri,Microsoft.Azure.NotificationHubs.TokenScope)" />
      <MemberSignature Language="F#" Value="static member CreateSimpleWebTokenProvider : string * Uri * Microsoft.Azure.NotificationHubs.TokenScope -&gt; Microsoft.Azure.NotificationHubs.TokenProvider" Usage="Microsoft.Azure.NotificationHubs.TokenProvider.CreateSimpleWebTokenProvider (token, stsUri, tokenScope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="System.String" />
        <Parameter Name="stsUri" Type="System.Uri" />
        <Parameter Name="tokenScope" Type="Microsoft.Azure.NotificationHubs.TokenScope" />
      </Parameters>
      <Docs>
        <param name="token"><span data-ttu-id="ede7e-218">単純な web トークンを表す文字列。</span><span class="sxs-lookup"><span data-stu-id="ede7e-218">The string that represents the simple web token.</span></span></param>
        <param name="stsUri"><span data-ttu-id="ede7e-219">セキュリティ トークン サービス (STS) の URI。</span><span class="sxs-lookup"><span data-stu-id="ede7e-219">The URI of the Security Token Service (STS).</span></span></param>
        <param name="tokenScope"><span data-ttu-id="ede7e-220">プロバイダーに関連付けられているトークンのスコープです。</span><span class="sxs-lookup"><span data-stu-id="ede7e-220">The token scope associated with the provider.</span></span></param>
        <summary><span data-ttu-id="ede7e-221">単純な web トークン プロバイダーを作成します。</span><span class="sxs-lookup"><span data-stu-id="ede7e-221">Creates a simple web token provider.</span></span></summary>
        <returns><span data-ttu-id="ede7e-222">作成された単純な web トークン プロバイダー。</span><span class="sxs-lookup"><span data-stu-id="ede7e-222">The created simple web token provider.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateWindowsTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.TokenProvider CreateWindowsTokenProvider (System.Collections.Generic.IEnumerable&lt;Uri&gt; stsUris);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.TokenProvider CreateWindowsTokenProvider(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; stsUris) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.CreateWindowsTokenProvider(System.Collections.Generic.IEnumerable{System.Uri})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateWindowsTokenProvider (stsUris As IEnumerable(Of Uri)) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateWindowsTokenProvider : seq&lt;Uri&gt; -&gt; Microsoft.Azure.NotificationHubs.TokenProvider" Usage="Microsoft.Azure.NotificationHubs.TokenProvider.CreateWindowsTokenProvider stsUris" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="stsUris" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
      </Parameters>
      <Docs>
        <param name="stsUris"><span data-ttu-id="ede7e-223">セキュリティ トークン サービス (STS) の Uri。</span><span class="sxs-lookup"><span data-stu-id="ede7e-223">The URIs of the Security Token Service (STS).</span></span></param>
        <summary><span data-ttu-id="ede7e-224">Windows トークン プロバイダーを作成します。</span><span class="sxs-lookup"><span data-stu-id="ede7e-224">Creates a windows token provider.</span></span></summary>
        <returns><span data-ttu-id="ede7e-225"><see cref="T:Microsoft.Azure.NotificationHubs.TokenProvider" /> Windows トークンを返すためです。</span><span class="sxs-lookup"><span data-stu-id="ede7e-225">The <see cref="T:Microsoft.Azure.NotificationHubs.TokenProvider" /> for returning the windows token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateWindowsTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.TokenProvider CreateWindowsTokenProvider (System.Collections.Generic.IEnumerable&lt;Uri&gt; stsUris, System.Net.NetworkCredential credential);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.TokenProvider CreateWindowsTokenProvider(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; stsUris, class System.Net.NetworkCredential credential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.CreateWindowsTokenProvider(System.Collections.Generic.IEnumerable{System.Uri},System.Net.NetworkCredential)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateWindowsTokenProvider (stsUris As IEnumerable(Of Uri), credential As NetworkCredential) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateWindowsTokenProvider : seq&lt;Uri&gt; * System.Net.NetworkCredential -&gt; Microsoft.Azure.NotificationHubs.TokenProvider" Usage="Microsoft.Azure.NotificationHubs.TokenProvider.CreateWindowsTokenProvider (stsUris, credential)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="stsUris" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="credential" Type="System.Net.NetworkCredential" />
      </Parameters>
      <Docs>
        <param name="stsUris"><span data-ttu-id="ede7e-226">セキュリティ トークン サービス (STS) の Uri。</span><span class="sxs-lookup"><span data-stu-id="ede7e-226">The URIs of the Security Token Service (STS).</span></span></param>
        <param name="credential"><span data-ttu-id="ede7e-227">ユーザーの資格情報。</span><span class="sxs-lookup"><span data-stu-id="ede7e-227">The user credential.</span></span></param>
        <summary><span data-ttu-id="ede7e-228">Windows トークン プロバイダーを作成します。</span><span class="sxs-lookup"><span data-stu-id="ede7e-228">Creates a windows token provider.</span></span></summary>
        <returns><span data-ttu-id="ede7e-229"><see cref="T:Microsoft.Azure.NotificationHubs.TokenProvider" /> Windows トークンを返すためです。</span><span class="sxs-lookup"><span data-stu-id="ede7e-229">The <see cref="T:Microsoft.Azure.NotificationHubs.TokenProvider" /> for returning the windows token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndGetToken">
      <MemberSignature Language="C#" Value="public System.IdentityModel.Tokens.SecurityToken EndGetToken (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.IdentityModel.Tokens.SecurityToken EndGetToken(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.EndGetToken(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Function EndGetToken (result As IAsyncResult) As SecurityToken" />
      <MemberSignature Language="F#" Value="member this.EndGetToken : IAsyncResult -&gt; System.IdentityModel.Tokens.SecurityToken" Usage="tokenProvider.EndGetToken result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IdentityModel.Tokens.SecurityToken</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="ede7e-230"><see cref="T:System.IAsyncResult" />トークンを取得する非同期操作を参照するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="ede7e-230">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous operation to get a token.</span></span></param>
        <summary><span data-ttu-id="ede7e-231">非同期の操作によるセキュリティ トークンの取得を完了します。</span><span class="sxs-lookup"><span data-stu-id="ede7e-231">Completes an asynchronous operation to get a security token.</span></span></summary>
        <returns><span data-ttu-id="ede7e-232"><see cref="T:System.IdentityModel.Tokens.SecurityToken" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="ede7e-232">The <see cref="T:System.IdentityModel.Tokens.SecurityToken" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndGetWebToken">
      <MemberSignature Language="C#" Value="public string EndGetWebToken (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string EndGetWebToken(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.EndGetWebToken(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Function EndGetWebToken (result As IAsyncResult) As String" />
      <MemberSignature Language="F#" Value="member this.EndGetWebToken : IAsyncResult -&gt; string" Usage="tokenProvider.EndGetWebToken result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="ede7e-233"><see cref="T:System.IAsyncResult" /> Web トークンを取得する非同期操作を参照するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="ede7e-233">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous operation to get a web token.</span></span></param>
        <summary><span data-ttu-id="ede7e-234">Web トークンを取得する非同期操作を完了します。</span><span class="sxs-lookup"><span data-stu-id="ede7e-234">Completes an asynchronous operation to get a web token.</span></span></summary>
        <returns><span data-ttu-id="ede7e-235"><see cref="T:System.String" /> Web トークンを表すです。</span><span class="sxs-lookup"><span data-stu-id="ede7e-235">The <see cref="T:System.String" /> that represents the web token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.IdentityModel.Tokens.SecurityToken&gt; GetTokenAsync (string appliesTo, string action, bool bypassCache, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.IdentityModel.Tokens.SecurityToken&gt; GetTokenAsync(string appliesTo, string action, bool bypassCache, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.GetTokenAsync(System.String,System.String,System.Boolean,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetTokenAsync (appliesTo As String, action As String, bypassCache As Boolean, timeout As TimeSpan) As Task(Of SecurityToken)" />
      <MemberSignature Language="F#" Value="member this.GetTokenAsync : string * string * bool * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.IdentityModel.Tokens.SecurityToken&gt;" Usage="tokenProvider.GetTokenAsync (appliesTo, action, bypassCache, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
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
        <param name="appliesTo"><span data-ttu-id="ede7e-236">アクセス トークンが適用される URI。</span><span class="sxs-lookup"><span data-stu-id="ede7e-236">The URI which the access token applies to.</span></span></param>
        <param name="action"><span data-ttu-id="ede7e-237">要求された操作。</span><span class="sxs-lookup"><span data-stu-id="ede7e-237">The request action.</span></span></param>
        <param name="bypassCache"><span data-ttu-id="ede7e-238">キャッシュ内の既存のトークン情報を無視する場合は trueキャッシュのトークンの情報を使用する場合は false。</span><span class="sxs-lookup"><span data-stu-id="ede7e-238">true to ignore existing token information in the cache; false to use the token information in the cache.</span></span></param>
        <param name="timeout"><span data-ttu-id="ede7e-239">セキュリティ トークンを取得するメッセージのタイムアウト値を指定する時間間隔。</span><span class="sxs-lookup"><span data-stu-id="ede7e-239">The time span that specifies the timeout value for the message that gets the security token.</span></span></param>
        <summary><span data-ttu-id="ede7e-240">非同期的に、プロバイダーのトークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="ede7e-240">Asynchronously retrieves the token for the provider.</span></span></summary>
        <returns><span data-ttu-id="ede7e-241">非同期操作の結果。</span><span class="sxs-lookup"><span data-stu-id="ede7e-241">The result of the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetWebTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetWebTokenAsync (string appliesTo, string action, bool bypassCache, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; GetWebTokenAsync(string appliesTo, string action, bool bypassCache, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.GetWebTokenAsync(System.String,System.String,System.Boolean,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetWebTokenAsync (appliesTo As String, action As String, bypassCache As Boolean, timeout As TimeSpan) As Task(Of String)" />
      <MemberSignature Language="F#" Value="member this.GetWebTokenAsync : string * string * bool * TimeSpan -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="tokenProvider.GetWebTokenAsync (appliesTo, action, bypassCache, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
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
        <param name="appliesTo"><span data-ttu-id="ede7e-242">アクセス トークンが適用される URI。</span><span class="sxs-lookup"><span data-stu-id="ede7e-242">The URI which the access token applies to.</span></span></param>
        <param name="action"><span data-ttu-id="ede7e-243">要求された操作。</span><span class="sxs-lookup"><span data-stu-id="ede7e-243">The request action.</span></span></param>
        <param name="bypassCache"><span data-ttu-id="ede7e-244">キャッシュ内の既存のトークン情報を無視する場合は trueキャッシュのトークンの情報を使用する場合は false。</span><span class="sxs-lookup"><span data-stu-id="ede7e-244">true to ignore existing token information in the cache; false to use the token information in the cache.</span></span></param>
        <param name="timeout"><span data-ttu-id="ede7e-245">セキュリティ トークンを取得するメッセージのタイムアウト値を指定する時間間隔。</span><span class="sxs-lookup"><span data-stu-id="ede7e-245">The time span that specifies the timeout value for the message that gets the security token.</span></span></param>
        <summary><span data-ttu-id="ede7e-246">非同期的に、プロバイダーの web トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="ede7e-246">Asynchronously retrieves the web token for the provider.</span></span></summary>
        <returns><span data-ttu-id="ede7e-247">非同期操作の結果。</span><span class="sxs-lookup"><span data-stu-id="ede7e-247">The result of the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsWebTokenSupported">
      <MemberSignature Language="C#" Value="public bool IsWebTokenSupported { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsWebTokenSupported" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.TokenProvider.IsWebTokenSupported" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsWebTokenSupported As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsWebTokenSupported : bool" Usage="Microsoft.Azure.NotificationHubs.TokenProvider.IsWebTokenSupported" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="ede7e-248">取得または web トークンをこのプロバイダーでサポートされているかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="ede7e-248">Gets or sets a value that indicates whether web token is supported by this provider.</span></span></summary>
        <value><span data-ttu-id="ede7e-249">web トークンが; このプロバイダーでサポートされている場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="ede7e-249">true if web token is supported by this provider; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NormalizeAppliesTo">
      <MemberSignature Language="C#" Value="protected virtual string NormalizeAppliesTo (string appliesTo);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance string NormalizeAppliesTo(string appliesTo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.NormalizeAppliesTo(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function NormalizeAppliesTo (appliesTo As String) As String" />
      <MemberSignature Language="F#" Value="abstract member NormalizeAppliesTo : string -&gt; string&#xA;override this.NormalizeAppliesTo : string -&gt; string" Usage="tokenProvider.NormalizeAppliesTo appliesTo" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appliesTo" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="appliesTo"><span data-ttu-id="ede7e-250">アクセス トークンが適用される URI。</span><span class="sxs-lookup"><span data-stu-id="ede7e-250">The URI which the access token applies to.</span></span></param>
        <summary><span data-ttu-id="ede7e-251">値は、トークン プロバイダーと同じオブジェクトを返します。</span><span class="sxs-lookup"><span data-stu-id="ede7e-251">Returns an object whose value is the same as the token provider.</span></span></summary>
        <returns><span data-ttu-id="ede7e-252">返されるオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="ede7e-252">The returned object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginGetToken">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginGetToken (string appliesTo, string action, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginGetToken(string appliesTo, string action, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.OnBeginGetToken(System.String,System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnBeginGetToken (appliesTo As String, action As String, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member OnBeginGetToken : string * string * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="tokenProvider.OnBeginGetToken (appliesTo, action, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
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
        <param name="appliesTo"><span data-ttu-id="ede7e-253">アクセス トークンが適用される URI。</span><span class="sxs-lookup"><span data-stu-id="ede7e-253">The URI which the access token applies to.</span></span></param>
        <param name="action"><span data-ttu-id="ede7e-254">要求された操作。</span><span class="sxs-lookup"><span data-stu-id="ede7e-254">The request action.</span></span></param>
        <param name="timeout"><span data-ttu-id="ede7e-255">セキュリティ トークンを取得するメッセージのタイムアウト値を指定する時間間隔。</span><span class="sxs-lookup"><span data-stu-id="ede7e-255">The time span that specifies the timeout value for the message that gets the security token.</span></span></param>
        <param name="callback"><span data-ttu-id="ede7e-256">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</span><span class="sxs-lookup"><span data-stu-id="ede7e-256">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="ede7e-257">非同期操作に関する状態情報を含むユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="ede7e-257">A user-defined object that contains state information about the asynchronous operation.</span></span> </param>
        <summary><span data-ttu-id="ede7e-258">BeginGetToken メソッドの呼び出し時に実行します。</span><span class="sxs-lookup"><span data-stu-id="ede7e-258">Executes upon calling the BeginGetToken method.</span></span></summary>
        <returns><span data-ttu-id="ede7e-259"><see cref="T:System.IAsyncResult" />トークンを取得する非同期操作を参照するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="ede7e-259">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous operation to get a token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginGetWebToken">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginGetWebToken (string appliesTo, string action, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginGetWebToken(string appliesTo, string action, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.OnBeginGetWebToken(System.String,System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnBeginGetWebToken (appliesTo As String, action As String, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member OnBeginGetWebToken : string * string * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="tokenProvider.OnBeginGetWebToken (appliesTo, action, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
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
        <param name="appliesTo"><span data-ttu-id="ede7e-260">アクセス トークンが適用される URI。</span><span class="sxs-lookup"><span data-stu-id="ede7e-260">The URI which the access token applies to.</span></span></param>
        <param name="action"><span data-ttu-id="ede7e-261">要求された操作。</span><span class="sxs-lookup"><span data-stu-id="ede7e-261">The request action.</span></span></param>
        <param name="timeout"><span data-ttu-id="ede7e-262">セキュリティ トークンを取得するメッセージのタイムアウト値を指定する時間間隔。</span><span class="sxs-lookup"><span data-stu-id="ede7e-262">The time span that specifies the timeout value for the message that gets the security token.</span></span></param>
        <param name="callback"><span data-ttu-id="ede7e-263">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</span><span class="sxs-lookup"><span data-stu-id="ede7e-263">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="ede7e-264">非同期操作に関する状態情報を含むユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="ede7e-264">A user-defined object that contains state information about the asynchronous operation.</span></span> </param>
        <summary><span data-ttu-id="ede7e-265">BeginGetWebToken メソッドの呼び出し時に実行します。</span><span class="sxs-lookup"><span data-stu-id="ede7e-265">Executes upon calling the BeginGetWebToken method.</span></span></summary>
        <returns><span data-ttu-id="ede7e-266"><see cref="T:System.IAsyncResult" /> Web トークンを取得する非同期操作を参照するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="ede7e-266">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous operation to get a web token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndGetToken">
      <MemberSignature Language="C#" Value="protected abstract System.IdentityModel.Tokens.SecurityToken OnEndGetToken (IAsyncResult result, out DateTime cacheUntil);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IdentityModel.Tokens.SecurityToken OnEndGetToken(class System.IAsyncResult result, [out] valuetype System.DateTime&amp; cacheUntil) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.OnEndGetToken(System.IAsyncResult,System.DateTime@)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndGetToken (result As IAsyncResult, ByRef cacheUntil As DateTime) As SecurityToken" />
      <MemberSignature Language="F#" Value="abstract member OnEndGetToken : IAsyncResult *  -&gt; System.IdentityModel.Tokens.SecurityToken" Usage="tokenProvider.OnEndGetToken (result, cacheUntil)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IdentityModel.Tokens.SecurityToken</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
        <Parameter Name="cacheUntil" Type="System.DateTime&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="ede7e-267"><see cref="T:System.IAsyncResult" />トークンを取得する非同期操作を参照するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="ede7e-267">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous operation to get a token.</span></span></param>
        <param name="cacheUntil"><span data-ttu-id="ede7e-268">このメソッドが戻るとき、有効期限の日付と時刻、キャッシュ内のトークンの情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="ede7e-268">When this method returns, contains the expiration date and time of the token information in the cache.</span></span></param>
        <summary><span data-ttu-id="ede7e-269">EndGetToken メソッドの呼び出し時に実行します。</span><span class="sxs-lookup"><span data-stu-id="ede7e-269">Executes upon calling the EndGetToken method.</span></span></summary>
        <returns><span data-ttu-id="ede7e-270"><see cref="T:System.IdentityModel.Tokens.SecurityToken" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="ede7e-270">The <see cref="T:System.IdentityModel.Tokens.SecurityToken" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndGetWebToken">
      <MemberSignature Language="C#" Value="protected abstract string OnEndGetWebToken (IAsyncResult result, out DateTime cacheUntil);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance string OnEndGetWebToken(class System.IAsyncResult result, [out] valuetype System.DateTime&amp; cacheUntil) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TokenProvider.OnEndGetWebToken(System.IAsyncResult,System.DateTime@)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndGetWebToken (result As IAsyncResult, ByRef cacheUntil As DateTime) As String" />
      <MemberSignature Language="F#" Value="abstract member OnEndGetWebToken : IAsyncResult *  -&gt; string" Usage="tokenProvider.OnEndGetWebToken (result, cacheUntil)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
        <Parameter Name="cacheUntil" Type="System.DateTime&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="ede7e-271"><see cref="T:System.IAsyncResult" /> Web トークンを取得する非同期操作を参照するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="ede7e-271">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous operation to get a web token.</span></span></param>
        <param name="cacheUntil"><span data-ttu-id="ede7e-272">このメソッドが戻るとき、有効期限の日付と時刻、キャッシュ内のトークンの情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="ede7e-272">When this method returns, contains the expiration date and time of the token information in the cache.</span></span></param>
        <summary><span data-ttu-id="ede7e-273">EndGetWebToken メソッドの呼び出し時に実行します。</span><span class="sxs-lookup"><span data-stu-id="ede7e-273">Executes upon calling the EndGetWebToken method.</span></span></summary>
        <returns><span data-ttu-id="ede7e-274"><see cref="T:System.String" /> Web トークンを表すです。</span><span class="sxs-lookup"><span data-stu-id="ede7e-274">The <see cref="T:System.String" /> that represents the web token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StripQueryParameters">
      <MemberSignature Language="C#" Value="protected virtual bool StripQueryParameters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool StripQueryParameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.TokenProvider.StripQueryParameters" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable ReadOnly Property StripQueryParameters As Boolean" />
      <MemberSignature Language="F#" Value="member this.StripQueryParameters : bool" Usage="Microsoft.Azure.NotificationHubs.TokenProvider.StripQueryParameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="ede7e-275">トークン プロバイダーがクエリ パラメーターを削除するかどうかを取得します。</span><span class="sxs-lookup"><span data-stu-id="ede7e-275">Gets whether the token provider strips query parameters.</span></span></summary>
        <value><span data-ttu-id="ede7e-276">トークン プロバイダーはクエリ パラメーターを削除する場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="ede7e-276">true if the token provider strips query parameters; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenScope">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.TokenScope TokenScope { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.NotificationHubs.TokenScope TokenScope" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.TokenProvider.TokenScope" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TokenScope As TokenScope" />
      <MemberSignature Language="F#" Value="member this.TokenScope : Microsoft.Azure.NotificationHubs.TokenScope" Usage="Microsoft.Azure.NotificationHubs.TokenProvider.TokenScope" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.TokenScope</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="ede7e-277">取得またはプロバイダーに関連付けられているトークンのスコープを設定します。</span><span class="sxs-lookup"><span data-stu-id="ede7e-277">Gets or sets the token scope associated with the provider.</span></span></summary>
        <value><span data-ttu-id="ede7e-278">プロバイダーに関連付けられているトークンのスコープです。</span><span class="sxs-lookup"><span data-stu-id="ede7e-278">The token scope associated with the provider.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>