<Type Name="SharedAccessSignatureTokenProvider" FullName="Microsoft.Azure.NotificationHubs.SharedAccessSignatureTokenProvider">
  <TypeSignature Language="C#" Value="public class SharedAccessSignatureTokenProvider : Microsoft.Azure.NotificationHubs.TokenProvider" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SharedAccessSignatureTokenProvider extends Microsoft.Azure.NotificationHubs.TokenProvider" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.SharedAccessSignatureTokenProvider" />
  <TypeSignature Language="VB.NET" Value="Public Class SharedAccessSignatureTokenProvider&#xA;Inherits TokenProvider" />
  <TypeSignature Language="F#" Value="type SharedAccessSignatureTokenProvider = class&#xA;    inherit TokenProvider" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.NotificationHubs.TokenProvider</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="00089-101">トークン プロバイダーに関連付けられている共有アクセス署名を表します。</span><span class="sxs-lookup"><span data-stu-id="00089-101">Represents the shared access signature associated with the token provider.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BuildKey">
      <MemberSignature Language="C#" Value="protected override Microsoft.Azure.NotificationHubs.TokenProvider.Key BuildKey (string appliesTo, string action);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class Microsoft.Azure.NotificationHubs.TokenProvider/Key BuildKey(string appliesTo, string action) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.SharedAccessSignatureTokenProvider.BuildKey(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function BuildKey (appliesTo As String, action As String) As TokenProvider.Key" />
      <MemberSignature Language="F#" Value="override this.BuildKey : string * string -&gt; Microsoft.Azure.NotificationHubs.TokenProvider.Key" Usage="sharedAccessSignatureTokenProvider.BuildKey (appliesTo, action)" />
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
        <param name="appliesTo"><span data-ttu-id="00089-102">アクセス トークンが適用される URI。</span><span class="sxs-lookup"><span data-stu-id="00089-102">The URI which the access token applies to.</span></span></param>
        <param name="action"><span data-ttu-id="00089-103">要求された操作。</span><span class="sxs-lookup"><span data-stu-id="00089-103">The request action.</span></span></param>
        <summary><span data-ttu-id="00089-104">トークン プロバイダーをキーを生成します。</span><span class="sxs-lookup"><span data-stu-id="00089-104">Generates a key for the token provider.</span></span></summary>
        <returns><span data-ttu-id="00089-105">トークン プロバイダー用に生成されたキー。</span><span class="sxs-lookup"><span data-stu-id="00089-105">A generated key for the token provider.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EpochTime">
      <MemberSignature Language="C#" Value="public static readonly DateTime EpochTime;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly valuetype System.DateTime EpochTime" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.NotificationHubs.SharedAccessSignatureTokenProvider.EpochTime" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly EpochTime As DateTime " />
      <MemberSignature Language="F#" Value=" staticval mutable EpochTime : DateTime" Usage="Microsoft.Azure.NotificationHubs.SharedAccessSignatureTokenProvider.EpochTime" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="00089-106">エポック時間。</span><span class="sxs-lookup"><span data-stu-id="00089-106">The epoch time.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSharedAccessSignature">
      <MemberSignature Language="C#" Value="public static string GetSharedAccessSignature (string keyName, string sharedAccessKey, string resource, TimeSpan tokenTimeToLive);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetSharedAccessSignature(string keyName, string sharedAccessKey, string resource, valuetype System.TimeSpan tokenTimeToLive) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.SharedAccessSignatureTokenProvider.GetSharedAccessSignature(System.String,System.String,System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetSharedAccessSignature (keyName As String, sharedAccessKey As String, resource As String, tokenTimeToLive As TimeSpan) As String" />
      <MemberSignature Language="F#" Value="static member GetSharedAccessSignature : string * string * string * TimeSpan -&gt; string" Usage="Microsoft.Azure.NotificationHubs.SharedAccessSignatureTokenProvider.GetSharedAccessSignature (keyName, sharedAccessKey, resource, tokenTimeToLive)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="sharedAccessKey" Type="System.String" />
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="tokenTimeToLive" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="keyName"><span data-ttu-id="00089-107">キー名</span><span class="sxs-lookup"><span data-stu-id="00089-107">The key name</span></span></param>
        <param name="sharedAccessKey"><span data-ttu-id="00089-108">共有アクセス キー</span><span class="sxs-lookup"><span data-stu-id="00089-108">The shared access key</span></span></param>
        <param name="resource"><span data-ttu-id="00089-109">Unscaped リソース</span><span class="sxs-lookup"><span data-stu-id="00089-109">The unscaped resource</span></span></param>
        <param name="tokenTimeToLive"><span data-ttu-id="00089-110">Tolen time to live</span><span class="sxs-lookup"><span data-stu-id="00089-110">The tolen time to live</span></span></param>
        <summary>
             <span data-ttu-id="00089-111">共有アクセス署名の生成</span><span class="sxs-lookup"><span data-stu-id="00089-111">Generated a shared access signature</span></span>
            </summary>
        <returns><span data-ttu-id="00089-112">共有アクセス署名を返す</span><span class="sxs-lookup"><span data-stu-id="00089-112">Return a shared access signature</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginGetToken">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginGetToken (string appliesTo, string action, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginGetToken(string appliesTo, string action, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.SharedAccessSignatureTokenProvider.OnBeginGetToken(System.String,System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginGetToken (appliesTo As String, action As String, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginGetToken : string * string * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="sharedAccessSignatureTokenProvider.OnBeginGetToken (appliesTo, action, timeout, callback, state)" />
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
        <param name="appliesTo"><span data-ttu-id="00089-113">アクセス トークンが適用される URI。</span><span class="sxs-lookup"><span data-stu-id="00089-113">The URI which the access token applies to.</span></span></param>
        <param name="action"><span data-ttu-id="00089-114">要求された操作。</span><span class="sxs-lookup"><span data-stu-id="00089-114">The request action.</span></span></param>
        <param name="timeout"><span data-ttu-id="00089-115">セキュリティ トークンを取得するメッセージのタイムアウト値を指定する時間間隔。</span><span class="sxs-lookup"><span data-stu-id="00089-115">The time span that specifies the timeout value for the message that gets the security token.</span></span></param>
        <param name="callback"><span data-ttu-id="00089-116">操作が完了したときに呼び出されるメソッドを参照する AsyncCallback デリゲート。</span><span class="sxs-lookup"><span data-stu-id="00089-116">An AsyncCallback delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="00089-117">非同期操作に関する状態情報を含むユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="00089-117">A user-defined object that contains state information about the asynchronous operation.</span></span></param>
        <summary><span data-ttu-id="00089-118">BeginGetToken メソッドの呼び出し時に実行します。</span><span class="sxs-lookup"><span data-stu-id="00089-118">Executes upon calling the BeginGetToken method.</span></span></summary>
        <returns><span data-ttu-id="00089-119">操作の結果。</span><span class="sxs-lookup"><span data-stu-id="00089-119">The result of the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginGetWebToken">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginGetWebToken (string appliesTo, string action, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginGetWebToken(string appliesTo, string action, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.SharedAccessSignatureTokenProvider.OnBeginGetWebToken(System.String,System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginGetWebToken (appliesTo As String, action As String, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginGetWebToken : string * string * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="sharedAccessSignatureTokenProvider.OnBeginGetWebToken (appliesTo, action, timeout, callback, state)" />
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
        <param name="appliesTo"><span data-ttu-id="00089-120">アクセス トークンが適用される URI。</span><span class="sxs-lookup"><span data-stu-id="00089-120">The URI which the access token applies to.</span></span></param>
        <param name="action"><span data-ttu-id="00089-121">要求された操作。</span><span class="sxs-lookup"><span data-stu-id="00089-121">The request action.</span></span></param>
        <param name="timeout"><span data-ttu-id="00089-122">セキュリティ トークンを取得するメッセージのタイムアウト値を指定する時間間隔。</span><span class="sxs-lookup"><span data-stu-id="00089-122">The time span that specifies the timeout value for the message that gets the security token.</span></span></param>
        <param name="callback"><span data-ttu-id="00089-123">操作が完了したときに呼び出されるメソッドを参照する AsyncCallback デリゲート。</span><span class="sxs-lookup"><span data-stu-id="00089-123">An AsyncCallback delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="00089-124">非同期操作に関する状態情報を含むユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="00089-124">A user-defined object that contains state information about the asynchronous operation.</span></span></param>
        <summary><span data-ttu-id="00089-125">BeginGetWebToken メソッドの呼び出し時に実行します。</span><span class="sxs-lookup"><span data-stu-id="00089-125">Executes upon calling the BeginGetWebToken method.</span></span></summary>
        <returns><span data-ttu-id="00089-126">操作の結果。</span><span class="sxs-lookup"><span data-stu-id="00089-126">The result of the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndGetToken">
      <MemberSignature Language="C#" Value="protected override System.IdentityModel.Tokens.SecurityToken OnEndGetToken (IAsyncResult result, out DateTime cacheUntil);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IdentityModel.Tokens.SecurityToken OnEndGetToken(class System.IAsyncResult result, [out] valuetype System.DateTime&amp; cacheUntil) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.SharedAccessSignatureTokenProvider.OnEndGetToken(System.IAsyncResult,System.DateTime@)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnEndGetToken (result As IAsyncResult, ByRef cacheUntil As DateTime) As SecurityToken" />
      <MemberSignature Language="F#" Value="override this.OnEndGetToken : IAsyncResult *  -&gt; System.IdentityModel.Tokens.SecurityToken" Usage="sharedAccessSignatureTokenProvider.OnEndGetToken (result, cacheUntil)" />
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
        <param name="result"><span data-ttu-id="00089-127">トークンを取得する非同期操作を参照する IAsyncResult オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="00089-127">An IAsyncResult object that references the asynchronous operation to get a token.</span></span></param>
        <param name="cacheUntil"><span data-ttu-id="00089-128">このメソッドが戻るとき、有効期限の日付と時刻、キャッシュ内のトークンの情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="00089-128">When this method returns, contains the expiration date and time of the token information in the cache.</span></span></param>
        <summary><span data-ttu-id="00089-129">EndGetToken メソッドの呼び出し時に実行します。</span><span class="sxs-lookup"><span data-stu-id="00089-129">Executes upon calling the EndGetToken method.</span></span></summary>
        <returns><span data-ttu-id="00089-130"><see cref="T:System.IdentityModel.Tokens.SecurityToken" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="00089-130">The <see cref="T:System.IdentityModel.Tokens.SecurityToken" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndGetWebToken">
      <MemberSignature Language="C#" Value="protected override string OnEndGetWebToken (IAsyncResult result, out DateTime cacheUntil);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance string OnEndGetWebToken(class System.IAsyncResult result, [out] valuetype System.DateTime&amp; cacheUntil) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.SharedAccessSignatureTokenProvider.OnEndGetWebToken(System.IAsyncResult,System.DateTime@)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnEndGetWebToken (result As IAsyncResult, ByRef cacheUntil As DateTime) As String" />
      <MemberSignature Language="F#" Value="override this.OnEndGetWebToken : IAsyncResult *  -&gt; string" Usage="sharedAccessSignatureTokenProvider.OnEndGetWebToken (result, cacheUntil)" />
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
        <param name="result"><span data-ttu-id="00089-131">Web のトークンを取得する非同期操作を参照する IAsyncResult オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="00089-131">An IAsyncResult object that references the asynchronous operation to get a web token.</span></span></param>
        <param name="cacheUntil"><span data-ttu-id="00089-132">このメソッドが戻るとき、有効期限の日付と時刻、キャッシュ内のトークンの情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="00089-132">When this method returns, contains the expiration date and time of the token information in the cache.</span></span></param>
        <summary><span data-ttu-id="00089-133">EndGetWebToken メソッドの呼び出し時に実行します。</span><span class="sxs-lookup"><span data-stu-id="00089-133">Executes upon calling the EndGetWebToken method.</span></span></summary>
        <returns><span data-ttu-id="00089-134">Web トークンを表す文字列。</span><span class="sxs-lookup"><span data-stu-id="00089-134">The String that represents the web token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StripQueryParameters">
      <MemberSignature Language="C#" Value="protected override bool StripQueryParameters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool StripQueryParameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.SharedAccessSignatureTokenProvider.StripQueryParameters" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property StripQueryParameters As Boolean" />
      <MemberSignature Language="F#" Value="member this.StripQueryParameters : bool" Usage="Microsoft.Azure.NotificationHubs.SharedAccessSignatureTokenProvider.StripQueryParameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="00089-135">トークン プロバイダーがクエリ パラメーターを削除するかどうかを取得します。</span><span class="sxs-lookup"><span data-stu-id="00089-135">Gets whether the token provider strips query parameters.</span></span></summary>
        <value><span data-ttu-id="00089-136">トークン プロバイダーはクエリ パラメーターを削除する場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="00089-136">true if the token provider strips query parameters; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>