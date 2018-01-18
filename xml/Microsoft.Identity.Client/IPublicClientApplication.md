<Type Name="IPublicClientApplication" FullName="Microsoft.Identity.Client.IPublicClientApplication">
  <TypeSignature Language="C#" Value="public interface IPublicClientApplication : Microsoft.Identity.Client.IClientApplicationBase" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IPublicClientApplication implements class Microsoft.Identity.Client.IClientApplicationBase" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Identity.Client.IPublicClientApplication" />
  <TypeSignature Language="VB.NET" Value="Public Interface IPublicClientApplication&#xA;Implements IClientApplicationBase" />
  <TypeSignature Language="F#" Value="type IPublicClientApplication = interface&#xA;    interface IClientApplicationBase" />
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
            <span data-ttu-id="3cfb1-101">ネイティブ アプリケーション (デスクトップ/UWP/iOS/Android) に使用するコンポーネントです。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-101">Component to be used for native applications (Desktop/UWP/iOS/Android).</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String)) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iPublicClientApplication.AcquireTokenAsync scopes" />
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
        <param name="scopes"><span data-ttu-id="3cfb1-102">リソースに対して要求されたスコープの配列</span><span class="sxs-lookup"><span data-stu-id="3cfb1-102">Array of scopes requested for resource</span></span></param>
        <summary>
            <span data-ttu-id="3cfb1-103">対話型の要求トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-103">Interactive request to acquire token.</span></span> 
            </summary>
        <returns><span data-ttu-id="3cfb1-104">ユーザーのトークンを含む認証の結果</span><span class="sxs-lookup"><span data-stu-id="3cfb1-104">Authentication result containing token of the user</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.IUser user);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.IUser user) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), user As IUser) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iPublicClientApplication.AcquireTokenAsync (scopes, user)" />
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
        <Parameter Name="user" Type="Microsoft.Identity.Client.IUser" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="3cfb1-105">リソースに対して要求されたスコープの配列</span><span class="sxs-lookup"><span data-stu-id="3cfb1-105">Array of scopes requested for resource</span></span></param>
        <param name="user"><span data-ttu-id="3cfb1-106">Web UI で認証されるため、同じユーザーに適用するユーザー オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-106">User object to enforce the same user to be authenticated in the web UI.</span></span></param>
        <summary>
            <span data-ttu-id="3cfb1-107">対話型の要求トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-107">Interactive request to acquire token.</span></span> 
            </summary>
        <returns><span data-ttu-id="3cfb1-108">ユーザーのトークンを含む認証の結果</span><span class="sxs-lookup"><span data-stu-id="3cfb1-108">Authentication result containing token of the user</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.UIParent parent);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.UIParent parent) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.UIParent)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), parent As UIParent) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * Microsoft.Identity.Client.UIParent -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iPublicClientApplication.AcquireTokenAsync (scopes, parent)" />
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
        <Parameter Name="parent" Type="Microsoft.Identity.Client.UIParent" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="3cfb1-109">リソースに対して要求されたスコープの配列</span><span class="sxs-lookup"><span data-stu-id="3cfb1-109">Array of scopes requested for resource</span></span></param>
        <param name="parent"><span data-ttu-id="3cfb1-110">オブジェクトには、親ウィンドウ/アクティビティへの参照が含まれています。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-110">Object contains reference to parent window/activity.</span></span> <span data-ttu-id="3cfb1-111">Xamarin.Android についてのみ必要です。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-111">REQUIRED for Xamarin.Android only.</span></span></param>
        <summary>
            <span data-ttu-id="3cfb1-112">対話型の要求トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-112">Interactive request to acquire token.</span></span> 
            </summary>
        <returns><span data-ttu-id="3cfb1-113">ユーザーのトークンを含む認証の結果</span><span class="sxs-lookup"><span data-stu-id="3cfb1-113">Authentication result containing token of the user</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, string loginHint);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, string loginHint) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), loginHint As String) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iPublicClientApplication.AcquireTokenAsync (scopes, loginHint)" />
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
        <Parameter Name="loginHint" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="3cfb1-114">リソースに対して要求されたスコープの配列</span><span class="sxs-lookup"><span data-stu-id="3cfb1-114">Array of scopes requested for resource</span></span></param>
        <param name="loginHint"><span data-ttu-id="3cfb1-115">ユーザーの識別子です。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-115">Identifier of the user.</span></span> <span data-ttu-id="3cfb1-116">通常は UPN です。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-116">Generally a UPN.</span></span></param>
        <summary>
            <span data-ttu-id="3cfb1-117">対話型の要求トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-117">Interactive request to acquire token.</span></span> 
            </summary>
        <returns><span data-ttu-id="3cfb1-118">ユーザーのトークンを含む認証の結果</span><span class="sxs-lookup"><span data-stu-id="3cfb1-118">Authentication result containing token of the user</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.IUser user, Microsoft.Identity.Client.UIParent parent);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.IUser user, class Microsoft.Identity.Client.UIParent parent) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser,Microsoft.Identity.Client.UIParent)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), user As IUser, parent As UIParent) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser * Microsoft.Identity.Client.UIParent -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iPublicClientApplication.AcquireTokenAsync (scopes, user, parent)" />
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
        <Parameter Name="user" Type="Microsoft.Identity.Client.IUser" />
        <Parameter Name="parent" Type="Microsoft.Identity.Client.UIParent" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="3cfb1-119">リソースに対して要求されたスコープの配列</span><span class="sxs-lookup"><span data-stu-id="3cfb1-119">Array of scopes requested for resource</span></span></param>
        <param name="user"><span data-ttu-id="3cfb1-120">Web UI で認証されるため、同じユーザーに適用するユーザー オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-120">User object to enforce the same user to be authenticated in the web UI.</span></span></param>
        <param name="parent"><span data-ttu-id="3cfb1-121">オブジェクトには、親ウィンドウ/アクティビティへの参照が含まれています。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-121">Object contains reference to parent window/activity.</span></span> <span data-ttu-id="3cfb1-122">Xamarin.Android についてのみ必要です。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-122">REQUIRED for Xamarin.Android only.</span></span></param>
        <summary>
            <span data-ttu-id="3cfb1-123">対話型の要求トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-123">Interactive request to acquire token.</span></span> 
            </summary>
        <returns><span data-ttu-id="3cfb1-124">ユーザーのトークンを含む認証の結果</span><span class="sxs-lookup"><span data-stu-id="3cfb1-124">Authentication result containing token of the user</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, string loginHint, Microsoft.Identity.Client.UIParent parent);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, string loginHint, class Microsoft.Identity.Client.UIParent parent) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},System.String,Microsoft.Identity.Client.UIParent)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), loginHint As String, parent As UIParent) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * string * Microsoft.Identity.Client.UIParent -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iPublicClientApplication.AcquireTokenAsync (scopes, loginHint, parent)" />
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
        <Parameter Name="loginHint" Type="System.String" />
        <Parameter Name="parent" Type="Microsoft.Identity.Client.UIParent" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="3cfb1-125">リソースに対して要求されたスコープの配列</span><span class="sxs-lookup"><span data-stu-id="3cfb1-125">Array of scopes requested for resource</span></span></param>
        <param name="loginHint"><span data-ttu-id="3cfb1-126">ユーザーの識別子です。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-126">Identifier of the user.</span></span> <span data-ttu-id="3cfb1-127">通常は UPN です。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-127">Generally a UPN.</span></span></param>
        <param name="parent"><span data-ttu-id="3cfb1-128">オブジェクトには、親ウィンドウ/アクティビティへの参照が含まれています。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-128">Object contains reference to parent window/activity.</span></span> <span data-ttu-id="3cfb1-129">Xamarin.Android についてのみ必要です。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-129">REQUIRED for Xamarin.Android only.</span></span></param>
        <summary>
            <span data-ttu-id="3cfb1-130">対話型の要求トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-130">Interactive request to acquire token.</span></span> 
            </summary>
        <returns><span data-ttu-id="3cfb1-131">ユーザーのトークンを含む認証の結果</span><span class="sxs-lookup"><span data-stu-id="3cfb1-131">Authentication result containing token of the user</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.IUser user, Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.IUser user, valuetype Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser,Microsoft.Identity.Client.UIBehavior,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), user As IUser, behavior As UIBehavior, extraQueryParameters As String) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser * Microsoft.Identity.Client.UIBehavior * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iPublicClientApplication.AcquireTokenAsync (scopes, user, behavior, extraQueryParameters)" />
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
        <Parameter Name="user" Type="Microsoft.Identity.Client.IUser" />
        <Parameter Name="behavior" Type="Microsoft.Identity.Client.UIBehavior" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="3cfb1-132">リソースに対して要求されたスコープの配列</span><span class="sxs-lookup"><span data-stu-id="3cfb1-132">Array of scopes requested for resource</span></span></param>
        <param name="user"><span data-ttu-id="3cfb1-133">Web UI で認証されるため、同じユーザーに適用するユーザー オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-133">User object to enforce the same user to be authenticated in the web UI.</span></span></param>
        <param name="behavior"><span data-ttu-id="3cfb1-134">UI の動作を制御する列挙体。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-134">Enumeration to control UI behavior.</span></span></param>
        <param name="extraQueryParameters"><span data-ttu-id="3cfb1-135">証明機関に HTTP 認証要求のクエリ文字列には、このパラメーターが追加されます。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-135">This parameter will be appended as is to the query string in the HTTP authentication request to the authority.</span></span> <span data-ttu-id="3cfb1-136">パラメーターを null にすることができます。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-136">The parameter can be null.</span></span></param>
        <summary>
            <span data-ttu-id="3cfb1-137">対話型の要求トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-137">Interactive request to acquire token.</span></span> 
            </summary>
        <returns><span data-ttu-id="3cfb1-138">ユーザーのトークンを含む認証の結果</span><span class="sxs-lookup"><span data-stu-id="3cfb1-138">Authentication result containing token of the user</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, string loginHint, Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, string loginHint, valuetype Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},System.String,Microsoft.Identity.Client.UIBehavior,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), loginHint As String, behavior As UIBehavior, extraQueryParameters As String) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * string * Microsoft.Identity.Client.UIBehavior * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iPublicClientApplication.AcquireTokenAsync (scopes, loginHint, behavior, extraQueryParameters)" />
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
        <Parameter Name="loginHint" Type="System.String" />
        <Parameter Name="behavior" Type="Microsoft.Identity.Client.UIBehavior" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="3cfb1-139">リソースに対して要求されたスコープの配列</span><span class="sxs-lookup"><span data-stu-id="3cfb1-139">Array of scopes requested for resource</span></span></param>
        <param name="loginHint"><span data-ttu-id="3cfb1-140">ユーザーの識別子です。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-140">Identifier of the user.</span></span> <span data-ttu-id="3cfb1-141">通常は UPN です。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-141">Generally a UPN.</span></span></param>
        <param name="behavior"><span data-ttu-id="3cfb1-142">UI の動作を制御する列挙体。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-142">Enumeration to control UI behavior.</span></span></param>
        <param name="extraQueryParameters"><span data-ttu-id="3cfb1-143">証明機関に HTTP 認証要求のクエリ文字列には、このパラメーターが追加されます。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-143">This parameter will be appended as is to the query string in the HTTP authentication request to the authority.</span></span> <span data-ttu-id="3cfb1-144">パラメーターを null にすることができます。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-144">The parameter can be null.</span></span></param>
        <summary>
            <span data-ttu-id="3cfb1-145">対話型の要求トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-145">Interactive request to acquire token.</span></span> 
            </summary>
        <returns><span data-ttu-id="3cfb1-146">ユーザーのトークンを含む認証の結果</span><span class="sxs-lookup"><span data-stu-id="3cfb1-146">Authentication result containing token of the user</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.IUser user, Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, Microsoft.Identity.Client.UIParent parent);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.IUser user, valuetype Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, class Microsoft.Identity.Client.UIParent parent) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser,Microsoft.Identity.Client.UIBehavior,System.String,Microsoft.Identity.Client.UIParent)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), user As IUser, behavior As UIBehavior, extraQueryParameters As String, parent As UIParent) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser * Microsoft.Identity.Client.UIBehavior * string * Microsoft.Identity.Client.UIParent -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iPublicClientApplication.AcquireTokenAsync (scopes, user, behavior, extraQueryParameters, parent)" />
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
        <Parameter Name="user" Type="Microsoft.Identity.Client.IUser" />
        <Parameter Name="behavior" Type="Microsoft.Identity.Client.UIBehavior" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
        <Parameter Name="parent" Type="Microsoft.Identity.Client.UIParent" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="3cfb1-147">リソースに対して要求されたスコープの配列</span><span class="sxs-lookup"><span data-stu-id="3cfb1-147">Array of scopes requested for resource</span></span></param>
        <param name="user"><span data-ttu-id="3cfb1-148">Web UI で認証されるため、同じユーザーに適用するユーザー オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-148">User object to enforce the same user to be authenticated in the web UI.</span></span></param>
        <param name="behavior"><span data-ttu-id="3cfb1-149">UI の動作を制御する列挙体。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-149">Enumeration to control UI behavior.</span></span></param>
        <param name="extraQueryParameters"><span data-ttu-id="3cfb1-150">証明機関に HTTP 認証要求のクエリ文字列には、このパラメーターが追加されます。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-150">This parameter will be appended as is to the query string in the HTTP authentication request to the authority.</span></span> <span data-ttu-id="3cfb1-151">パラメーターを null にすることができます。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-151">The parameter can be null.</span></span></param>
        <param name="parent"><span data-ttu-id="3cfb1-152">オブジェクトには、親ウィンドウ/アクティビティへの参照が含まれています。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-152">Object contains reference to parent window/activity.</span></span> <span data-ttu-id="3cfb1-153">Xamarin.Android についてのみ必要です。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-153">REQUIRED for Xamarin.Android only.</span></span></param>
        <summary>
            <span data-ttu-id="3cfb1-154">対話型の要求トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-154">Interactive request to acquire token.</span></span> 
            </summary>
        <returns><span data-ttu-id="3cfb1-155">ユーザーのトークンを含む認証の結果</span><span class="sxs-lookup"><span data-stu-id="3cfb1-155">Authentication result containing token of the user</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, string loginHint, Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, Microsoft.Identity.Client.UIParent parent);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, string loginHint, valuetype Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, class Microsoft.Identity.Client.UIParent parent) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},System.String,Microsoft.Identity.Client.UIBehavior,System.String,Microsoft.Identity.Client.UIParent)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), loginHint As String, behavior As UIBehavior, extraQueryParameters As String, parent As UIParent) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * string * Microsoft.Identity.Client.UIBehavior * string * Microsoft.Identity.Client.UIParent -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iPublicClientApplication.AcquireTokenAsync (scopes, loginHint, behavior, extraQueryParameters, parent)" />
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
        <Parameter Name="loginHint" Type="System.String" />
        <Parameter Name="behavior" Type="Microsoft.Identity.Client.UIBehavior" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
        <Parameter Name="parent" Type="Microsoft.Identity.Client.UIParent" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="3cfb1-156">リソースに対して要求されたスコープの配列</span><span class="sxs-lookup"><span data-stu-id="3cfb1-156">Array of scopes requested for resource</span></span></param>
        <param name="loginHint"><span data-ttu-id="3cfb1-157">ユーザーの識別子です。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-157">Identifier of the user.</span></span> <span data-ttu-id="3cfb1-158">通常は UPN です。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-158">Generally a UPN.</span></span></param>
        <param name="behavior"><span data-ttu-id="3cfb1-159">UI の動作を制御する列挙体。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-159">Enumeration to control UI behavior.</span></span></param>
        <param name="extraQueryParameters"><span data-ttu-id="3cfb1-160">証明機関に HTTP 認証要求のクエリ文字列には、このパラメーターが追加されます。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-160">This parameter will be appended as is to the query string in the HTTP authentication request to the authority.</span></span> <span data-ttu-id="3cfb1-161">パラメーターを null にすることができます。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-161">The parameter can be null.</span></span></param>
        <param name="parent"><span data-ttu-id="3cfb1-162">オブジェクトには、親ウィンドウ/アクティビティへの参照が含まれています。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-162">Object contains reference to parent window/activity.</span></span> <span data-ttu-id="3cfb1-163">Xamarin.Android についてのみ必要です。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-163">REQUIRED for Xamarin.Android only.</span></span></param>
        <summary>
            <span data-ttu-id="3cfb1-164">対話型の要求トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-164">Interactive request to acquire token.</span></span> 
            </summary>
        <returns><span data-ttu-id="3cfb1-165">ユーザーのトークンを含む認証の結果</span><span class="sxs-lookup"><span data-stu-id="3cfb1-165">Authentication result containing token of the user</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.IUser user, Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, System.Collections.Generic.IEnumerable&lt;string&gt; extraScopesToConsent, string authority);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.IUser user, valuetype Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, class System.Collections.Generic.IEnumerable`1&lt;string&gt; extraScopesToConsent, string authority) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser,Microsoft.Identity.Client.UIBehavior,System.String,System.Collections.Generic.IEnumerable{System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), user As IUser, behavior As UIBehavior, extraQueryParameters As String, extraScopesToConsent As IEnumerable(Of String), authority As String) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser * Microsoft.Identity.Client.UIBehavior * string * seq&lt;string&gt; * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iPublicClientApplication.AcquireTokenAsync (scopes, user, behavior, extraQueryParameters, extraScopesToConsent, authority)" />
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
        <Parameter Name="user" Type="Microsoft.Identity.Client.IUser" />
        <Parameter Name="behavior" Type="Microsoft.Identity.Client.UIBehavior" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
        <Parameter Name="extraScopesToConsent" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="authority" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="3cfb1-166">リソースに対して要求されたスコープの配列</span><span class="sxs-lookup"><span data-stu-id="3cfb1-166">Array of scopes requested for resource</span></span></param>
        <param name="user"><span data-ttu-id="3cfb1-167">Web UI で認証されるため、同じユーザーに適用するユーザー オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-167">User object to enforce the same user to be authenticated in the web UI.</span></span></param>
        <param name="behavior"><span data-ttu-id="3cfb1-168">UI の動作を制御する列挙体。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-168">Enumeration to control UI behavior.</span></span></param>
        <param name="extraQueryParameters"><span data-ttu-id="3cfb1-169">証明機関に HTTP 認証要求のクエリ文字列には、このパラメーターが追加されます。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-169">This parameter will be appended as is to the query string in the HTTP authentication request to the authority.</span></span> <span data-ttu-id="3cfb1-170">パラメーターを null にすることができます。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-170">The parameter can be null.</span></span></param>
        <param name="extraScopesToConsent"><span data-ttu-id="3cfb1-171">開発者があらかじめ同意を要求できますスコープの配列です。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-171">Array of scopes for which a developer can request consent upfront.</span></span></param>
        <param name="authority"><span data-ttu-id="3cfb1-172">トークンの要求対象となる特定の機関です。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-172">Specific authority for which the token is requested.</span></span> <span data-ttu-id="3cfb1-173">構成されているよりも、別の値を渡すことは、構成済みの値を変更しません。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-173">Passing a different value than configured does not change the configured value</span></span></param>
        <summary>
            <span data-ttu-id="3cfb1-174">対話型の要求トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-174">Interactive request to acquire token.</span></span> 
            </summary>
        <returns><span data-ttu-id="3cfb1-175">ユーザーのトークンを含む認証の結果</span><span class="sxs-lookup"><span data-stu-id="3cfb1-175">Authentication result containing token of the user</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, string loginHint, Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, System.Collections.Generic.IEnumerable&lt;string&gt; extraScopesToConsent, string authority);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, string loginHint, valuetype Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, class System.Collections.Generic.IEnumerable`1&lt;string&gt; extraScopesToConsent, string authority) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},System.String,Microsoft.Identity.Client.UIBehavior,System.String,System.Collections.Generic.IEnumerable{System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), loginHint As String, behavior As UIBehavior, extraQueryParameters As String, extraScopesToConsent As IEnumerable(Of String), authority As String) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * string * Microsoft.Identity.Client.UIBehavior * string * seq&lt;string&gt; * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iPublicClientApplication.AcquireTokenAsync (scopes, loginHint, behavior, extraQueryParameters, extraScopesToConsent, authority)" />
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
        <Parameter Name="loginHint" Type="System.String" />
        <Parameter Name="behavior" Type="Microsoft.Identity.Client.UIBehavior" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
        <Parameter Name="extraScopesToConsent" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="authority" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="3cfb1-176">リソースに対して要求されたスコープの配列</span><span class="sxs-lookup"><span data-stu-id="3cfb1-176">Array of scopes requested for resource</span></span></param>
        <param name="loginHint"><span data-ttu-id="3cfb1-177">ユーザーの識別子です。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-177">Identifier of the user.</span></span> <span data-ttu-id="3cfb1-178">通常は UPN です。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-178">Generally a UPN.</span></span></param>
        <param name="behavior"><span data-ttu-id="3cfb1-179">UI の動作を制御する列挙体。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-179">Enumeration to control UI behavior.</span></span></param>
        <param name="extraQueryParameters"><span data-ttu-id="3cfb1-180">証明機関に HTTP 認証要求のクエリ文字列には、このパラメーターが追加されます。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-180">This parameter will be appended as is to the query string in the HTTP authentication request to the authority.</span></span> <span data-ttu-id="3cfb1-181">パラメーターを null にすることができます。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-181">The parameter can be null.</span></span></param>
        <param name="extraScopesToConsent"><span data-ttu-id="3cfb1-182">開発者があらかじめ同意を要求できますスコープの配列です。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-182">Array of scopes for which a developer can request consent upfront.</span></span></param>
        <param name="authority"><span data-ttu-id="3cfb1-183">トークンの要求対象となる特定の機関です。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-183">Specific authority for which the token is requested.</span></span> <span data-ttu-id="3cfb1-184">構成されているよりも、別の値を渡すことは、構成済みの値を変更しません。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-184">Passing a different value than configured does not change the configured value</span></span></param>
        <summary>
            <span data-ttu-id="3cfb1-185">対話型の要求トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-185">Interactive request to acquire token.</span></span> 
            </summary>
        <returns><span data-ttu-id="3cfb1-186">ユーザーのトークンを含む認証の結果</span><span class="sxs-lookup"><span data-stu-id="3cfb1-186">Authentication result containing token of the user</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.IUser user, Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, System.Collections.Generic.IEnumerable&lt;string&gt; extraScopesToConsent, string authority, Microsoft.Identity.Client.UIParent parent);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.IUser user, valuetype Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, class System.Collections.Generic.IEnumerable`1&lt;string&gt; extraScopesToConsent, string authority, class Microsoft.Identity.Client.UIParent parent) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser,Microsoft.Identity.Client.UIBehavior,System.String,System.Collections.Generic.IEnumerable{System.String},System.String,Microsoft.Identity.Client.UIParent)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), user As IUser, behavior As UIBehavior, extraQueryParameters As String, extraScopesToConsent As IEnumerable(Of String), authority As String, parent As UIParent) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser * Microsoft.Identity.Client.UIBehavior * string * seq&lt;string&gt; * string * Microsoft.Identity.Client.UIParent -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iPublicClientApplication.AcquireTokenAsync (scopes, user, behavior, extraQueryParameters, extraScopesToConsent, authority, parent)" />
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
        <Parameter Name="user" Type="Microsoft.Identity.Client.IUser" />
        <Parameter Name="behavior" Type="Microsoft.Identity.Client.UIBehavior" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
        <Parameter Name="extraScopesToConsent" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="authority" Type="System.String" />
        <Parameter Name="parent" Type="Microsoft.Identity.Client.UIParent" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="3cfb1-187">リソースに対して要求されたスコープの配列</span><span class="sxs-lookup"><span data-stu-id="3cfb1-187">Array of scopes requested for resource</span></span></param>
        <param name="user"><span data-ttu-id="3cfb1-188">Web UI で認証されるため、同じユーザーに適用するユーザー オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-188">User object to enforce the same user to be authenticated in the web UI.</span></span></param>
        <param name="behavior"><span data-ttu-id="3cfb1-189">UI の動作を制御する列挙体。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-189">Enumeration to control UI behavior.</span></span></param>
        <param name="extraQueryParameters"><span data-ttu-id="3cfb1-190">証明機関に HTTP 認証要求のクエリ文字列には、このパラメーターが追加されます。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-190">This parameter will be appended as is to the query string in the HTTP authentication request to the authority.</span></span> <span data-ttu-id="3cfb1-191">パラメーターを null にすることができます。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-191">The parameter can be null.</span></span></param>
        <param name="extraScopesToConsent"><span data-ttu-id="3cfb1-192">開発者があらかじめ同意を要求できますスコープの配列です。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-192">Array of scopes for which a developer can request consent upfront.</span></span></param>
        <param name="authority"><span data-ttu-id="3cfb1-193">トークンの要求対象となる特定の機関です。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-193">Specific authority for which the token is requested.</span></span> <span data-ttu-id="3cfb1-194">構成されているよりも、別の値を渡すことは、構成済みの値を変更しません。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-194">Passing a different value than configured does not change the configured value</span></span></param>
        <param name="parent"><span data-ttu-id="3cfb1-195">オブジェクトには、親ウィンドウ/アクティビティへの参照が含まれています。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-195">Object contains reference to parent window/activity.</span></span> <span data-ttu-id="3cfb1-196">Xamarin.Android についてのみ必要です。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-196">REQUIRED for Xamarin.Android only.</span></span></param>
        <summary>
            <span data-ttu-id="3cfb1-197">対話型の要求トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-197">Interactive request to acquire token.</span></span> 
            </summary>
        <returns><span data-ttu-id="3cfb1-198">ユーザーのトークンを含む認証の結果</span><span class="sxs-lookup"><span data-stu-id="3cfb1-198">Authentication result containing token of the user</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, string loginHint, Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, System.Collections.Generic.IEnumerable&lt;string&gt; extraScopesToConsent, string authority, Microsoft.Identity.Client.UIParent parent);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, string loginHint, valuetype Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, class System.Collections.Generic.IEnumerable`1&lt;string&gt; extraScopesToConsent, string authority, class Microsoft.Identity.Client.UIParent parent) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},System.String,Microsoft.Identity.Client.UIBehavior,System.String,System.Collections.Generic.IEnumerable{System.String},System.String,Microsoft.Identity.Client.UIParent)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), loginHint As String, behavior As UIBehavior, extraQueryParameters As String, extraScopesToConsent As IEnumerable(Of String), authority As String, parent As UIParent) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * string * Microsoft.Identity.Client.UIBehavior * string * seq&lt;string&gt; * string * Microsoft.Identity.Client.UIParent -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iPublicClientApplication.AcquireTokenAsync (scopes, loginHint, behavior, extraQueryParameters, extraScopesToConsent, authority, parent)" />
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
        <Parameter Name="loginHint" Type="System.String" />
        <Parameter Name="behavior" Type="Microsoft.Identity.Client.UIBehavior" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
        <Parameter Name="extraScopesToConsent" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="authority" Type="System.String" />
        <Parameter Name="parent" Type="Microsoft.Identity.Client.UIParent" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="3cfb1-199">リソースに対して要求されたスコープの配列</span><span class="sxs-lookup"><span data-stu-id="3cfb1-199">Array of scopes requested for resource</span></span></param>
        <param name="loginHint"><span data-ttu-id="3cfb1-200">ユーザーの識別子です。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-200">Identifier of the user.</span></span> <span data-ttu-id="3cfb1-201">通常は UPN です。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-201">Generally a UPN.</span></span></param>
        <param name="behavior"><span data-ttu-id="3cfb1-202">UI の動作を制御する列挙体。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-202">Enumeration to control UI behavior.</span></span></param>
        <param name="extraQueryParameters"><span data-ttu-id="3cfb1-203">証明機関に HTTP 認証要求のクエリ文字列には、このパラメーターが追加されます。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-203">This parameter will be appended as is to the query string in the HTTP authentication request to the authority.</span></span> <span data-ttu-id="3cfb1-204">パラメーターを null にすることができます。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-204">The parameter can be null.</span></span></param>
        <param name="extraScopesToConsent"><span data-ttu-id="3cfb1-205">開発者があらかじめ同意を要求できますスコープの配列です。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-205">Array of scopes for which a developer can request consent upfront.</span></span></param>
        <param name="authority"><span data-ttu-id="3cfb1-206">トークンの要求対象となる特定の機関です。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-206">Specific authority for which the token is requested.</span></span> <span data-ttu-id="3cfb1-207">構成されているよりも、別の値を渡すことは、構成済みの値を変更しません。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-207">Passing a different value than configured does not change the configured value</span></span></param>
        <param name="parent"><span data-ttu-id="3cfb1-208">オブジェクトには、親ウィンドウ/アクティビティへの参照が含まれています。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-208">Object contains reference to parent window/activity.</span></span> <span data-ttu-id="3cfb1-209">Xamarin.Android についてのみ必要です。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-209">REQUIRED for Xamarin.Android only.</span></span></param>
        <summary>
            <span data-ttu-id="3cfb1-210">対話型の要求トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="3cfb1-210">Interactive request to acquire token.</span></span> 
            </summary>
        <returns><span data-ttu-id="3cfb1-211">ユーザーのトークンを含む認証の結果</span><span class="sxs-lookup"><span data-stu-id="3cfb1-211">Authentication result containing token of the user</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>