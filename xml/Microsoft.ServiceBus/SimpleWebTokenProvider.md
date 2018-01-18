<Type Name="SimpleWebTokenProvider" FullName="Microsoft.ServiceBus.SimpleWebTokenProvider">
  <TypeSignature Language="C#" Value="public class SimpleWebTokenProvider : Microsoft.ServiceBus.TokenProvider" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SimpleWebTokenProvider extends Microsoft.ServiceBus.TokenProvider" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.SimpleWebTokenProvider" />
  <TypeSignature Language="VB.NET" Value="Public Class SimpleWebTokenProvider&#xA;Inherits TokenProvider" />
  <TypeSignature Language="F#" Value="type SimpleWebTokenProvider = class&#xA;    inherit TokenProvider" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.TokenProvider</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="46aed-101">一連の非同期単純な Web トークン (SWT) の取得操作を実行するメソッドを提供します。</span><span class="sxs-lookup"><span data-stu-id="46aed-101">Provides a set of methods that execute asynchronous simple Web token (SWT) retrieval operations.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BuildKey">
      <MemberSignature Language="C#" Value="protected override Microsoft.ServiceBus.TokenProvider.Key BuildKey (string appliesTo, string action);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class Microsoft.ServiceBus.TokenProvider/Key BuildKey(string appliesTo, string action) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SimpleWebTokenProvider.BuildKey(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function BuildKey (appliesTo As String, action As String) As TokenProvider.Key" />
      <MemberSignature Language="F#" Value="override this.BuildKey : string * string -&gt; Microsoft.ServiceBus.TokenProvider.Key" Usage="simpleWebTokenProvider.BuildKey (appliesTo, action)" />
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
        <param name="appliesTo"><span data-ttu-id="46aed-102">アクセス トークンが適用される URI。</span><span class="sxs-lookup"><span data-stu-id="46aed-102">The URI which the access token applies to.</span></span></param>
        <param name="action"><span data-ttu-id="46aed-103">要求された操作。</span><span class="sxs-lookup"><span data-stu-id="46aed-103">The request action.</span></span></param>
        <summary><span data-ttu-id="46aed-104">単純な web トークン プロバイダーをキーを生成します。</span><span class="sxs-lookup"><span data-stu-id="46aed-104">Generates a key for the simple web token provider.</span></span></summary>
        <returns><span data-ttu-id="46aed-105">単純な web トークン プロバイダーの生成されたキー。</span><span class="sxs-lookup"><span data-stu-id="46aed-105">A generated key for the simple web token provider.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginGetToken">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginGetToken (string appliesTo, string action, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginGetToken(string appliesTo, string action, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SimpleWebTokenProvider.OnBeginGetToken(System.String,System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginGetToken (appliesTo As String, action As String, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginGetToken : string * string * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="simpleWebTokenProvider.OnBeginGetToken (appliesTo, action, timeout, callback, state)" />
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
        <param name="appliesTo"><span data-ttu-id="46aed-106">アクセス トークンが適用される URI。</span><span class="sxs-lookup"><span data-stu-id="46aed-106">The URI which the access token applies to.</span></span></param>
        <param name="action"><span data-ttu-id="46aed-107">要求された操作。</span><span class="sxs-lookup"><span data-stu-id="46aed-107">The request action.</span></span></param>
        <param name="timeout"><span data-ttu-id="46aed-108">セキュリティ トークンを取得するメッセージのタイムアウト値を指定する時間間隔。</span><span class="sxs-lookup"><span data-stu-id="46aed-108">The time span that specifies the timeout value for the message that gets the security token.</span></span></param>
        <param name="callback"><span data-ttu-id="46aed-109">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</span><span class="sxs-lookup"><span data-stu-id="46aed-109">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="46aed-110">非同期操作に関する状態情報を含むユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="46aed-110">A user-defined object that contains state information about the asynchronous operation.</span></span></param>
        <summary><span data-ttu-id="46aed-111">Begin get トークン アクションを実行します。</span><span class="sxs-lookup"><span data-stu-id="46aed-111">Executes the begin get token action.</span></span></summary>
        <returns><span data-ttu-id="46aed-112"><see cref="T:System.IAsyncResult" />トークンを取得する非同期操作を参照するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="46aed-112">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous operation to get a token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginGetWebToken">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginGetWebToken (string appliesTo, string action, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginGetWebToken(string appliesTo, string action, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SimpleWebTokenProvider.OnBeginGetWebToken(System.String,System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginGetWebToken (appliesTo As String, action As String, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginGetWebToken : string * string * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="simpleWebTokenProvider.OnBeginGetWebToken (appliesTo, action, timeout, callback, state)" />
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
        <param name="appliesTo"><span data-ttu-id="46aed-113">アクセス トークンが適用される URI。</span><span class="sxs-lookup"><span data-stu-id="46aed-113">The URI which the access token applies to.</span></span></param>
        <param name="action"><span data-ttu-id="46aed-114">要求された操作。</span><span class="sxs-lookup"><span data-stu-id="46aed-114">The request action.</span></span></param>
        <param name="timeout"><span data-ttu-id="46aed-115">セキュリティ トークンを取得するメッセージのタイムアウト値を指定する時間間隔。</span><span class="sxs-lookup"><span data-stu-id="46aed-115">The time span that specifies the timeout value for the message that gets the security token.</span></span></param>
        <param name="callback"><span data-ttu-id="46aed-116">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</span><span class="sxs-lookup"><span data-stu-id="46aed-116">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="46aed-117">非同期操作に関する状態情報を含むユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="46aed-117">A user-defined object that contains state information about the asynchronous operation.</span></span></param>
        <summary><span data-ttu-id="46aed-118">Begin get web トークンのアクションを実行します。</span><span class="sxs-lookup"><span data-stu-id="46aed-118">Executes the begin get web token action.</span></span></summary>
        <returns><span data-ttu-id="46aed-119"><see cref="T:System.IAsyncResult" /> Web トークンを取得する非同期操作を参照するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="46aed-119">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous operation to get a web token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndGetToken">
      <MemberSignature Language="C#" Value="protected override System.IdentityModel.Tokens.SecurityToken OnEndGetToken (IAsyncResult result, out DateTime cacheUntil);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IdentityModel.Tokens.SecurityToken OnEndGetToken(class System.IAsyncResult result, [out] valuetype System.DateTime&amp; cacheUntil) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SimpleWebTokenProvider.OnEndGetToken(System.IAsyncResult,System.DateTime@)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnEndGetToken (result As IAsyncResult, ByRef cacheUntil As DateTime) As SecurityToken" />
      <MemberSignature Language="F#" Value="override this.OnEndGetToken : IAsyncResult *  -&gt; System.IdentityModel.Tokens.SecurityToken" Usage="simpleWebTokenProvider.OnEndGetToken (result, cacheUntil)" />
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
        <param name="result"><span data-ttu-id="46aed-120"><see cref="T:System.IAsyncResult" />トークンを取得する非同期操作を参照するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="46aed-120">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous operation to get a token.</span></span></param>
        <param name="cacheUntil"><span data-ttu-id="46aed-121">このメソッドが戻るとき、有効期限の日付と時刻、キャッシュ内のトークンの情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="46aed-121">When this method returns, contains the expiration date and time of the token information in the cache.</span></span></param>
        <summary><span data-ttu-id="46aed-122">最後の get トークン アクションを実行します。</span><span class="sxs-lookup"><span data-stu-id="46aed-122">Executes the end get token action.</span></span></summary>
        <returns><span data-ttu-id="46aed-123">セキュリティ トークン。</span><span class="sxs-lookup"><span data-stu-id="46aed-123">The security token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndGetWebToken">
      <MemberSignature Language="C#" Value="protected override string OnEndGetWebToken (IAsyncResult result, out DateTime cacheUntil);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance string OnEndGetWebToken(class System.IAsyncResult result, [out] valuetype System.DateTime&amp; cacheUntil) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SimpleWebTokenProvider.OnEndGetWebToken(System.IAsyncResult,System.DateTime@)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnEndGetWebToken (result As IAsyncResult, ByRef cacheUntil As DateTime) As String" />
      <MemberSignature Language="F#" Value="override this.OnEndGetWebToken : IAsyncResult *  -&gt; string" Usage="simpleWebTokenProvider.OnEndGetWebToken (result, cacheUntil)" />
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
        <param name="result"><span data-ttu-id="46aed-124"><see cref="T:System.IAsyncResult" /> Web トークンを取得する非同期操作を参照するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="46aed-124">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous operation to get a web token.</span></span></param>
        <param name="cacheUntil"><span data-ttu-id="46aed-125">このメソッドが戻るとき、有効期限の日付と時刻、キャッシュ内のトークンの情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="46aed-125">When this method returns, contains the expiration date and time of the token information in the cache.</span></span></param>
        <summary><span data-ttu-id="46aed-126">End get web トークンのアクションを実行します。</span><span class="sxs-lookup"><span data-stu-id="46aed-126">Executes the end get web token action.</span></span></summary>
        <returns><span data-ttu-id="46aed-127">Web トークンです。</span><span class="sxs-lookup"><span data-stu-id="46aed-127">The web token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>