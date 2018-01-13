<Type Name="TokenProvider" FullName="Microsoft.Azure.Relay.TokenProvider">
  <TypeSignature Language="C#" Value="public abstract class TokenProvider" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit TokenProvider extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Relay.TokenProvider" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class TokenProvider" />
  <TypeSignature Language="F#" Value="type TokenProvider = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="13b1b-101">追加のトークン プロバイダーを実装するのには、この抽象基本クラスを拡張できます。</span><span class="sxs-lookup"><span data-stu-id="13b1b-101">This abstract base class can be extended to implement additional token providers.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected TokenProvider ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.TokenProvider.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="13b1b-102"><see cref="T:Microsoft.Azure.Relay.TokenProvider" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="13b1b-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.Relay.TokenProvider" /> class.</span></span> </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedAccessSignatureTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Relay.TokenProvider CreateSharedAccessSignatureTokenProvider (string sharedAccessSignature);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Relay.TokenProvider CreateSharedAccessSignatureTokenProvider(string sharedAccessSignature) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.TokenProvider.CreateSharedAccessSignatureTokenProvider(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSharedAccessSignatureTokenProvider (sharedAccessSignature As String) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSharedAccessSignatureTokenProvider : string -&gt; Microsoft.Azure.Relay.TokenProvider" Usage="Microsoft.Azure.Relay.TokenProvider.CreateSharedAccessSignatureTokenProvider sharedAccessSignature" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Relay.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sharedAccessSignature" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sharedAccessSignature"><span data-ttu-id="13b1b-103">共有アクセス署名</span><span class="sxs-lookup"><span data-stu-id="13b1b-103">The shared access signature</span></span></param>
        <summary>
            <span data-ttu-id="13b1b-104">SharedAccessSignature に基づいて TokenProvider を構築します。</span><span class="sxs-lookup"><span data-stu-id="13b1b-104">Construct a TokenProvider based on a sharedAccessSignature.</span></span>
            </summary>
        <returns><span data-ttu-id="13b1b-105">共有アクセス署名を使用して初期化 TokenProvider</span><span class="sxs-lookup"><span data-stu-id="13b1b-105">A TokenProvider initialized with the shared access signature</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedAccessSignatureTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Relay.TokenProvider CreateSharedAccessSignatureTokenProvider (string keyName, string sharedAccessKey);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Relay.TokenProvider CreateSharedAccessSignatureTokenProvider(string keyName, string sharedAccessKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.TokenProvider.CreateSharedAccessSignatureTokenProvider(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSharedAccessSignatureTokenProvider (keyName As String, sharedAccessKey As String) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSharedAccessSignatureTokenProvider : string * string -&gt; Microsoft.Azure.Relay.TokenProvider" Usage="Microsoft.Azure.Relay.TokenProvider.CreateSharedAccessSignatureTokenProvider (keyName, sharedAccessKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Relay.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="sharedAccessKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="keyName"><span data-ttu-id="13b1b-106">対応する SharedAccessKeyAuthorizationRule のキー名。</span><span class="sxs-lookup"><span data-stu-id="13b1b-106">The key name of the corresponding SharedAccessKeyAuthorizationRule.</span></span></param>
        <param name="sharedAccessKey"><span data-ttu-id="13b1b-107">SharedAccessKeyAuthorizationRule に関連付けられたキー</span><span class="sxs-lookup"><span data-stu-id="13b1b-107">The key associated with the SharedAccessKeyAuthorizationRule</span></span></param>
        <summary>
            <span data-ttu-id="13b1b-108">指定されたキー名と共有アクセス キーに基づく TokenProvider を構築します。</span><span class="sxs-lookup"><span data-stu-id="13b1b-108">Construct a TokenProvider based on the provided Key Name and Shared Access Key.</span></span>
            </summary>
        <returns><span data-ttu-id="13b1b-109">指定された規則 Id とパスワードを使用して初期化 TokenProvider</span><span class="sxs-lookup"><span data-stu-id="13b1b-109">A TokenProvider initialized with the provided RuleId and Password</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.SecurityToken&gt; GetTokenAsync (string audience, TimeSpan validFor);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Relay.SecurityToken&gt; GetTokenAsync(string audience, valuetype System.TimeSpan validFor) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.TokenProvider.GetTokenAsync(System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetTokenAsync (audience As String, validFor As TimeSpan) As Task(Of SecurityToken)" />
      <MemberSignature Language="F#" Value="member this.GetTokenAsync : string * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.SecurityToken&gt;" Usage="tokenProvider.GetTokenAsync (audience, validFor)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.SecurityToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="audience" Type="System.String" />
        <Parameter Name="validFor" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="audience"><span data-ttu-id="13b1b-110">セキュリティ トークンの対象ユーザー。</span><span class="sxs-lookup"><span data-stu-id="13b1b-110">The target audience for the security token.</span></span></param>
        <param name="validFor"><span data-ttu-id="13b1b-111">どのくらいの期間、生成されたトークンはに対して有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="13b1b-111">How long the generated token should be valid for.</span></span></param>
        <summary>
            <span data-ttu-id="13b1b-112">取得、<see cref="T:Microsoft.Azure.Relay.SecurityToken" />指定された対象ユーザーと期間。</span><span class="sxs-lookup"><span data-stu-id="13b1b-112">Gets a <see cref="T:Microsoft.Azure.Relay.SecurityToken" /> for the given audience and duration.</span></span>
            </summary>
        <returns><span data-ttu-id="13b1b-113">新しく作成された SecurityToken を返すタスク。</span><span class="sxs-lookup"><span data-stu-id="13b1b-113">A Task returning the newly created SecurityToken.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnGetTokenAsync">
      <MemberSignature Language="C#" Value="protected abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.SecurityToken&gt; OnGetTokenAsync (string audience, TimeSpan validFor);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Relay.SecurityToken&gt; OnGetTokenAsync(string audience, valuetype System.TimeSpan validFor) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.TokenProvider.OnGetTokenAsync(System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnGetTokenAsync (audience As String, validFor As TimeSpan) As Task(Of SecurityToken)" />
      <MemberSignature Language="F#" Value="abstract member OnGetTokenAsync : string * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.SecurityToken&gt;" Usage="tokenProvider.OnGetTokenAsync (audience, validFor)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.SecurityToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="audience" Type="System.String" />
        <Parameter Name="validFor" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="audience"><span data-ttu-id="13b1b-114">セキュリティ トークンの対象ユーザー。</span><span class="sxs-lookup"><span data-stu-id="13b1b-114">The target audience for the security token.</span></span></param>
        <param name="validFor"><span data-ttu-id="13b1b-115">どのくらいの期間、生成されたトークンはに対して有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="13b1b-115">How long the generated token should be valid for.</span></span></param>
        <summary>
            <span data-ttu-id="13b1b-116">その SecurityTokens を生成する派生の TokenProvider 型によって実装されます。</span><span class="sxs-lookup"><span data-stu-id="13b1b-116">Implemented by derived TokenProvider types to generate their SecurityTokens.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ThisLock">
      <MemberSignature Language="C#" Value="protected object ThisLock { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object ThisLock" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.TokenProvider.ThisLock" />
      <MemberSignature Language="VB.NET" Value="Protected ReadOnly Property ThisLock As Object" />
      <MemberSignature Language="F#" Value="member this.ThisLock : obj" Usage="Microsoft.Azure.Relay.TokenProvider.ThisLock" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="13b1b-117">指定されたインスタンスの同期オブジェクトを取得します。</span><span class="sxs-lookup"><span data-stu-id="13b1b-117">Gets the synchronization object for the given instance.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>