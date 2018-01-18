<Type Name="IWithAuthenticationProvider&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAuthenticationProvider&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithAuthenticationProvider&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAuthenticationProvider`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAuthenticationProvider`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAuthenticationProvider(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithAuthenticationProvider&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="ab997-101">この定義をアタッチした後に戻るに親の定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="ab997-101">The stage of the parent definition to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="ab997-102">指定するプロバイダーの詳細な情報を許可する、web アプリの認証定義します。</span><span class="sxs-lookup"><span data-stu-id="ab997-102">A web app authentication definition allowing detailed provider information to be specified.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithActiveDirectory">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAttach&lt;ParentT&gt; WithActiveDirectory (string clientId, string issuerUrl);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAttach`1&lt;!ParentT&gt; WithActiveDirectory(string clientId, string issuerUrl) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAuthenticationProvider`1.WithActiveDirectory(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithActiveDirectory (clientId As String, issuerUrl As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithActiveDirectory : string * string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithAuthenticationProvider.WithActiveDirectory (clientId, issuerUrl)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="issuerUrl" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="clientId"><span data-ttu-id="ab997-103">AAD アプリのクライアントの id。</span><span class="sxs-lookup"><span data-stu-id="ab997-103">The AAD app's client ID.</span></span></param>
        <param name="issuerUrl"><span data-ttu-id="ab997-104">Https://sts.windows.net/(テナント Id) の形式でトークン発行者の URL です。</span><span class="sxs-lookup"><span data-stu-id="ab997-104">The token issuer URL in the format of https://sts.windows.net/(tenantId).</span></span></param>
        <summary>
            <span data-ttu-id="ab997-105">Active Directory およびそのクライアント ID と発行者の URL であるプロバイダーを指定します。</span><span class="sxs-lookup"><span data-stu-id="ab997-105">Specifies the provider to be Active Directory and its client ID and issuer URL.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="ab997-106">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="ab997-106">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithFacebook">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAttach&lt;ParentT&gt; WithFacebook (string appId, string appSecret);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAttach`1&lt;!ParentT&gt; WithFacebook(string appId, string appSecret) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAuthenticationProvider`1.WithFacebook(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithFacebook (appId As String, appSecret As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithFacebook : string * string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithAuthenticationProvider.WithFacebook (appId, appSecret)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appId" Type="System.String" />
        <Parameter Name="appSecret" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="appId"><span data-ttu-id="ab997-107">Facebook アプリ id。</span><span class="sxs-lookup"><span data-stu-id="ab997-107">The Facebook app ID.</span></span></param>
        <param name="appSecret"><span data-ttu-id="ab997-108">Facebook アプリのシークレット。</span><span class="sxs-lookup"><span data-stu-id="ab997-108">The Facebook app secret.</span></span></param>
        <summary>
            <span data-ttu-id="ab997-109">Facebook アプリ ID およびそのアプリのシークレットをあるプロバイダーを指定します。</span><span class="sxs-lookup"><span data-stu-id="ab997-109">Specifies the provider to be Facebook and its app ID and app secret.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="ab997-110">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="ab997-110">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithGoogle">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAttach&lt;ParentT&gt; WithGoogle (string clientId, string clientSecret);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAttach`1&lt;!ParentT&gt; WithGoogle(string clientId, string clientSecret) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAuthenticationProvider`1.WithGoogle(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithGoogle (clientId As String, clientSecret As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithGoogle : string * string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithAuthenticationProvider.WithGoogle (clientId, clientSecret)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="clientSecret" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="clientId"><span data-ttu-id="ab997-111">Google のアプリのクライアント ID</span><span class="sxs-lookup"><span data-stu-id="ab997-111">The Google app's client ID.</span></span></param>
        <param name="clientSecret"><span data-ttu-id="ab997-112">Google のアプリのクライアント シークレット。</span><span class="sxs-lookup"><span data-stu-id="ab997-112">The Google app's client secret.</span></span></param>
        <summary>
            <span data-ttu-id="ab997-113">Google、クライアント ID、およびクライアント シークレットをあるプロバイダーを指定します。</span><span class="sxs-lookup"><span data-stu-id="ab997-113">Specifies the provider to be Google and its client ID and client secret.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="ab997-114">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="ab997-114">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithMicrosoft">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAttach&lt;ParentT&gt; WithMicrosoft (string clientId, string clientSecret);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAttach`1&lt;!ParentT&gt; WithMicrosoft(string clientId, string clientSecret) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAuthenticationProvider`1.WithMicrosoft(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithMicrosoft (clientId As String, clientSecret As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithMicrosoft : string * string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithAuthenticationProvider.WithMicrosoft (clientId, clientSecret)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="clientSecret" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="clientId"><span data-ttu-id="ab997-115">Microsoft アプリのクライアントの id。</span><span class="sxs-lookup"><span data-stu-id="ab997-115">The Microsoft app's client ID.</span></span></param>
        <param name="clientSecret"><span data-ttu-id="ab997-116">Microsoft アプリのクライアント シークレット。</span><span class="sxs-lookup"><span data-stu-id="ab997-116">The Microsoft app's client secret.</span></span></param>
        <summary>
            <span data-ttu-id="ab997-117">Microsoft およびそのクライアント ID およびクライアント シークレットをあるプロバイダーを指定します。</span><span class="sxs-lookup"><span data-stu-id="ab997-117">Specifies the provider to be Microsoft and its client ID and client secret.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="ab997-118">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="ab997-118">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithTwitter">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAttach&lt;ParentT&gt; WithTwitter (string apiKey, string apiSecret);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAttach`1&lt;!ParentT&gt; WithTwitter(string apiKey, string apiSecret) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAuthenticationProvider`1.WithTwitter(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithTwitter (apiKey As String, apiSecret As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithTwitter : string * string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithAuthenticationProvider.WithTwitter (apiKey, apiSecret)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="apiKey" Type="System.String" />
        <Parameter Name="apiSecret" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="apiKey"><span data-ttu-id="ab997-119">Twitter アプリの API キー。</span><span class="sxs-lookup"><span data-stu-id="ab997-119">The Twitter app's API key.</span></span></param>
        <param name="apiSecret"><span data-ttu-id="ab997-120">Twitter アプリの API のシークレット。</span><span class="sxs-lookup"><span data-stu-id="ab997-120">The Twitter app's API secret.</span></span></param>
        <summary>
            <span data-ttu-id="ab997-121">Twitter であるプロバイダーを指定します、API キー、および API シークレット。</span><span class="sxs-lookup"><span data-stu-id="ab997-121">Specifies the provider to be Twitter and its API key and API secret.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="ab997-122">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="ab997-122">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>