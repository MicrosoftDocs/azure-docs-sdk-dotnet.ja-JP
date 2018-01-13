<Type Name="IMobileServiceClient" FullName="Microsoft.WindowsAzure.MobileServices.IMobileServiceClient">
  <TypeSignature Language="C#" Value="public interface IMobileServiceClient" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IMobileServiceClient" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient" />
  <TypeSignature Language="VB.NET" Value="Public Interface IMobileServiceClient" />
  <TypeSignature Language="F#" Value="type IMobileServiceClient = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7990d-101">ためのインターフェイス、<see cref="T:Microsoft.WindowsAzure.MobileServices.MobileServiceClient" />です。</span><span class="sxs-lookup"><span data-stu-id="7990d-101">Interface for the <see cref="T:Microsoft.WindowsAzure.MobileServices.MobileServiceClient" />.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AlternateLoginHost">
      <MemberSignature Language="C#" Value="public Uri AlternateLoginHost { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri AlternateLoginHost" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.AlternateLoginHost" />
      <MemberSignature Language="VB.NET" Value="Public Property AlternateLoginHost As Uri" />
      <MemberSignature Language="F#" Value="member this.AlternateLoginHost : Uri with get, set" Usage="Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.AlternateLoginHost" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7990d-102">ログインの代替ホストの URI</span><span class="sxs-lookup"><span data-stu-id="7990d-102">Alternate Host URI for login</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentUser">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.MobileServiceUser CurrentUser { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.MobileServices.MobileServiceUser CurrentUser" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.CurrentUser" />
      <MemberSignature Language="VB.NET" Value="Public Property CurrentUser As MobileServiceUser" />
      <MemberSignature Language="F#" Value="member this.CurrentUser : Microsoft.WindowsAzure.MobileServices.MobileServiceUser with get, set" Usage="Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.CurrentUser" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.MobileServiceUser</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7990d-103">現在では、MobileServiceClient.Login() 呼び出しは成功後に指定されたユーザーを認証します。</span><span class="sxs-lookup"><span data-stu-id="7990d-103">The current authenticated user provided after a successful call to MobileServiceClient.Login().</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventManager">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.Eventing.IMobileServiceEventManager EventManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.MobileServices.Eventing.IMobileServiceEventManager EventManager" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.EventManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EventManager As IMobileServiceEventManager" />
      <MemberSignature Language="F#" Value="member this.EventManager : Microsoft.WindowsAzure.MobileServices.Eventing.IMobileServiceEventManager" Usage="Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.EventManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Eventing.IMobileServiceEventManager</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7990d-104">イベント マネージャーを公開し、発行およびイベントを使用するモバイル サービスの種類で使用されるイベント ストリームを管理します。</span><span class="sxs-lookup"><span data-stu-id="7990d-104">The event manager that exposes and manages the event stream used by the mobile services types to publish and consume events.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSyncTable">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable GetSyncTable (string tableName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable GetSyncTable(string tableName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.GetSyncTable(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSyncTable (tableName As String) As IMobileServiceSyncTable" />
      <MemberSignature Language="F#" Value="abstract member GetSyncTable : string -&gt; Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable" Usage="iMobileServiceClient.GetSyncTable tableName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tableName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="tableName"><span data-ttu-id="7990d-105">テーブルの名前。</span><span class="sxs-lookup"><span data-stu-id="7990d-105">The name of the table.</span></span></param>
        <summary>
            <span data-ttu-id="7990d-106">返します、<see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable" />インスタンスで、ローカル テーブルの型指定されていないデータの操作を提供します。</span><span class="sxs-lookup"><span data-stu-id="7990d-106">Returns a <see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable" /> instance, which provides untyped data operations for a local table.</span></span>
            </summary>
        <returns><span data-ttu-id="7990d-107">テーブルです。</span><span class="sxs-lookup"><span data-stu-id="7990d-107">The table.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSyncTable&lt;T&gt;">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable&lt;T&gt; GetSyncTable&lt;T&gt; ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1&lt;!!T&gt; GetSyncTable&lt;T&gt;() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.GetSyncTable``1" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSyncTable(Of T) () As IMobileServiceSyncTable(Of T)" />
      <MemberSignature Language="F#" Value="abstract member GetSyncTable : unit -&gt; Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable&lt;'T&gt;" Usage="iMobileServiceClient.GetSyncTable " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters />
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="7990d-108">テーブル内のインスタンスの型。</span><span class="sxs-lookup"><span data-stu-id="7990d-108">The type of the instances in the table.</span></span>
            </typeparam>
        <summary>
            <span data-ttu-id="7990d-109">返します、<see cref="T:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1" />インスタンスで、ローカル テーブルの操作を厳密に型指定されたデータを提供します。</span><span class="sxs-lookup"><span data-stu-id="7990d-109">Returns a <see cref="T:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1" /> instance, which provides strongly typed data operations for a local table.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="7990d-110">テーブルです。</span><span class="sxs-lookup"><span data-stu-id="7990d-110">The table.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTable">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTable GetTable (string tableName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTable GetTable(string tableName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.GetTable(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetTable (tableName As String) As IMobileServiceTable" />
      <MemberSignature Language="F#" Value="abstract member GetTable : string -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTable" Usage="iMobileServiceClient.GetTable tableName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.IMobileServiceTable</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tableName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="tableName">
            <span data-ttu-id="7990d-111">テーブルの名前。</span><span class="sxs-lookup"><span data-stu-id="7990d-111">The name of the table.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7990d-112">返します、<see cref="T:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable" />インスタンス、そのテーブルの型指定されていないデータの操作を提供します。</span><span class="sxs-lookup"><span data-stu-id="7990d-112">Returns a <see cref="T:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable" /> instance, which provides untyped data operations for that table.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="7990d-113">テーブルです。</span><span class="sxs-lookup"><span data-stu-id="7990d-113">The table.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTable&lt;T&gt;">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTable&lt;T&gt; GetTable&lt;T&gt; ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1&lt;!!T&gt; GetTable&lt;T&gt;() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.GetTable``1" />
      <MemberSignature Language="VB.NET" Value="Public Function GetTable(Of T) () As IMobileServiceTable(Of T)" />
      <MemberSignature Language="F#" Value="abstract member GetTable : unit -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTable&lt;'T&gt;" Usage="iMobileServiceClient.GetTable " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.IMobileServiceTable&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters />
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="7990d-114">テーブル内のインスタンスの型。</span><span class="sxs-lookup"><span data-stu-id="7990d-114">The type of the instances in the table.</span></span>
            </typeparam>
        <summary>
            <span data-ttu-id="7990d-115">返します、<see cref="T:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1" />インスタンス、そのテーブルに対して操作を厳密に型指定されたデータを提供します。</span><span class="sxs-lookup"><span data-stu-id="7990d-115">Returns a <see cref="T:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1" /> instance, which provides strongly typed data operations for that table.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="7990d-116">テーブルです。</span><span class="sxs-lookup"><span data-stu-id="7990d-116">The table.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstallationId">
      <MemberSignature Language="C#" Value="public string InstallationId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InstallationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.InstallationId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InstallationId As String" />
      <MemberSignature Language="F#" Value="member this.InstallationId : string" Usage="Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.InstallationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7990d-117">アプリケーションのインストール id を返します。</span><span class="sxs-lookup"><span data-stu-id="7990d-117">Returns the application's installation id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeApiAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt; InvokeApiAsync (string apiName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Newtonsoft.Json.Linq.JToken&gt; InvokeApiAsync(string apiName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.InvokeApiAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member InvokeApiAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;" Usage="iMobileServiceClient.InvokeApiAsync (apiName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="apiName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="apiName"><span data-ttu-id="7990d-118">カスタム API の名前です。</span><span class="sxs-lookup"><span data-stu-id="7990d-118">The name of the custom API.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="7990d-119"><see cref="T:System.Threading.CancellationToken" />観察するトークン</span><span class="sxs-lookup"><span data-stu-id="7990d-119">The <see cref="T:System.Threading.CancellationToken" /> token to observe</span></span></param>
        <summary>
            <span data-ttu-id="7990d-120">HTTP POST を使用して、Microsoft Azure モバイル サービスのユーザー定義のカスタム API を呼び出します。</span><span class="sxs-lookup"><span data-stu-id="7990d-120">Invokes a user-defined custom API of a Microsoft Azure Mobile Service using an HTTP POST.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeApiAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt; InvokeApiAsync (string apiName, Newtonsoft.Json.Linq.JToken body, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Newtonsoft.Json.Linq.JToken&gt; InvokeApiAsync(string apiName, class Newtonsoft.Json.Linq.JToken body, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.InvokeApiAsync(System.String,Newtonsoft.Json.Linq.JToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member InvokeApiAsync : string * Newtonsoft.Json.Linq.JToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;" Usage="iMobileServiceClient.InvokeApiAsync (apiName, body, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="apiName" Type="System.String" />
        <Parameter Name="body" Type="Newtonsoft.Json.Linq.JToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="apiName"><span data-ttu-id="7990d-121">カスタム API の名前です。</span><span class="sxs-lookup"><span data-stu-id="7990d-121">The name of the custom API.</span></span></param>
        <param name="body"><span data-ttu-id="7990d-122">HTTP 本文として送信する値。</span><span class="sxs-lookup"><span data-stu-id="7990d-122">The value to be sent as the HTTP body.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="7990d-123"><see cref="T:System.Threading.CancellationToken" />観察するトークン</span><span class="sxs-lookup"><span data-stu-id="7990d-123">The <see cref="T:System.Threading.CancellationToken" /> token to observe</span></span></param>
        <summary>
            <span data-ttu-id="7990d-124">HTTP コンテンツの送信をサポートする HTTP POST を使用して、Microsoft Azure モバイル サービスのユーザー定義のカスタム API を呼び出します。</span><span class="sxs-lookup"><span data-stu-id="7990d-124">Invokes a user-defined custom API of a Microsoft Azure Mobile Service using an HTTP POST, with support for sending HTTP content.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeApiAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt; InvokeApiAsync (string apiName, System.Net.Http.HttpMethod method, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Newtonsoft.Json.Linq.JToken&gt; InvokeApiAsync(string apiName, class System.Net.Http.HttpMethod method, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.InvokeApiAsync(System.String,System.Net.Http.HttpMethod,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member InvokeApiAsync : string * System.Net.Http.HttpMethod * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;" Usage="iMobileServiceClient.InvokeApiAsync (apiName, method, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="apiName" Type="System.String" />
        <Parameter Name="method" Type="System.Net.Http.HttpMethod" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="apiName"><span data-ttu-id="7990d-125">カスタム API の名前です。</span><span class="sxs-lookup"><span data-stu-id="7990d-125">The name of the custom API.</span></span></param>
        <param name="method"><span data-ttu-id="7990d-126">HTTP メソッド。</span><span class="sxs-lookup"><span data-stu-id="7990d-126">The HTTP method.</span></span></param>
        <param name="parameters">
            <span data-ttu-id="7990d-127">ユーザー定義パラメーターと要求 URI クエリ文字列に含める値のディクショナリ。</span><span class="sxs-lookup"><span data-stu-id="7990d-127">A dictionary of user-defined parameters and values to include in the request URI query string.</span></span>
            </param>
        <param name="cancellationToken"><span data-ttu-id="7990d-128"><see cref="T:System.Threading.CancellationToken" />観察するトークン</span><span class="sxs-lookup"><span data-stu-id="7990d-128">The <see cref="T:System.Threading.CancellationToken" /> token to observe</span></span></param>
        <summary>
            <span data-ttu-id="7990d-129">指定された HTTP メソッドを使用して、Microsoft Azure モバイル サービスのユーザー定義のカスタム API を呼び出します。</span><span class="sxs-lookup"><span data-stu-id="7990d-129">Invokes a user-defined custom API of a Microsoft Azure Mobile Service using the specified HTTP Method.</span></span>
            <span data-ttu-id="7990d-130">追加のデータは、クエリ文字列に送信されます。</span><span class="sxs-lookup"><span data-stu-id="7990d-130">Additional data will sent to through the query string.</span></span>
            </summary>
        <returns><span data-ttu-id="7990d-131">カスタム api の呼び出しからの応答コンテンツ。</span><span class="sxs-lookup"><span data-stu-id="7990d-131">The response content from the custom api invocation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeApiAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt; InvokeApiAsync (string apiName, Newtonsoft.Json.Linq.JToken body, System.Net.Http.HttpMethod method, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Newtonsoft.Json.Linq.JToken&gt; InvokeApiAsync(string apiName, class Newtonsoft.Json.Linq.JToken body, class System.Net.Http.HttpMethod method, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.InvokeApiAsync(System.String,Newtonsoft.Json.Linq.JToken,System.Net.Http.HttpMethod,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member InvokeApiAsync : string * Newtonsoft.Json.Linq.JToken * System.Net.Http.HttpMethod * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;" Usage="iMobileServiceClient.InvokeApiAsync (apiName, body, method, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="apiName" Type="System.String" />
        <Parameter Name="body" Type="Newtonsoft.Json.Linq.JToken" />
        <Parameter Name="method" Type="System.Net.Http.HttpMethod" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="apiName"><span data-ttu-id="7990d-132">カスタム API の名前です。</span><span class="sxs-lookup"><span data-stu-id="7990d-132">The name of the custom API.</span></span></param>
        <param name="body"><span data-ttu-id="7990d-133">HTTP 本文として送信する値。</span><span class="sxs-lookup"><span data-stu-id="7990d-133">The value to be sent as the HTTP body.</span></span></param>
        <param name="method"><span data-ttu-id="7990d-134">HTTP メソッド。</span><span class="sxs-lookup"><span data-stu-id="7990d-134">The HTTP method.</span></span></param>
        <param name="parameters">
            <span data-ttu-id="7990d-135">ユーザー定義パラメーターと要求 URI クエリ文字列に含める値のディクショナリ。</span><span class="sxs-lookup"><span data-stu-id="7990d-135">A dictionary of user-defined parameters and values to include in the request URI query string.</span></span>
            </param>
        <param name="cancellationToken"><span data-ttu-id="7990d-136"><see cref="T:System.Threading.CancellationToken" />観察するトークン</span><span class="sxs-lookup"><span data-stu-id="7990d-136">The <see cref="T:System.Threading.CancellationToken" /> token to observe</span></span></param>
        <summary>
            <span data-ttu-id="7990d-137">指定された HTTP メソッドを使用して、Microsoft Azure モバイル サービスのユーザー定義のカスタム API を呼び出します。</span><span class="sxs-lookup"><span data-stu-id="7990d-137">Invokes a user-defined custom API of a Microsoft Azure Mobile Service using the specified HTTP method.</span></span>
            <span data-ttu-id="7990d-138">追加のデータは、HTTP コンテンツまたはクエリ文字列が送信できます。</span><span class="sxs-lookup"><span data-stu-id="7990d-138">Additional data can be sent though the HTTP content or the query string.</span></span>
            </summary>
        <returns><span data-ttu-id="7990d-139">カスタム api の呼び出しからの応答コンテンツ。</span><span class="sxs-lookup"><span data-stu-id="7990d-139">The response content from the custom api invocation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeApiAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Net.Http.HttpResponseMessage&gt; InvokeApiAsync (string apiName, System.Net.Http.HttpContent content, System.Net.Http.HttpMethod method, System.Collections.Generic.IDictionary&lt;string,string&gt; requestHeaders, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Net.Http.HttpResponseMessage&gt; InvokeApiAsync(string apiName, class System.Net.Http.HttpContent content, class System.Net.Http.HttpMethod method, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; requestHeaders, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.InvokeApiAsync(System.String,System.Net.Http.HttpContent,System.Net.Http.HttpMethod,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member InvokeApiAsync : string * System.Net.Http.HttpContent * System.Net.Http.HttpMethod * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Net.Http.HttpResponseMessage&gt;" Usage="iMobileServiceClient.InvokeApiAsync (apiName, content, method, requestHeaders, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Net.Http.HttpResponseMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="apiName" Type="System.String" />
        <Parameter Name="content" Type="System.Net.Http.HttpContent" />
        <Parameter Name="method" Type="System.Net.Http.HttpMethod" />
        <Parameter Name="requestHeaders" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="apiName"><span data-ttu-id="7990d-140">カスタム API の名前です。</span><span class="sxs-lookup"><span data-stu-id="7990d-140">The name of the custom API.</span></span></param>
        <param name="content"><span data-ttu-id="7990d-141">HTTP コンテンツ。</span><span class="sxs-lookup"><span data-stu-id="7990d-141">The HTTP content.</span></span></param>
        <param name="method"><span data-ttu-id="7990d-142">HTTP メソッド。</span><span class="sxs-lookup"><span data-stu-id="7990d-142">The HTTP method.</span></span></param>
        <param name="requestHeaders">
            <span data-ttu-id="7990d-143">HttpRequest に含めるユーザー定義のヘッダーのディクショナリ。</span><span class="sxs-lookup"><span data-stu-id="7990d-143">A dictionary of user-defined headers to include in the HttpRequest.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7990d-144">ユーザー定義パラメーターと要求 URI クエリ文字列に含める値のディクショナリ。</span><span class="sxs-lookup"><span data-stu-id="7990d-144">A dictionary of user-defined parameters and values to include in the request URI query string.</span></span>
            </param>
        <param name="cancellationToken"><span data-ttu-id="7990d-145"><see cref="T:System.Threading.CancellationToken" />観察するトークン</span><span class="sxs-lookup"><span data-stu-id="7990d-145">The <see cref="T:System.Threading.CancellationToken" /> token to observe</span></span></param>
        <summary>
            <span data-ttu-id="7990d-146">指定された http メソッドを使用して、Microsoft Azure モバイル サービスのユーザー定義のカスタム API を呼び出します。</span><span class="sxs-lookup"><span data-stu-id="7990d-146">Invokes a user-defined custom API of a Microsoft Azure Mobile Service using the specified HttpMethod.</span></span>
            <span data-ttu-id="7990d-147">追加のデータは、HTTP コンテンツまたはクエリ文字列が送信できます。</span><span class="sxs-lookup"><span data-stu-id="7990d-147">Additional data can be sent though the HTTP content or the query string.</span></span> 
            </summary>
        <returns><span data-ttu-id="7990d-148">カスタム api の呼び出しからの HTTP 応答。</span><span class="sxs-lookup"><span data-stu-id="7990d-148">The HTTP Response from the custom api invocation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeApiAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; InvokeApiAsync&lt;T&gt; (string apiName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; InvokeApiAsync&lt;T&gt;(string apiName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.InvokeApiAsync``1(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member InvokeApiAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'T&gt;" Usage="iMobileServiceClient.InvokeApiAsync (apiName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="apiName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="7990d-149">Microsoft Azure モバイル サービスから返されるインスタンスの型。</span><span class="sxs-lookup"><span data-stu-id="7990d-149">The type of instance returned from the Microsoft Azure Mobile Service.</span></span></typeparam>
        <param name="apiName"><span data-ttu-id="7990d-150">カスタム API の名前です。</span><span class="sxs-lookup"><span data-stu-id="7990d-150">The name of the custom API.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="7990d-151"><see cref="T:System.Threading.CancellationToken" />観察するトークン</span><span class="sxs-lookup"><span data-stu-id="7990d-151">The <see cref="T:System.Threading.CancellationToken" /> token to observe</span></span></param>
        <summary>
            <span data-ttu-id="7990d-152">HTTP POST を使用して、Microsoft Azure モバイル サービスのユーザー定義のカスタム API を呼び出します。</span><span class="sxs-lookup"><span data-stu-id="7990d-152">Invokes a user-defined custom API of a Microsoft Azure Mobile Service using an HTTP POST.</span></span>
            </summary>
        <returns><span data-ttu-id="7990d-153">カスタム api の呼び出しからの応答コンテンツ。</span><span class="sxs-lookup"><span data-stu-id="7990d-153">The response content from the custom api invocation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeApiAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; InvokeApiAsync&lt;T&gt; (string apiName, System.Net.Http.HttpMethod method, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; InvokeApiAsync&lt;T&gt;(string apiName, class System.Net.Http.HttpMethod method, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.InvokeApiAsync``1(System.String,System.Net.Http.HttpMethod,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member InvokeApiAsync : string * System.Net.Http.HttpMethod * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'T&gt;" Usage="iMobileServiceClient.InvokeApiAsync (apiName, method, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="apiName" Type="System.String" />
        <Parameter Name="method" Type="System.Net.Http.HttpMethod" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="7990d-154">Microsoft Azure モバイル サービスに送信されるインスタンスの型。</span><span class="sxs-lookup"><span data-stu-id="7990d-154">The type of instance sent to the Microsoft Azure Mobile Service.</span></span></typeparam>
        <param name="apiName"><span data-ttu-id="7990d-155">カスタム API の名前です。</span><span class="sxs-lookup"><span data-stu-id="7990d-155">The name of the custom API.</span></span></param>
        <param name="method"><span data-ttu-id="7990d-156">HTTP メソッド。</span><span class="sxs-lookup"><span data-stu-id="7990d-156">The HTTP method.</span></span></param>
        <param name="parameters">
            <span data-ttu-id="7990d-157">ユーザー定義パラメーターと要求 URI クエリ文字列に含める値のディクショナリ。</span><span class="sxs-lookup"><span data-stu-id="7990d-157">A dictionary of user-defined parameters and values to include in the request URI query string.</span></span>
            </param>
        <param name="cancellationToken"><span data-ttu-id="7990d-158"><see cref="T:System.Threading.CancellationToken" />観察するトークン</span><span class="sxs-lookup"><span data-stu-id="7990d-158">The <see cref="T:System.Threading.CancellationToken" /> token to observe</span></span></param>
        <summary>
            <span data-ttu-id="7990d-159">指定された HTTP メソッドを使用して、Microsoft Azure モバイル サービスのユーザー定義のカスタム API を呼び出します。</span><span class="sxs-lookup"><span data-stu-id="7990d-159">Invokes a user-defined custom API of a Microsoft Azure Mobile Service using the specified HTTP Method.</span></span>
            <span data-ttu-id="7990d-160">クエリ文字列を使用して、追加のデータを渡すことができます。</span><span class="sxs-lookup"><span data-stu-id="7990d-160">Additional data can be passed using the query string.</span></span>
            </summary>
        <returns><span data-ttu-id="7990d-161">カスタム api の呼び出しからの応答コンテンツ。</span><span class="sxs-lookup"><span data-stu-id="7990d-161">The response content from the custom api invocation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeApiAsync&lt;T,U&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;U&gt; InvokeApiAsync&lt;T,U&gt; (string apiName, T body, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!U&gt; InvokeApiAsync&lt;T, U&gt;(string apiName, !!T body, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.InvokeApiAsync``2(System.String,``0,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member InvokeApiAsync : string * 'T * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'U&gt;" Usage="iMobileServiceClient.InvokeApiAsync (apiName, body, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;U&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
        <TypeParameter Name="U" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="apiName" Type="System.String" />
        <Parameter Name="body" Type="T" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="7990d-162">Microsoft Azure モバイル サービスに送信されるインスタンスの型。</span><span class="sxs-lookup"><span data-stu-id="7990d-162">The type of instance sent to the Microsoft Azure Mobile Service.</span></span></typeparam>
        <typeparam name="U"><span data-ttu-id="7990d-163">Microsoft Azure モバイル サービスから返されるインスタンスの型。</span><span class="sxs-lookup"><span data-stu-id="7990d-163">The type of instance returned from the Microsoft Azure Mobile Service.</span></span></typeparam>
        <param name="apiName"><span data-ttu-id="7990d-164">カスタム API の名前です。</span><span class="sxs-lookup"><span data-stu-id="7990d-164">The name of the custom API.</span></span></param>
        <param name="body"><span data-ttu-id="7990d-165">HTTP 本文として送信する値。</span><span class="sxs-lookup"><span data-stu-id="7990d-165">The value to be sent as the HTTP body.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="7990d-166"><see cref="T:System.Threading.CancellationToken" />観察するトークン</span><span class="sxs-lookup"><span data-stu-id="7990d-166">The <see cref="T:System.Threading.CancellationToken" /> token to observe</span></span></param>
        <summary>
            <span data-ttu-id="7990d-167">HTTP コンテンツを送信するためのサポートが HTTP POST を使用して、Microsoft Azure モバイル サービスのユーザー定義のカスタム API を呼び出します。</span><span class="sxs-lookup"><span data-stu-id="7990d-167">Invokes a user-defined custom API of a Microsoft Azure Mobile Service using an HTTP POST with support for sending HTTP content.</span></span>
            </summary>
        <returns><span data-ttu-id="7990d-168">カスタム api の呼び出しからの応答コンテンツ。</span><span class="sxs-lookup"><span data-stu-id="7990d-168">The response content from the custom api invocation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeApiAsync&lt;T,U&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;U&gt; InvokeApiAsync&lt;T,U&gt; (string apiName, T body, System.Net.Http.HttpMethod method, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!U&gt; InvokeApiAsync&lt;T, U&gt;(string apiName, !!T body, class System.Net.Http.HttpMethod method, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.InvokeApiAsync``2(System.String,``0,System.Net.Http.HttpMethod,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member InvokeApiAsync : string * 'T * System.Net.Http.HttpMethod * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'U&gt;" Usage="iMobileServiceClient.InvokeApiAsync (apiName, body, method, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;U&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
        <TypeParameter Name="U" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="apiName" Type="System.String" />
        <Parameter Name="body" Type="T" />
        <Parameter Name="method" Type="System.Net.Http.HttpMethod" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="7990d-169">Microsoft Azure モバイル サービスに送信されるインスタンスの型。</span><span class="sxs-lookup"><span data-stu-id="7990d-169">The type of instance sent to the Microsoft Azure Mobile Service.</span></span></typeparam>
        <typeparam name="U"><span data-ttu-id="7990d-170">Microsoft Azure モバイル サービスから返されるインスタンスの型。</span><span class="sxs-lookup"><span data-stu-id="7990d-170">The type of instance returned from the Microsoft Azure Mobile Service.</span></span></typeparam>
        <param name="apiName"><span data-ttu-id="7990d-171">カスタム API の名前です。</span><span class="sxs-lookup"><span data-stu-id="7990d-171">The name of the custom API.</span></span></param>
        <param name="body"><span data-ttu-id="7990d-172">HTTP 本文として送信する値。</span><span class="sxs-lookup"><span data-stu-id="7990d-172">The value to be sent as the HTTP body.</span></span></param>
        <param name="method"><span data-ttu-id="7990d-173">HTTP メソッド。</span><span class="sxs-lookup"><span data-stu-id="7990d-173">The HTTP method.</span></span></param>
        <param name="parameters">
            <span data-ttu-id="7990d-174">ユーザー定義パラメーターと要求 URI クエリ文字列に含める値のディクショナリ。</span><span class="sxs-lookup"><span data-stu-id="7990d-174">A dictionary of user-defined parameters and values to include in the request URI query string.</span></span>
            </param>
        <param name="cancellationToken"><span data-ttu-id="7990d-175"><see cref="T:System.Threading.CancellationToken" />観察するトークン</span><span class="sxs-lookup"><span data-stu-id="7990d-175">The <see cref="T:System.Threading.CancellationToken" /> token to observe</span></span></param>
        <summary>
            <span data-ttu-id="7990d-176">指定された HTTP メソッドを使用して、Microsoft Azure モバイル サービスのユーザー定義のカスタム API を呼び出します。</span><span class="sxs-lookup"><span data-stu-id="7990d-176">Invokes a user-defined custom API of a Microsoft Azure Mobile Service using the specified HTTP Method.</span></span>
            <span data-ttu-id="7990d-177">追加のデータは、HTTP コンテンツまたはクエリ文字列が送信できます。</span><span class="sxs-lookup"><span data-stu-id="7990d-177">Additional data can be sent though the HTTP content or the query string.</span></span>
            </summary>
        <returns><span data-ttu-id="7990d-178">カスタム api の呼び出しからの応答コンテンツ。</span><span class="sxs-lookup"><span data-stu-id="7990d-178">The response content from the custom api invocation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoginAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MobileServices.MobileServiceUser&gt; LoginAsync (Microsoft.WindowsAzure.MobileServices.MobileServiceAuthenticationProvider provider, Newtonsoft.Json.Linq.JObject token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.MobileServices.MobileServiceUser&gt; LoginAsync(valuetype Microsoft.WindowsAzure.MobileServices.MobileServiceAuthenticationProvider provider, class Newtonsoft.Json.Linq.JObject token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.LoginAsync(Microsoft.WindowsAzure.MobileServices.MobileServiceAuthenticationProvider,Newtonsoft.Json.Linq.JObject)" />
      <MemberSignature Language="VB.NET" Value="Public Function LoginAsync (provider As MobileServiceAuthenticationProvider, token As JObject) As Task(Of MobileServiceUser)" />
      <MemberSignature Language="F#" Value="abstract member LoginAsync : Microsoft.WindowsAzure.MobileServices.MobileServiceAuthenticationProvider * Newtonsoft.Json.Linq.JObject -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MobileServices.MobileServiceUser&gt;" Usage="iMobileServiceClient.LoginAsync (provider, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MobileServices.MobileServiceUser&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="provider" Type="Microsoft.WindowsAzure.MobileServices.MobileServiceAuthenticationProvider" />
        <Parameter Name="token" Type="Newtonsoft.Json.Linq.JObject" />
      </Parameters>
      <Docs>
        <param name="provider">
            <span data-ttu-id="7990d-179">使用する認証プロバイダーです。</span><span class="sxs-lookup"><span data-stu-id="7990d-179">Authentication provider to use.</span></span>
            </param>
        <param name="token">
            <span data-ttu-id="7990d-180">ログインに使用する既存の OAuth トークンとプロバイダー固有のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="7990d-180">Provider specific object with existing OAuth token to log in with.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7990d-181">プロバイダーとトークンのオブジェクトで、Windows Azure モバイル サービスにユーザーを記録します。</span><span class="sxs-lookup"><span data-stu-id="7990d-181">Logs a user into a Windows Azure Mobile Service with the provider and a token object.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="7990d-182">ユーザーが認証を終了するとタスクが完了します。</span><span class="sxs-lookup"><span data-stu-id="7990d-182">Task that will complete when the user has finished authentication.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="7990d-183">トークンのオブジェクトは、特定のプロバイダーに応じて書式設定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="7990d-183">The token object needs to be formatted depending on the specific provider.</span></span> <span data-ttu-id="7990d-184">これらは、プロバイダーに基づく形式のいくつかの例: <list type="bullet"> <item> <term>MicrosoftAccount</term> <description> <code>{"authenticationToken":"&lt;the_authentication_token&gt;"}</code> </description> </item> <item> <term>Facebook</term><description><code>{"access_token":"&lt;the_access_token&gt;"}</code></description></item><item><term>Google</term><description><code>{"access_token":"&lt;the_access_token&gt;"}</code></description></item></list></span><span class="sxs-lookup"><span data-stu-id="7990d-184">These are some examples of formats based on the providers: <list type="bullet"><item><term>MicrosoftAccount</term><description><code>{"authenticationToken":"&lt;the_authentication_token&gt;"}</code></description></item><item><term>Facebook</term><description><code>{"access_token":"&lt;the_access_token&gt;"}</code></description></item><item><term>Google</term><description><code>{"access_token":"&lt;the_access_token&gt;"}</code></description></item></list></span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="LoginAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MobileServices.MobileServiceUser&gt; LoginAsync (string provider, Newtonsoft.Json.Linq.JObject token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.MobileServices.MobileServiceUser&gt; LoginAsync(string provider, class Newtonsoft.Json.Linq.JObject token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.LoginAsync(System.String,Newtonsoft.Json.Linq.JObject)" />
      <MemberSignature Language="VB.NET" Value="Public Function LoginAsync (provider As String, token As JObject) As Task(Of MobileServiceUser)" />
      <MemberSignature Language="F#" Value="abstract member LoginAsync : string * Newtonsoft.Json.Linq.JObject -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MobileServices.MobileServiceUser&gt;" Usage="iMobileServiceClient.LoginAsync (provider, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MobileServices.MobileServiceUser&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="provider" Type="System.String" />
        <Parameter Name="token" Type="Newtonsoft.Json.Linq.JObject" />
      </Parameters>
      <Docs>
        <param name="provider">
            <span data-ttu-id="7990d-185">使用する認証プロバイダーです。</span><span class="sxs-lookup"><span data-stu-id="7990d-185">Authentication provider to use.</span></span>
            </param>
        <param name="token">
            <span data-ttu-id="7990d-186">ログインに使用する既存の OAuth トークンとプロバイダー固有のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="7990d-186">Provider specific object with existing OAuth token to log in with.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7990d-187">プロバイダーとトークンのオブジェクトで、Microsoft Azure モバイル サービスにユーザーを記録します。</span><span class="sxs-lookup"><span data-stu-id="7990d-187">Logs a user into a Microsoft Azure Mobile Service with the provider and a token object.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="7990d-188">ユーザーが認証を終了するとタスクが完了します。</span><span class="sxs-lookup"><span data-stu-id="7990d-188">Task that will complete when the user has finished authentication.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="7990d-189">トークンのオブジェクトは、特定のプロバイダーに応じて書式設定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="7990d-189">The token object needs to be formatted depending on the specific provider.</span></span> <span data-ttu-id="7990d-190">これらは、プロバイダーに基づく形式のいくつかの例: <list type="bullet"> <item> <term>MicrosoftAccount</term> <description> <code>{"authenticationToken":"&lt;the_authentication_token&gt;"}</code> </description> </item> <item> <term>Facebook</term><description><code>{"access_token":"&lt;the_access_token&gt;"}</code></description></item><item><term>Google</term><description><code>{"access_token":"&lt;the_access_token&gt;"}</code></description></item></list></span><span class="sxs-lookup"><span data-stu-id="7990d-190">These are some examples of formats based on the providers: <list type="bullet"><item><term>MicrosoftAccount</term><description><code>{"authenticationToken":"&lt;the_authentication_token&gt;"}</code></description></item><item><term>Facebook</term><description><code>{"access_token":"&lt;the_access_token&gt;"}</code></description></item><item><term>Google</term><description><code>{"access_token":"&lt;the_access_token&gt;"}</code></description></item></list></span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="LoginUriPrefix">
      <MemberSignature Language="C#" Value="public string LoginUriPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LoginUriPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.LoginUriPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property LoginUriPrefix As String" />
      <MemberSignature Language="F#" Value="member this.LoginUriPrefix : string with get, set" Usage="Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.LoginUriPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7990d-191">ログインのエンドポイントのプレフィックス。</span><span class="sxs-lookup"><span data-stu-id="7990d-191">Prefix for login endpoints.</span></span> <span data-ttu-id="7990d-192">既定値を/.auth/login に設定されていない場合</span><span class="sxs-lookup"><span data-stu-id="7990d-192">If not set defaults to /.auth/login</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LogoutAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task LogoutAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task LogoutAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.LogoutAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function LogoutAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member LogoutAsync : unit -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceClient.LogoutAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7990d-193">ユーザーをログアウトします。</span><span class="sxs-lookup"><span data-stu-id="7990d-193">Log a user out.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MobileAppUri">
      <MemberSignature Language="C#" Value="public Uri MobileAppUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri MobileAppUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.MobileAppUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MobileAppUri As Uri" />
      <MemberSignature Language="F#" Value="member this.MobileAppUri : Uri" Usage="Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.MobileAppUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7990d-194">Microsoft Azure のモバイル アプリの絶対 URI です。</span><span class="sxs-lookup"><span data-stu-id="7990d-194">Absolute URI of the Microsoft Azure Mobile App.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshUserAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MobileServices.MobileServiceUser&gt; RefreshUserAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.MobileServices.MobileServiceUser&gt; RefreshUserAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.RefreshUserAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function RefreshUserAsync () As Task(Of MobileServiceUser)" />
      <MemberSignature Language="F#" Value="abstract member RefreshUserAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MobileServices.MobileServiceUser&gt;" Usage="iMobileServiceClient.RefreshUserAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MobileServices.MobileServiceUser&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7990d-195">ログインしたユーザーの id プロバイダーにアクセス トークンを更新します。</span><span class="sxs-lookup"><span data-stu-id="7990d-195">Refreshes access token with the identity provider for the logged in user.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="7990d-196">ユーザーがアクセス トークンを更新し終えたときに完了するタスク</span><span class="sxs-lookup"><span data-stu-id="7990d-196">Task that will complete when the user has finished refreshing access token</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerializerSettings">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.MobileServiceJsonSerializerSettings SerializerSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.MobileServices.MobileServiceJsonSerializerSettings SerializerSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.SerializerSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property SerializerSettings As MobileServiceJsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.SerializerSettings : Microsoft.WindowsAzure.MobileServices.MobileServiceJsonSerializerSettings with get, set" Usage="Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.SerializerSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.MobileServiceJsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7990d-197">取得または設定をシリアル化に使用します。</span><span class="sxs-lookup"><span data-stu-id="7990d-197">Gets or sets the settings used for serialization.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SyncContext">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext SyncContext { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext SyncContext" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.SyncContext" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SyncContext As IMobileServiceSyncContext" />
      <MemberSignature Language="F#" Value="member this.SyncContext : Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext" Usage="Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.SyncContext" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7990d-198"><see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext" /> インスタンスを返します。</span><span class="sxs-lookup"><span data-stu-id="7990d-198">Returns a <see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext" /> instance.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>