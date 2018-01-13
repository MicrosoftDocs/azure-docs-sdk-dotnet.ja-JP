<Type Name="PublicClientApplication" FullName="Microsoft.Identity.Client.PublicClientApplication">
  <TypeSignature Language="C#" Value="public sealed class PublicClientApplication : Microsoft.Identity.Client.ClientApplicationBase, Microsoft.Identity.Client.IPublicClientApplication" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PublicClientApplication extends Microsoft.Identity.Client.ClientApplicationBase implements class Microsoft.Identity.Client.IClientApplicationBase, class Microsoft.Identity.Client.IPublicClientApplication" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Identity.Client.PublicClientApplication" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PublicClientApplication&#xA;Inherits ClientApplicationBase&#xA;Implements IPublicClientApplication" />
  <TypeSignature Language="F#" Value="type PublicClientApplication = class&#xA;    inherit ClientApplicationBase&#xA;    interface IPublicClientApplication&#xA;    interface IClientApplicationBase" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Identity.Client</AssemblyName>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Identity.Client.ClientApplicationBase</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Identity.Client.IPublicClientApplication</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="1aa3f-101">ネイティブ アプリケーション (デスクトップ/UWP/iOS/Android) 用に使用するクラス。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-101">Class to be used for native applications (Desktop/UWP/iOS/Android).</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PublicClientApplication (string clientId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string clientId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.PublicClientApplication.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (clientId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Identity.Client.PublicClientApplication : string -&gt; Microsoft.Identity.Client.PublicClientApplication" Usage="new Microsoft.Identity.Client.PublicClientApplication clientId" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="clientId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="clientId"><span data-ttu-id="1aa3f-102">アプリケーションのクライアント id</span><span class="sxs-lookup"><span data-stu-id="1aa3f-102">Client id of the application</span></span></param>
        <summary>
            <span data-ttu-id="1aa3f-103">アプリケーションの Consutructor します。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-103">Consutructor of the application.</span></span> <span data-ttu-id="1aa3f-104">既定の機関として https://login.microsoftonline.com/common が使用されます。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-104">It will use https://login.microsoftonline.com/common as the default authority.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PublicClientApplication (string clientId, string authority);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string clientId, string authority) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.PublicClientApplication.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (clientId As String, authority As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Identity.Client.PublicClientApplication : string * string -&gt; Microsoft.Identity.Client.PublicClientApplication" Usage="new Microsoft.Identity.Client.PublicClientApplication (clientId, authority)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="authority" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="clientId"><span data-ttu-id="1aa3f-105">アプリケーションのクライアント id</span><span class="sxs-lookup"><span data-stu-id="1aa3f-105">Client id of the application</span></span></param>
        <param name="authority"><span data-ttu-id="1aa3f-106">アプリケーションに使用する既定の機関</span><span class="sxs-lookup"><span data-stu-id="1aa3f-106">Default authority to be used for the application</span></span></param>
        <summary>
            <span data-ttu-id="1aa3f-107">アプリケーションの Consutructor します。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-107">Consutructor of the application.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PublicClientApplication (string clientId, string authority, Microsoft.Identity.Client.TokenCache userTokenCache);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string clientId, string authority, class Microsoft.Identity.Client.TokenCache userTokenCache) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.PublicClientApplication.#ctor(System.String,System.String,Microsoft.Identity.Client.TokenCache)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (clientId As String, authority As String, userTokenCache As TokenCache)" />
      <MemberSignature Language="F#" Value="new Microsoft.Identity.Client.PublicClientApplication : string * string * Microsoft.Identity.Client.TokenCache -&gt; Microsoft.Identity.Client.PublicClientApplication" Usage="new Microsoft.Identity.Client.PublicClientApplication (clientId, authority, userTokenCache)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="authority" Type="System.String" />
        <Parameter Name="userTokenCache" Type="Microsoft.Identity.Client.TokenCache" />
      </Parameters>
      <Docs>
        <param name="clientId"><span data-ttu-id="1aa3f-108">アプリケーションのクライアント id</span><span class="sxs-lookup"><span data-stu-id="1aa3f-108">Client id of the application</span></span></param>
        <param name="authority"><span data-ttu-id="1aa3f-109">アプリケーションに使用する既定の機関</span><span class="sxs-lookup"><span data-stu-id="1aa3f-109">Default authority to be used for the application</span></span></param>
        <param name="userTokenCache"><span data-ttu-id="1aa3f-110">TokenCache のインスタンス。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-110">Instance of TokenCache.</span></span></param>
        <summary>
            <span data-ttu-id="1aa3f-111">アプリケーション インスタンスを作成するコンス トラクターです。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-111">Constructor to create application instance.</span></span> <span data-ttu-id="1aa3f-112">このコンス トラクターは、デスクトップと NetCore アプリのみ</span><span class="sxs-lookup"><span data-stu-id="1aa3f-112">This constructor is only available for Dekstop and NetCore apps</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.PublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String)) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;&#xA;override this.AcquireTokenAsync : seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="publicClientApplication.AcquireTokenAsync scopes" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.PublicClientApplication/&lt;AcquireTokenAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="1aa3f-113">リソースに対して要求されたスコープの配列</span><span class="sxs-lookup"><span data-stu-id="1aa3f-113">Array of scopes requested for resource</span></span></param>
        <summary>
            <span data-ttu-id="1aa3f-114">対話型の要求トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-114">Interactive request to acquire token.</span></span> 
            </summary>
        <returns><span data-ttu-id="1aa3f-115">ユーザーのトークンを含む認証の結果</span><span class="sxs-lookup"><span data-stu-id="1aa3f-115">Authentication result containing token of the user</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.IUser user);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.IUser user) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.PublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), user As IUser) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;&#xA;override this.AcquireTokenAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="publicClientApplication.AcquireTokenAsync (scopes, user)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.PublicClientApplication/&lt;AcquireTokenAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="user" Type="Microsoft.Identity.Client.IUser" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="1aa3f-116">リソースに対して要求されたスコープの配列</span><span class="sxs-lookup"><span data-stu-id="1aa3f-116">Array of scopes requested for resource</span></span></param>
        <param name="user"><span data-ttu-id="1aa3f-117">Web UI で認証されるため、同じユーザーに適用するユーザー オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-117">User object to enforce the same user to be authenticated in the web UI.</span></span></param>
        <summary>
            <span data-ttu-id="1aa3f-118">対話型の要求トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-118">Interactive request to acquire token.</span></span> 
            </summary>
        <returns><span data-ttu-id="1aa3f-119">ユーザーのトークンを含む認証の結果</span><span class="sxs-lookup"><span data-stu-id="1aa3f-119">Authentication result containing token of the user</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.UIParent parent);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.UIParent parent) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.PublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.UIParent)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), parent As UIParent) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * Microsoft.Identity.Client.UIParent -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;&#xA;override this.AcquireTokenAsync : seq&lt;string&gt; * Microsoft.Identity.Client.UIParent -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="publicClientApplication.AcquireTokenAsync (scopes, parent)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.UIParent)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.PublicClientApplication/&lt;AcquireTokenAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="parent" Type="Microsoft.Identity.Client.UIParent" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="1aa3f-120">リソースに対して要求されたスコープの配列</span><span class="sxs-lookup"><span data-stu-id="1aa3f-120">Array of scopes requested for resource</span></span></param>
        <param name="parent"><span data-ttu-id="1aa3f-121">オブジェクトには、親ウィンドウ/アクティビティへの参照が含まれています。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-121">Object contains reference to parent window/activity.</span></span> <span data-ttu-id="1aa3f-122">Xamarin.Android についてのみ必要です。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-122">REQUIRED for Xamarin.Android only.</span></span></param>
        <summary>
            <span data-ttu-id="1aa3f-123">対話型の要求トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-123">Interactive request to acquire token.</span></span> 
            </summary>
        <returns><span data-ttu-id="1aa3f-124">ユーザーのトークンを含む認証の結果</span><span class="sxs-lookup"><span data-stu-id="1aa3f-124">Authentication result containing token of the user</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, string loginHint);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, string loginHint) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.PublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), loginHint As String) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;&#xA;override this.AcquireTokenAsync : seq&lt;string&gt; * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="publicClientApplication.AcquireTokenAsync (scopes, loginHint)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.PublicClientApplication/&lt;AcquireTokenAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="loginHint" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="1aa3f-125">リソースに対して要求されたスコープの配列</span><span class="sxs-lookup"><span data-stu-id="1aa3f-125">Array of scopes requested for resource</span></span></param>
        <param name="loginHint"><span data-ttu-id="1aa3f-126">ユーザーの識別子です。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-126">Identifier of the user.</span></span> <span data-ttu-id="1aa3f-127">通常は UPN です。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-127">Generally a UPN.</span></span></param>
        <summary>
            <span data-ttu-id="1aa3f-128">対話型の要求トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-128">Interactive request to acquire token.</span></span> 
            </summary>
        <returns><span data-ttu-id="1aa3f-129">ユーザーのトークンを含む認証の結果</span><span class="sxs-lookup"><span data-stu-id="1aa3f-129">Authentication result containing token of the user</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.IUser user, Microsoft.Identity.Client.UIParent parent);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.IUser user, class Microsoft.Identity.Client.UIParent parent) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.PublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser,Microsoft.Identity.Client.UIParent)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), user As IUser, parent As UIParent) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser * Microsoft.Identity.Client.UIParent -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;&#xA;override this.AcquireTokenAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser * Microsoft.Identity.Client.UIParent -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="publicClientApplication.AcquireTokenAsync (scopes, user, parent)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser,Microsoft.Identity.Client.UIParent)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.PublicClientApplication/&lt;AcquireTokenAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="user" Type="Microsoft.Identity.Client.IUser" />
        <Parameter Name="parent" Type="Microsoft.Identity.Client.UIParent" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="1aa3f-130">リソースに対して要求されたスコープの配列</span><span class="sxs-lookup"><span data-stu-id="1aa3f-130">Array of scopes requested for resource</span></span></param>
        <param name="user"><span data-ttu-id="1aa3f-131">Web UI で認証されるため、同じユーザーに適用するユーザー オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-131">User object to enforce the same user to be authenticated in the web UI.</span></span></param>
        <param name="parent"><span data-ttu-id="1aa3f-132">オブジェクトには、親ウィンドウ/アクティビティへの参照が含まれています。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-132">Object contains reference to parent window/activity.</span></span> <span data-ttu-id="1aa3f-133">Xamarin.Android についてのみ必要です。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-133">REQUIRED for Xamarin.Android only.</span></span></param>
        <summary>
            <span data-ttu-id="1aa3f-134">対話型の要求トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-134">Interactive request to acquire token.</span></span> 
            </summary>
        <returns><span data-ttu-id="1aa3f-135">ユーザーのトークンを含む認証の結果</span><span class="sxs-lookup"><span data-stu-id="1aa3f-135">Authentication result containing token of the user</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, string loginHint, Microsoft.Identity.Client.UIParent parent);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, string loginHint, class Microsoft.Identity.Client.UIParent parent) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.PublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},System.String,Microsoft.Identity.Client.UIParent)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), loginHint As String, parent As UIParent) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * string * Microsoft.Identity.Client.UIParent -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;&#xA;override this.AcquireTokenAsync : seq&lt;string&gt; * string * Microsoft.Identity.Client.UIParent -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="publicClientApplication.AcquireTokenAsync (scopes, loginHint, parent)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},System.String,Microsoft.Identity.Client.UIParent)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.PublicClientApplication/&lt;AcquireTokenAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="loginHint" Type="System.String" />
        <Parameter Name="parent" Type="Microsoft.Identity.Client.UIParent" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="1aa3f-136">リソースに対して要求されたスコープの配列</span><span class="sxs-lookup"><span data-stu-id="1aa3f-136">Array of scopes requested for resource</span></span></param>
        <param name="loginHint"><span data-ttu-id="1aa3f-137">ユーザーの識別子です。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-137">Identifier of the user.</span></span> <span data-ttu-id="1aa3f-138">通常は UPN です。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-138">Generally a UPN.</span></span></param>
        <param name="parent"><span data-ttu-id="1aa3f-139">オブジェクトには、親ウィンドウ/アクティビティへの参照が含まれています。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-139">Object contains reference to parent window/activity.</span></span> <span data-ttu-id="1aa3f-140">Xamarin.Android についてのみ必要です。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-140">REQUIRED for Xamarin.Android only.</span></span></param>
        <summary>
            <span data-ttu-id="1aa3f-141">対話型の要求トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-141">Interactive request to acquire token.</span></span> 
            </summary>
        <returns><span data-ttu-id="1aa3f-142">ユーザーのトークンを含む認証の結果</span><span class="sxs-lookup"><span data-stu-id="1aa3f-142">Authentication result containing token of the user</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.IUser user, Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.IUser user, valuetype Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.PublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser,Microsoft.Identity.Client.UIBehavior,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), user As IUser, behavior As UIBehavior, extraQueryParameters As String) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser * Microsoft.Identity.Client.UIBehavior * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;&#xA;override this.AcquireTokenAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser * Microsoft.Identity.Client.UIBehavior * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="publicClientApplication.AcquireTokenAsync (scopes, user, behavior, extraQueryParameters)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser,Microsoft.Identity.Client.UIBehavior,System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.PublicClientApplication/&lt;AcquireTokenAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
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
        <param name="scopes"><span data-ttu-id="1aa3f-143">リソースに対して要求されたスコープの配列</span><span class="sxs-lookup"><span data-stu-id="1aa3f-143">Array of scopes requested for resource</span></span></param>
        <param name="user"><span data-ttu-id="1aa3f-144">Web UI で認証されるため、同じユーザーに適用するユーザー オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-144">User object to enforce the same user to be authenticated in the web UI.</span></span></param>
        <param name="behavior"><span data-ttu-id="1aa3f-145">UI の動作を制御する列挙体。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-145">Enumeration to control UI behavior.</span></span></param>
        <param name="extraQueryParameters"><span data-ttu-id="1aa3f-146">証明機関に HTTP 認証要求のクエリ文字列には、このパラメーターが追加されます。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-146">This parameter will be appended as is to the query string in the HTTP authentication request to the authority.</span></span> <span data-ttu-id="1aa3f-147">パラメーターを null にすることができます。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-147">The parameter can be null.</span></span></param>
        <summary>
            <span data-ttu-id="1aa3f-148">対話型の要求トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-148">Interactive request to acquire token.</span></span> 
            </summary>
        <returns><span data-ttu-id="1aa3f-149">ユーザーのトークンを含む認証の結果</span><span class="sxs-lookup"><span data-stu-id="1aa3f-149">Authentication result containing token of the user</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, string loginHint, Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, string loginHint, valuetype Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.PublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},System.String,Microsoft.Identity.Client.UIBehavior,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), loginHint As String, behavior As UIBehavior, extraQueryParameters As String) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * string * Microsoft.Identity.Client.UIBehavior * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;&#xA;override this.AcquireTokenAsync : seq&lt;string&gt; * string * Microsoft.Identity.Client.UIBehavior * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="publicClientApplication.AcquireTokenAsync (scopes, loginHint, behavior, extraQueryParameters)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},System.String,Microsoft.Identity.Client.UIBehavior,System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.PublicClientApplication/&lt;AcquireTokenAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
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
        <param name="scopes"><span data-ttu-id="1aa3f-150">リソースに対して要求されたスコープの配列</span><span class="sxs-lookup"><span data-stu-id="1aa3f-150">Array of scopes requested for resource</span></span></param>
        <param name="loginHint"><span data-ttu-id="1aa3f-151">ユーザーの識別子です。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-151">Identifier of the user.</span></span> <span data-ttu-id="1aa3f-152">通常は UPN です。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-152">Generally a UPN.</span></span></param>
        <param name="behavior"><span data-ttu-id="1aa3f-153">UI の動作を制御する列挙体。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-153">Enumeration to control UI behavior.</span></span></param>
        <param name="extraQueryParameters"><span data-ttu-id="1aa3f-154">証明機関に HTTP 認証要求のクエリ文字列には、このパラメーターが追加されます。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-154">This parameter will be appended as is to the query string in the HTTP authentication request to the authority.</span></span> <span data-ttu-id="1aa3f-155">パラメーターを null にすることができます。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-155">The parameter can be null.</span></span></param>
        <summary>
            <span data-ttu-id="1aa3f-156">対話型の要求トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-156">Interactive request to acquire token.</span></span> 
            </summary>
        <returns><span data-ttu-id="1aa3f-157">ユーザーのトークンを含む認証の結果</span><span class="sxs-lookup"><span data-stu-id="1aa3f-157">Authentication result containing token of the user</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.IUser user, Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, Microsoft.Identity.Client.UIParent parent);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.IUser user, valuetype Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, class Microsoft.Identity.Client.UIParent parent) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.PublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser,Microsoft.Identity.Client.UIBehavior,System.String,Microsoft.Identity.Client.UIParent)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), user As IUser, behavior As UIBehavior, extraQueryParameters As String, parent As UIParent) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser * Microsoft.Identity.Client.UIBehavior * string * Microsoft.Identity.Client.UIParent -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;&#xA;override this.AcquireTokenAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser * Microsoft.Identity.Client.UIBehavior * string * Microsoft.Identity.Client.UIParent -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="publicClientApplication.AcquireTokenAsync (scopes, user, behavior, extraQueryParameters, parent)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser,Microsoft.Identity.Client.UIBehavior,System.String,Microsoft.Identity.Client.UIParent)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.PublicClientApplication/&lt;AcquireTokenAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
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
        <param name="scopes"><span data-ttu-id="1aa3f-158">リソースに対して要求されたスコープの配列</span><span class="sxs-lookup"><span data-stu-id="1aa3f-158">Array of scopes requested for resource</span></span></param>
        <param name="user"><span data-ttu-id="1aa3f-159">Web UI で認証されるため、同じユーザーに適用するユーザー オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-159">User object to enforce the same user to be authenticated in the web UI.</span></span></param>
        <param name="behavior"><span data-ttu-id="1aa3f-160">UI の動作を制御する列挙体。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-160">Enumeration to control UI behavior.</span></span></param>
        <param name="extraQueryParameters"><span data-ttu-id="1aa3f-161">証明機関に HTTP 認証要求のクエリ文字列には、このパラメーターが追加されます。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-161">This parameter will be appended as is to the query string in the HTTP authentication request to the authority.</span></span> <span data-ttu-id="1aa3f-162">パラメーターを null にすることができます。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-162">The parameter can be null.</span></span></param>
        <param name="parent"><span data-ttu-id="1aa3f-163">オブジェクトには、親ウィンドウ/アクティビティへの参照が含まれています。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-163">Object contains reference to parent window/activity.</span></span> <span data-ttu-id="1aa3f-164">Xamarin.Android についてのみ必要です。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-164">REQUIRED for Xamarin.Android only.</span></span></param>
        <summary>
            <span data-ttu-id="1aa3f-165">対話型の要求トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-165">Interactive request to acquire token.</span></span> 
            </summary>
        <returns><span data-ttu-id="1aa3f-166">ユーザーのトークンを含む認証の結果</span><span class="sxs-lookup"><span data-stu-id="1aa3f-166">Authentication result containing token of the user</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, string loginHint, Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, Microsoft.Identity.Client.UIParent parent);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, string loginHint, valuetype Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, class Microsoft.Identity.Client.UIParent parent) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.PublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},System.String,Microsoft.Identity.Client.UIBehavior,System.String,Microsoft.Identity.Client.UIParent)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), loginHint As String, behavior As UIBehavior, extraQueryParameters As String, parent As UIParent) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * string * Microsoft.Identity.Client.UIBehavior * string * Microsoft.Identity.Client.UIParent -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;&#xA;override this.AcquireTokenAsync : seq&lt;string&gt; * string * Microsoft.Identity.Client.UIBehavior * string * Microsoft.Identity.Client.UIParent -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="publicClientApplication.AcquireTokenAsync (scopes, loginHint, behavior, extraQueryParameters, parent)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},System.String,Microsoft.Identity.Client.UIBehavior,System.String,Microsoft.Identity.Client.UIParent)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.PublicClientApplication/&lt;AcquireTokenAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
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
        <param name="scopes"><span data-ttu-id="1aa3f-167">リソースに対して要求されたスコープの配列</span><span class="sxs-lookup"><span data-stu-id="1aa3f-167">Array of scopes requested for resource</span></span></param>
        <param name="loginHint"><span data-ttu-id="1aa3f-168">ユーザーの識別子です。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-168">Identifier of the user.</span></span> <span data-ttu-id="1aa3f-169">通常は UPN です。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-169">Generally a UPN.</span></span></param>
        <param name="behavior"><span data-ttu-id="1aa3f-170">UI の動作を制御する列挙体。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-170">Enumeration to control UI behavior.</span></span></param>
        <param name="extraQueryParameters"><span data-ttu-id="1aa3f-171">証明機関に HTTP 認証要求のクエリ文字列には、このパラメーターが追加されます。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-171">This parameter will be appended as is to the query string in the HTTP authentication request to the authority.</span></span> <span data-ttu-id="1aa3f-172">パラメーターを null にすることができます。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-172">The parameter can be null.</span></span></param>
        <param name="parent"><span data-ttu-id="1aa3f-173">オブジェクトには、親ウィンドウ/アクティビティへの参照が含まれています。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-173">Object contains reference to parent window/activity.</span></span> <span data-ttu-id="1aa3f-174">Xamarin.Android についてのみ必要です。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-174">REQUIRED for Xamarin.Android only.</span></span></param>
        <summary>
            <span data-ttu-id="1aa3f-175">対話型の要求トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-175">Interactive request to acquire token.</span></span> 
            </summary>
        <returns><span data-ttu-id="1aa3f-176">ユーザーのトークンを含む認証の結果</span><span class="sxs-lookup"><span data-stu-id="1aa3f-176">Authentication result containing token of the user</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.IUser user, Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, System.Collections.Generic.IEnumerable&lt;string&gt; extraScopesToConsent, string authority);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.IUser user, valuetype Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, class System.Collections.Generic.IEnumerable`1&lt;string&gt; extraScopesToConsent, string authority) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.PublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser,Microsoft.Identity.Client.UIBehavior,System.String,System.Collections.Generic.IEnumerable{System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), user As IUser, behavior As UIBehavior, extraQueryParameters As String, extraScopesToConsent As IEnumerable(Of String), authority As String) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser * Microsoft.Identity.Client.UIBehavior * string * seq&lt;string&gt; * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;&#xA;override this.AcquireTokenAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser * Microsoft.Identity.Client.UIBehavior * string * seq&lt;string&gt; * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="publicClientApplication.AcquireTokenAsync (scopes, user, behavior, extraQueryParameters, extraScopesToConsent, authority)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser,Microsoft.Identity.Client.UIBehavior,System.String,System.Collections.Generic.IEnumerable{System.String},System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.PublicClientApplication/&lt;AcquireTokenAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
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
        <param name="scopes"><span data-ttu-id="1aa3f-177">リソースに対して要求されたスコープの配列</span><span class="sxs-lookup"><span data-stu-id="1aa3f-177">Array of scopes requested for resource</span></span></param>
        <param name="user"><span data-ttu-id="1aa3f-178">Web UI で認証されるため、同じユーザーに適用するユーザー オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-178">User object to enforce the same user to be authenticated in the web UI.</span></span></param>
        <param name="behavior"><span data-ttu-id="1aa3f-179">UI の動作を制御する列挙体。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-179">Enumeration to control UI behavior.</span></span></param>
        <param name="extraQueryParameters"><span data-ttu-id="1aa3f-180">証明機関に HTTP 認証要求のクエリ文字列には、このパラメーターが追加されます。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-180">This parameter will be appended as is to the query string in the HTTP authentication request to the authority.</span></span> <span data-ttu-id="1aa3f-181">パラメーターを null にすることができます。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-181">The parameter can be null.</span></span></param>
        <param name="extraScopesToConsent"><span data-ttu-id="1aa3f-182">開発者があらかじめ同意を要求できますスコープの配列です。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-182">Array of scopes for which a developer can request consent upfront.</span></span></param>
        <param name="authority"><span data-ttu-id="1aa3f-183">トークンの要求対象となる特定の機関です。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-183">Specific authority for which the token is requested.</span></span> <span data-ttu-id="1aa3f-184">構成されているよりも、別の値を渡すことは、構成済みの値を変更しません。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-184">Passing a different value than configured does not change the configured value</span></span></param>
        <summary>
            <span data-ttu-id="1aa3f-185">対話型の要求トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-185">Interactive request to acquire token.</span></span> 
            </summary>
        <returns><span data-ttu-id="1aa3f-186">ユーザーのトークンを含む認証の結果</span><span class="sxs-lookup"><span data-stu-id="1aa3f-186">Authentication result containing token of the user</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, string loginHint, Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, System.Collections.Generic.IEnumerable&lt;string&gt; extraScopesToConsent, string authority);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, string loginHint, valuetype Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, class System.Collections.Generic.IEnumerable`1&lt;string&gt; extraScopesToConsent, string authority) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.PublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},System.String,Microsoft.Identity.Client.UIBehavior,System.String,System.Collections.Generic.IEnumerable{System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), loginHint As String, behavior As UIBehavior, extraQueryParameters As String, extraScopesToConsent As IEnumerable(Of String), authority As String) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * string * Microsoft.Identity.Client.UIBehavior * string * seq&lt;string&gt; * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;&#xA;override this.AcquireTokenAsync : seq&lt;string&gt; * string * Microsoft.Identity.Client.UIBehavior * string * seq&lt;string&gt; * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="publicClientApplication.AcquireTokenAsync (scopes, loginHint, behavior, extraQueryParameters, extraScopesToConsent, authority)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},System.String,Microsoft.Identity.Client.UIBehavior,System.String,System.Collections.Generic.IEnumerable{System.String},System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.PublicClientApplication/&lt;AcquireTokenAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
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
        <param name="scopes"><span data-ttu-id="1aa3f-187">リソースに対して要求されたスコープの配列</span><span class="sxs-lookup"><span data-stu-id="1aa3f-187">Array of scopes requested for resource</span></span></param>
        <param name="loginHint"><span data-ttu-id="1aa3f-188">ユーザーの識別子です。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-188">Identifier of the user.</span></span> <span data-ttu-id="1aa3f-189">通常は UPN です。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-189">Generally a UPN.</span></span></param>
        <param name="behavior"><span data-ttu-id="1aa3f-190">UI の動作を制御する列挙体。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-190">Enumeration to control UI behavior.</span></span></param>
        <param name="extraQueryParameters"><span data-ttu-id="1aa3f-191">証明機関に HTTP 認証要求のクエリ文字列には、このパラメーターが追加されます。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-191">This parameter will be appended as is to the query string in the HTTP authentication request to the authority.</span></span> <span data-ttu-id="1aa3f-192">パラメーターを null にすることができます。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-192">The parameter can be null.</span></span></param>
        <param name="extraScopesToConsent"><span data-ttu-id="1aa3f-193">開発者があらかじめ同意を要求できますスコープの配列です。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-193">Array of scopes for which a developer can request consent upfront.</span></span></param>
        <param name="authority"><span data-ttu-id="1aa3f-194">トークンの要求対象となる特定の機関です。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-194">Specific authority for which the token is requested.</span></span> <span data-ttu-id="1aa3f-195">構成されているよりも、別の値を渡すことは、構成済みの値を変更しません。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-195">Passing a different value than configured does not change the configured value</span></span></param>
        <summary>
            <span data-ttu-id="1aa3f-196">対話型の要求トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-196">Interactive request to acquire token.</span></span> 
            </summary>
        <returns><span data-ttu-id="1aa3f-197">ユーザーのトークンを含む認証の結果</span><span class="sxs-lookup"><span data-stu-id="1aa3f-197">Authentication result containing token of the user</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.IUser user, Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, System.Collections.Generic.IEnumerable&lt;string&gt; extraScopesToConsent, string authority, Microsoft.Identity.Client.UIParent parent);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.IUser user, valuetype Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, class System.Collections.Generic.IEnumerable`1&lt;string&gt; extraScopesToConsent, string authority, class Microsoft.Identity.Client.UIParent parent) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.PublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser,Microsoft.Identity.Client.UIBehavior,System.String,System.Collections.Generic.IEnumerable{System.String},System.String,Microsoft.Identity.Client.UIParent)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), user As IUser, behavior As UIBehavior, extraQueryParameters As String, extraScopesToConsent As IEnumerable(Of String), authority As String, parent As UIParent) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser * Microsoft.Identity.Client.UIBehavior * string * seq&lt;string&gt; * string * Microsoft.Identity.Client.UIParent -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;&#xA;override this.AcquireTokenAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser * Microsoft.Identity.Client.UIBehavior * string * seq&lt;string&gt; * string * Microsoft.Identity.Client.UIParent -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="publicClientApplication.AcquireTokenAsync (scopes, user, behavior, extraQueryParameters, extraScopesToConsent, authority, parent)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser,Microsoft.Identity.Client.UIBehavior,System.String,System.Collections.Generic.IEnumerable{System.String},System.String,Microsoft.Identity.Client.UIParent)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.PublicClientApplication/&lt;AcquireTokenAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
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
        <param name="scopes"><span data-ttu-id="1aa3f-198">リソースに対して要求されたスコープの配列</span><span class="sxs-lookup"><span data-stu-id="1aa3f-198">Array of scopes requested for resource</span></span></param>
        <param name="user"><span data-ttu-id="1aa3f-199">Web UI で認証されるため、同じユーザーに適用するユーザー オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-199">User object to enforce the same user to be authenticated in the web UI.</span></span></param>
        <param name="behavior"><span data-ttu-id="1aa3f-200">UI の動作を制御する列挙体。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-200">Enumeration to control UI behavior.</span></span></param>
        <param name="extraQueryParameters"><span data-ttu-id="1aa3f-201">証明機関に HTTP 認証要求のクエリ文字列には、このパラメーターが追加されます。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-201">This parameter will be appended as is to the query string in the HTTP authentication request to the authority.</span></span> <span data-ttu-id="1aa3f-202">パラメーターを null にすることができます。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-202">The parameter can be null.</span></span></param>
        <param name="extraScopesToConsent"><span data-ttu-id="1aa3f-203">開発者があらかじめ同意を要求できますスコープの配列です。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-203">Array of scopes for which a developer can request consent upfront.</span></span></param>
        <param name="authority"><span data-ttu-id="1aa3f-204">トークンの要求対象となる特定の機関です。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-204">Specific authority for which the token is requested.</span></span> <span data-ttu-id="1aa3f-205">構成されているよりも、別の値を渡すことは、構成済みの値を変更しません。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-205">Passing a different value than configured does not change the configured value</span></span></param>
        <param name="parent"><span data-ttu-id="1aa3f-206">オブジェクトには、親ウィンドウ/アクティビティへの参照が含まれています。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-206">Object contains reference to parent window/activity.</span></span> <span data-ttu-id="1aa3f-207">Xamarin.Android についてのみ必要です。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-207">REQUIRED for Xamarin.Android only.</span></span></param>
        <summary>
            <span data-ttu-id="1aa3f-208">対話型の要求トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-208">Interactive request to acquire token.</span></span> 
            </summary>
        <returns><span data-ttu-id="1aa3f-209">ユーザーのトークンを含む認証の結果</span><span class="sxs-lookup"><span data-stu-id="1aa3f-209">Authentication result containing token of the user</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, string loginHint, Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, System.Collections.Generic.IEnumerable&lt;string&gt; extraScopesToConsent, string authority, Microsoft.Identity.Client.UIParent parent);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, string loginHint, valuetype Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, class System.Collections.Generic.IEnumerable`1&lt;string&gt; extraScopesToConsent, string authority, class Microsoft.Identity.Client.UIParent parent) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.PublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},System.String,Microsoft.Identity.Client.UIBehavior,System.String,System.Collections.Generic.IEnumerable{System.String},System.String,Microsoft.Identity.Client.UIParent)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), loginHint As String, behavior As UIBehavior, extraQueryParameters As String, extraScopesToConsent As IEnumerable(Of String), authority As String, parent As UIParent) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * string * Microsoft.Identity.Client.UIBehavior * string * seq&lt;string&gt; * string * Microsoft.Identity.Client.UIParent -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;&#xA;override this.AcquireTokenAsync : seq&lt;string&gt; * string * Microsoft.Identity.Client.UIBehavior * string * seq&lt;string&gt; * string * Microsoft.Identity.Client.UIParent -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="publicClientApplication.AcquireTokenAsync (scopes, loginHint, behavior, extraQueryParameters, extraScopesToConsent, authority, parent)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},System.String,Microsoft.Identity.Client.UIBehavior,System.String,System.Collections.Generic.IEnumerable{System.String},System.String,Microsoft.Identity.Client.UIParent)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.PublicClientApplication/&lt;AcquireTokenAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
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
        <param name="scopes"><span data-ttu-id="1aa3f-210">リソースに対して要求されたスコープの配列</span><span class="sxs-lookup"><span data-stu-id="1aa3f-210">Array of scopes requested for resource</span></span></param>
        <param name="loginHint"><span data-ttu-id="1aa3f-211">ユーザーの識別子です。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-211">Identifier of the user.</span></span> <span data-ttu-id="1aa3f-212">通常は UPN です。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-212">Generally a UPN.</span></span></param>
        <param name="behavior"><span data-ttu-id="1aa3f-213">UI の動作を制御する列挙体。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-213">Enumeration to control UI behavior.</span></span></param>
        <param name="extraQueryParameters"><span data-ttu-id="1aa3f-214">証明機関に HTTP 認証要求のクエリ文字列には、このパラメーターが追加されます。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-214">This parameter will be appended as is to the query string in the HTTP authentication request to the authority.</span></span> <span data-ttu-id="1aa3f-215">パラメーターを null にすることができます。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-215">The parameter can be null.</span></span></param>
        <param name="extraScopesToConsent"><span data-ttu-id="1aa3f-216">開発者があらかじめ同意を要求できますスコープの配列です。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-216">Array of scopes for which a developer can request consent upfront.</span></span></param>
        <param name="authority"><span data-ttu-id="1aa3f-217">トークンの要求対象となる特定の機関です。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-217">Specific authority for which the token is requested.</span></span> <span data-ttu-id="1aa3f-218">構成されているよりも、別の値を渡すことは、構成済みの値を変更しません。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-218">Passing a different value than configured does not change the configured value</span></span></param>
        <param name="parent"><span data-ttu-id="1aa3f-219">オブジェクトには、親ウィンドウ/アクティビティへの参照が含まれています。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-219">Object contains reference to parent window/activity.</span></span> <span data-ttu-id="1aa3f-220">Xamarin.Android についてのみ必要です。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-220">REQUIRED for Xamarin.Android only.</span></span></param>
        <summary>
            <span data-ttu-id="1aa3f-221">対話型の要求トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="1aa3f-221">Interactive request to acquire token.</span></span> 
            </summary>
        <returns><span data-ttu-id="1aa3f-222">ユーザーのトークンを含む認証の結果</span><span class="sxs-lookup"><span data-stu-id="1aa3f-222">Authentication result containing token of the user</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>