<Type Name="OAuthTokenProvider" FullName="Microsoft.Azure.NotificationHubs.OAuthTokenProvider">
  <TypeSignature Language="C#" Value="public class OAuthTokenProvider : Microsoft.Azure.NotificationHubs.TokenProvider" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OAuthTokenProvider extends Microsoft.Azure.NotificationHubs.TokenProvider" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.OAuthTokenProvider" />
  <TypeSignature Language="VB.NET" Value="Public Class OAuthTokenProvider&#xA;Inherits TokenProvider" />
  <TypeSignature Language="F#" Value="type OAuthTokenProvider = class&#xA;    inherit TokenProvider" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.NotificationHubs.TokenProvider</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="8115e-101">Service bus の認証トークンを提供します。</span><span class="sxs-lookup"><span data-stu-id="8115e-101">Provides authentication token for the service bus.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BuildKey">
      <MemberSignature Language="C#" Value="protected override Microsoft.Azure.NotificationHubs.TokenProvider.Key BuildKey (string appliesTo, string action);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class Microsoft.Azure.NotificationHubs.TokenProvider/Key BuildKey(string appliesTo, string action) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.OAuthTokenProvider.BuildKey(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function BuildKey (appliesTo As String, action As String) As TokenProvider.Key" />
      <MemberSignature Language="F#" Value="override this.BuildKey : string * string -&gt; Microsoft.Azure.NotificationHubs.TokenProvider.Key" Usage="oAuthTokenProvider.BuildKey (appliesTo, action)" />
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
        <param name="appliesTo"><span data-ttu-id="8115e-102">キーの適用されるプロバイダー。</span><span class="sxs-lookup"><span data-stu-id="8115e-102">The provider in which the key will be applied.</span></span></param>
        <param name="action"><span data-ttu-id="8115e-103">アクション。</span><span class="sxs-lookup"><span data-stu-id="8115e-103">The action.</span></span></param>
        <summary><span data-ttu-id="8115e-104">プロバイダーのキーを作成します。</span><span class="sxs-lookup"><span data-stu-id="8115e-104">Builds a key for the provider.</span></span></summary>
        <returns><span data-ttu-id="8115e-105">キーがあります。</span><span class="sxs-lookup"><span data-stu-id="8115e-105">A Key.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NormalizeAppliesTo">
      <MemberSignature Language="C#" Value="protected override string NormalizeAppliesTo (string appliesTo);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance string NormalizeAppliesTo(string appliesTo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.OAuthTokenProvider.NormalizeAppliesTo(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function NormalizeAppliesTo (appliesTo As String) As String" />
      <MemberSignature Language="F#" Value="override this.NormalizeAppliesTo : string -&gt; string" Usage="oAuthTokenProvider.NormalizeAppliesTo appliesTo" />
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
        <param name="appliesTo"><span data-ttu-id="8115e-106">正規化を適用するトークン プロバイダー。</span><span class="sxs-lookup"><span data-stu-id="8115e-106">The token provider where the normalization will be applied.</span></span></param>
        <summary><span data-ttu-id="8115e-107">トークン プロバイダーに正規化を適用します。</span><span class="sxs-lookup"><span data-stu-id="8115e-107">Applies normalization into the token provider.</span></span></summary>
        <returns><span data-ttu-id="8115e-108">正規化されたトークン プロバイダー。</span><span class="sxs-lookup"><span data-stu-id="8115e-108">The normalized token provider.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginGetToken">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginGetToken (string appliesTo, string action, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginGetToken(string appliesTo, string action, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.OAuthTokenProvider.OnBeginGetToken(System.String,System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginGetToken (appliesTo As String, action As String, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginGetToken : string * string * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="oAuthTokenProvider.OnBeginGetToken (appliesTo, action, timeout, callback, state)" />
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
        <param name="appliesTo"><span data-ttu-id="8115e-109">トークンが適用されるプロバイダー。</span><span class="sxs-lookup"><span data-stu-id="8115e-109">The provider in which the token will be applied.</span></span></param>
        <param name="action"><span data-ttu-id="8115e-110">アクション。</span><span class="sxs-lookup"><span data-stu-id="8115e-110">The action.</span></span></param>
        <param name="timeout"><span data-ttu-id="8115e-111">期間。</span><span class="sxs-lookup"><span data-stu-id="8115e-111">The duration.</span></span></param>
        <param name="callback"><span data-ttu-id="8115e-112">コールバック。</span><span class="sxs-lookup"><span data-stu-id="8115e-112">The callback.</span></span></param>
        <param name="state"><span data-ttu-id="8115e-113">操作の状態。</span><span class="sxs-lookup"><span data-stu-id="8115e-113">The state of the operation.</span></span></param>
        <summary><span data-ttu-id="8115e-114">プロバイダーが開始されると、トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="8115e-114">Retrieves a token when the provider begins.</span></span></summary>
        <returns><span data-ttu-id="8115e-115">操作の非同期の結果。</span><span class="sxs-lookup"><span data-stu-id="8115e-115">The asynchronous result of the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginGetWebToken">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginGetWebToken (string appliesTo, string action, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginGetWebToken(string appliesTo, string action, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.OAuthTokenProvider.OnBeginGetWebToken(System.String,System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginGetWebToken (appliesTo As String, action As String, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginGetWebToken : string * string * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="oAuthTokenProvider.OnBeginGetWebToken (appliesTo, action, timeout, callback, state)" />
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
        <param name="appliesTo"><span data-ttu-id="8115e-116">プロバイダー web トークンが適用されます。</span><span class="sxs-lookup"><span data-stu-id="8115e-116">The provider in which the web token will be applied.</span></span></param>
        <param name="action"><span data-ttu-id="8115e-117">アクション。</span><span class="sxs-lookup"><span data-stu-id="8115e-117">The action.</span></span></param>
        <param name="timeout"><span data-ttu-id="8115e-118">期間。</span><span class="sxs-lookup"><span data-stu-id="8115e-118">The duration.</span></span></param>
        <param name="callback"><span data-ttu-id="8115e-119">コールバック。</span><span class="sxs-lookup"><span data-stu-id="8115e-119">The callback.</span></span></param>
        <param name="state"><span data-ttu-id="8115e-120">操作の状態。</span><span class="sxs-lookup"><span data-stu-id="8115e-120">The state of the operation.</span></span></param>
        <summary><span data-ttu-id="8115e-121">プロバイダーが開始されると、web トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="8115e-121">Retrieves a web token when the provider begins.</span></span></summary>
        <returns><span data-ttu-id="8115e-122">操作の非同期の結果。</span><span class="sxs-lookup"><span data-stu-id="8115e-122">The asynchronous result of the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndGetToken">
      <MemberSignature Language="C#" Value="protected override System.IdentityModel.Tokens.SecurityToken OnEndGetToken (IAsyncResult result, out DateTime cacheUntil);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IdentityModel.Tokens.SecurityToken OnEndGetToken(class System.IAsyncResult result, [out] valuetype System.DateTime&amp; cacheUntil) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.OAuthTokenProvider.OnEndGetToken(System.IAsyncResult,System.DateTime@)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnEndGetToken (result As IAsyncResult, ByRef cacheUntil As DateTime) As SecurityToken" />
      <MemberSignature Language="F#" Value="override this.OnEndGetToken : IAsyncResult *  -&gt; System.IdentityModel.Tokens.SecurityToken" Usage="oAuthTokenProvider.OnEndGetToken (result, cacheUntil)" />
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
        <param name="result"><span data-ttu-id="8115e-123">操作の結果。</span><span class="sxs-lookup"><span data-stu-id="8115e-123">The result of the operation.</span></span></param>
        <param name="cacheUntil"><span data-ttu-id="8115e-124">データを格納するプロバイダーの期間です。</span><span class="sxs-lookup"><span data-stu-id="8115e-124">The duration for the provider to store data.</span></span></param>
        <summary><span data-ttu-id="8115e-125">プロバイダーの終了時に、トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="8115e-125">Retrieves a token when the provider ends.</span></span></summary>
        <returns><span data-ttu-id="8115e-126">取得したトークンです。</span><span class="sxs-lookup"><span data-stu-id="8115e-126">The retrieved token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndGetWebToken">
      <MemberSignature Language="C#" Value="protected override string OnEndGetWebToken (IAsyncResult result, out DateTime cacheUntil);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance string OnEndGetWebToken(class System.IAsyncResult result, [out] valuetype System.DateTime&amp; cacheUntil) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.OAuthTokenProvider.OnEndGetWebToken(System.IAsyncResult,System.DateTime@)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnEndGetWebToken (result As IAsyncResult, ByRef cacheUntil As DateTime) As String" />
      <MemberSignature Language="F#" Value="override this.OnEndGetWebToken : IAsyncResult *  -&gt; string" Usage="oAuthTokenProvider.OnEndGetWebToken (result, cacheUntil)" />
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
        <param name="result"><span data-ttu-id="8115e-127">操作の結果。</span><span class="sxs-lookup"><span data-stu-id="8115e-127">The result of the operation.</span></span></param>
        <param name="cacheUntil"><span data-ttu-id="8115e-128">データを格納するプロバイダーの期間です。</span><span class="sxs-lookup"><span data-stu-id="8115e-128">The duration for the provider to store data.</span></span></param>
        <summary><span data-ttu-id="8115e-129">プロバイダーの終了時に、web トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="8115e-129">Retrieves a web token when the provider ends.</span></span></summary>
        <returns><span data-ttu-id="8115e-130">取得したトークンです。</span><span class="sxs-lookup"><span data-stu-id="8115e-130">The retrieved token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>