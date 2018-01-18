<Type Name="WindowsTokenProvider" FullName="Microsoft.Azure.NotificationHubs.WindowsTokenProvider">
  <TypeSignature Language="C#" Value="public class WindowsTokenProvider : Microsoft.Azure.NotificationHubs.TokenProvider" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WindowsTokenProvider extends Microsoft.Azure.NotificationHubs.TokenProvider" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.WindowsTokenProvider" />
  <TypeSignature Language="VB.NET" Value="Public Class WindowsTokenProvider&#xA;Inherits TokenProvider" />
  <TypeSignature Language="F#" Value="type WindowsTokenProvider = class&#xA;    inherit TokenProvider" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.NotificationHubs.TokenProvider</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="56f80-101">Service bus のトークン プロバイダーを表します。</span><span class="sxs-lookup"><span data-stu-id="56f80-101">Represents the token provider for the service bus.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BuildKey">
      <MemberSignature Language="C#" Value="protected override Microsoft.Azure.NotificationHubs.TokenProvider.Key BuildKey (string appliesTo, string action);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class Microsoft.Azure.NotificationHubs.TokenProvider/Key BuildKey(string appliesTo, string action) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.WindowsTokenProvider.BuildKey(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function BuildKey (appliesTo As String, action As String) As TokenProvider.Key" />
      <MemberSignature Language="F#" Value="override this.BuildKey : string * string -&gt; Microsoft.Azure.NotificationHubs.TokenProvider.Key" Usage="windowsTokenProvider.BuildKey (appliesTo, action)" />
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
        <param name="appliesTo"><span data-ttu-id="56f80-102">アクセス トークンが適用される URI。</span><span class="sxs-lookup"><span data-stu-id="56f80-102">The URI which the access token applies to.</span></span></param>
        <param name="action"><span data-ttu-id="56f80-103">要求された操作。</span><span class="sxs-lookup"><span data-stu-id="56f80-103">The request action.</span></span></param>
        <summary><span data-ttu-id="56f80-104">トークン プロバイダーをキーを生成します。</span><span class="sxs-lookup"><span data-stu-id="56f80-104">Generates a key for the token provider.</span></span></summary>
        <returns><span data-ttu-id="56f80-105">生成されたキー。</span><span class="sxs-lookup"><span data-stu-id="56f80-105">A generated key.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NormalizeAppliesTo">
      <MemberSignature Language="C#" Value="protected override string NormalizeAppliesTo (string appliesTo);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance string NormalizeAppliesTo(string appliesTo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.WindowsTokenProvider.NormalizeAppliesTo(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function NormalizeAppliesTo (appliesTo As String) As String" />
      <MemberSignature Language="F#" Value="override this.NormalizeAppliesTo : string -&gt; string" Usage="windowsTokenProvider.NormalizeAppliesTo appliesTo" />
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
        <param name="appliesTo"><span data-ttu-id="56f80-106">正規化が適用される URI。</span><span class="sxs-lookup"><span data-stu-id="56f80-106">The URI which the normalization applies to.</span></span></param>
        <summary><span data-ttu-id="56f80-107">Normalize ターゲット アドレスの URI の形式を返します。</span><span class="sxs-lookup"><span data-stu-id="56f80-107">Returns the normalize URI form of the target address.</span></span></summary>
        <returns><span data-ttu-id="56f80-108">正規化のターゲット アドレス URI 形式です。</span><span class="sxs-lookup"><span data-stu-id="56f80-108">The normalize URI form for the target address.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginGetToken">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginGetToken (string appliesTo, string action, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginGetToken(string appliesTo, string action, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.WindowsTokenProvider.OnBeginGetToken(System.String,System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginGetToken (appliesTo As String, action As String, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginGetToken : string * string * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="windowsTokenProvider.OnBeginGetToken (appliesTo, action, timeout, callback, state)" />
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
        <param name="appliesTo"><span data-ttu-id="56f80-109">トークンが適用されるオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="56f80-109">The object where the token will be applied.</span></span></param>
        <param name="action"><span data-ttu-id="56f80-110">アクション。</span><span class="sxs-lookup"><span data-stu-id="56f80-110">The action.</span></span></param>
        <param name="timeout"><span data-ttu-id="56f80-111">操作の期間です。</span><span class="sxs-lookup"><span data-stu-id="56f80-111">The duration of the operation.</span></span></param>
        <param name="callback"><span data-ttu-id="56f80-112">引数 fir プロバイダー。</span><span class="sxs-lookup"><span data-stu-id="56f80-112">The argument fir the provider.</span></span></param>
        <param name="state"><span data-ttu-id="56f80-113">プロバイダーの状態。</span><span class="sxs-lookup"><span data-stu-id="56f80-113">The state of the provider.</span></span></param>
        <summary><span data-ttu-id="56f80-114">プロバイダー サービスが開始されたときに、トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="56f80-114">Retrieves a token when the provider service was started.</span></span></summary>
        <returns><span data-ttu-id="56f80-115">操作の結果。</span><span class="sxs-lookup"><span data-stu-id="56f80-115">The result of the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginGetWebToken">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginGetWebToken (string appliesTo, string action, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginGetWebToken(string appliesTo, string action, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.WindowsTokenProvider.OnBeginGetWebToken(System.String,System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginGetWebToken (appliesTo As String, action As String, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginGetWebToken : string * string * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="windowsTokenProvider.OnBeginGetWebToken (appliesTo, action, timeout, callback, state)" />
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
        <param name="appliesTo"><span data-ttu-id="56f80-116">トークンが適用されるオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="56f80-116">The object where the token will be applied.</span></span></param>
        <param name="action"><span data-ttu-id="56f80-117">アクション。</span><span class="sxs-lookup"><span data-stu-id="56f80-117">The action.</span></span></param>
        <param name="timeout"><span data-ttu-id="56f80-118">操作の期間です。</span><span class="sxs-lookup"><span data-stu-id="56f80-118">The duration of the operation.</span></span></param>
        <param name="callback"><span data-ttu-id="56f80-119">引数 fir プロバイダー。</span><span class="sxs-lookup"><span data-stu-id="56f80-119">The argument fir the provider.</span></span></param>
        <param name="state"><span data-ttu-id="56f80-120">プロバイダーの状態。</span><span class="sxs-lookup"><span data-stu-id="56f80-120">The state of the provider.</span></span></param>
        <summary><span data-ttu-id="56f80-121">プロバイダー サービスが開始されたときに、web トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="56f80-121">Retrieves a web token when the provider service was started.</span></span></summary>
        <returns><span data-ttu-id="56f80-122">操作の結果。</span><span class="sxs-lookup"><span data-stu-id="56f80-122">The result of the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndGetToken">
      <MemberSignature Language="C#" Value="protected override System.IdentityModel.Tokens.SecurityToken OnEndGetToken (IAsyncResult result, out DateTime cacheUntil);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IdentityModel.Tokens.SecurityToken OnEndGetToken(class System.IAsyncResult result, [out] valuetype System.DateTime&amp; cacheUntil) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.WindowsTokenProvider.OnEndGetToken(System.IAsyncResult,System.DateTime@)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnEndGetToken (result As IAsyncResult, ByRef cacheUntil As DateTime) As SecurityToken" />
      <MemberSignature Language="F#" Value="override this.OnEndGetToken : IAsyncResult *  -&gt; System.IdentityModel.Tokens.SecurityToken" Usage="windowsTokenProvider.OnEndGetToken (result, cacheUntil)" />
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
        <param name="result"><span data-ttu-id="56f80-123">操作の結果。</span><span class="sxs-lookup"><span data-stu-id="56f80-123">The result of the operation.</span></span></param>
        <param name="cacheUntil"><span data-ttu-id="56f80-124">データを格納するプロバイダーの時間の指定した期間です。</span><span class="sxs-lookup"><span data-stu-id="56f80-124">The specified duration of time for the provider to store data.</span></span></param>
        <summary><span data-ttu-id="56f80-125">プロバイダー サービスが停止されたときに、トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="56f80-125">Retrieves a token when the provider service was stopped.</span></span></summary>
        <returns><span data-ttu-id="56f80-126">取得したトークンです。</span><span class="sxs-lookup"><span data-stu-id="56f80-126">The retrieved token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndGetWebToken">
      <MemberSignature Language="C#" Value="protected override string OnEndGetWebToken (IAsyncResult result, out DateTime cacheUntil);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance string OnEndGetWebToken(class System.IAsyncResult result, [out] valuetype System.DateTime&amp; cacheUntil) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.WindowsTokenProvider.OnEndGetWebToken(System.IAsyncResult,System.DateTime@)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnEndGetWebToken (result As IAsyncResult, ByRef cacheUntil As DateTime) As String" />
      <MemberSignature Language="F#" Value="override this.OnEndGetWebToken : IAsyncResult *  -&gt; string" Usage="windowsTokenProvider.OnEndGetWebToken (result, cacheUntil)" />
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
        <param name="result"><span data-ttu-id="56f80-127">操作の結果。</span><span class="sxs-lookup"><span data-stu-id="56f80-127">The result of the operation.</span></span></param>
        <param name="cacheUntil"><span data-ttu-id="56f80-128">データを格納するプロバイダーの時間の指定した期間です。</span><span class="sxs-lookup"><span data-stu-id="56f80-128">The specified duration of time for the provider to store data.</span></span></param>
        <summary><span data-ttu-id="56f80-129">プロバイダー サービスが停止されたときに、web トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="56f80-129">Retrieves a web token when the provider service was stopped.</span></span></summary>
        <returns><span data-ttu-id="56f80-130">取得された web トークンです。</span><span class="sxs-lookup"><span data-stu-id="56f80-130">The retrieved web token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>