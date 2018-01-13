<Type Name="ServiceBusConnectionStringBuilder" FullName="Microsoft.ServiceBus.ServiceBusConnectionStringBuilder">
  <TypeSignature Language="C#" Value="public class ServiceBusConnectionStringBuilder" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServiceBusConnectionStringBuilder extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceBusConnectionStringBuilder" />
  <TypeSignature Language="F#" Value="type ServiceBusConnectionStringBuilder = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="d8e76-101">作成し、接続文字列の内容を管理します。</span><span class="sxs-lookup"><span data-stu-id="d8e76-101">Creates and manages the contents of connection strings.</span></span> <span data-ttu-id="d8e76-102">このクラスは、クライアントのメッセージング エンティティを作成するための接続文字列を構築するために使用できます。</span><span class="sxs-lookup"><span data-stu-id="d8e76-102">You can use this class to construct a connection string for creating client messaging entities.</span></span> <span data-ttu-id="d8e76-103">既存の接続文字列で基本的な検証を実行するも使用できます。</span><span class="sxs-lookup"><span data-stu-id="d8e76-103">It can also be used to perform basic validation on an existing connection string.</span></span></summary>
    <remarks>To be added.</remarks>
    <code>
                <span data-ttu-id="d8e76-104">次のサンプル コードには、既存//接続文字列を Amqp を使用するトランスポートの種類の変更は、//フォーム var ビルダーの文字列で、新しい接続文字列を返す新しい ServiceBusConnectionStringBuilder(connectionString); を =ビルダー。TransportType TransportType.Amqp; を =Console.WriteLine (ビルダー。ToString()) です。</span><span class="sxs-lookup"><span data-stu-id="d8e76-104">// The following sample code takes an existing // connection string, change the transport type to use Amqp, // and return the new connection string in string form var bulider = new ServiceBusConnectionStringBuilder(connectionString); bulider.TransportType = TransportType.Amqp; Console.WriteLine(bulider.ToString());</span></span>
                </code>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceBusConnectionStringBuilder ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="d8e76-105"><see cref="T:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d8e76-105">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceBusConnectionStringBuilder (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (connectionString As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.ServiceBusConnectionStringBuilder : string -&gt; Microsoft.ServiceBus.ServiceBusConnectionStringBuilder" Usage="new Microsoft.ServiceBus.ServiceBusConnectionStringBuilder connectionString" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="d8e76-106">接続文字列、Azure 管理ポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="d8e76-106">The connection string, which you can obtain from the Azure Management Portal.</span></span></param>
        <summary><span data-ttu-id="d8e76-107">新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder" />指定した既存の接続文字列を持つクラス。</span><span class="sxs-lookup"><span data-stu-id="d8e76-107">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder" /> class with a specified existing connection string.</span></span></summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Configuration.ConfigurationErrorsException"><span data-ttu-id="d8e76-108">接続文字列にエンドポイントがない場合にスローします。接続文字列には、トークン プロバイダーを作成するための十分な情報はありません。</span><span class="sxs-lookup"><span data-stu-id="d8e76-108">Throws if The connection string is missing endpoints.The connection string does not have enough information to form a token provider.</span></span> <span data-ttu-id="d8e76-109">たとえば、SasIssuer 名が SasIssuer キーではないを指定した場合に発生します。<see cref="P:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.OperationTimeout" />値は有効ではありません<see cref="T:System.TimeSpan" />形式です。<see cref="P:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.RuntimePort" />または<see cref="P:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.ManagementPort" />値は整数形式ではありません。</span><span class="sxs-lookup"><span data-stu-id="d8e76-109">For example, this can happen if you supplied a SasIssuer name but not a SasIssuer key.The <see cref="P:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.OperationTimeout" /> value is not in a valid <see cref="T:System.TimeSpan" /> format.The <see cref="P:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.RuntimePort" /> or <see cref="P:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.ManagementPort" /> values are not in an integer format.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CreateUsingOAuthCredential">
      <MemberSignature Language="C#" Value="public static string CreateUsingOAuthCredential (System.Collections.Generic.IEnumerable&lt;Uri&gt; endpoints, System.Collections.Generic.IEnumerable&lt;Uri&gt; stsEndpoints, int runtimePort, int managementPort, string domain, string user, System.Security.SecureString password);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string CreateUsingOAuthCredential(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; endpoints, class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; stsEndpoints, int32 runtimePort, int32 managementPort, string domain, string user, class System.Security.SecureString password) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.CreateUsingOAuthCredential(System.Collections.Generic.IEnumerable{System.Uri},System.Collections.Generic.IEnumerable{System.Uri},System.Int32,System.Int32,System.String,System.String,System.Security.SecureString)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateUsingOAuthCredential (endpoints As IEnumerable(Of Uri), stsEndpoints As IEnumerable(Of Uri), runtimePort As Integer, managementPort As Integer, domain As String, user As String, password As SecureString) As String" />
      <MemberSignature Language="F#" Value="static member CreateUsingOAuthCredential : seq&lt;Uri&gt; * seq&lt;Uri&gt; * int * int * string * string * System.Security.SecureString -&gt; string" Usage="Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.CreateUsingOAuthCredential (endpoints, stsEndpoints, runtimePort, managementPort, domain, user, password)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpoints" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="stsEndpoints" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="runtimePort" Type="System.Int32" />
        <Parameter Name="managementPort" Type="System.Int32" />
        <Parameter Name="domain" Type="System.String" />
        <Parameter Name="user" Type="System.String" />
        <Parameter Name="password" Type="System.Security.SecureString" />
      </Parameters>
      <Docs>
        <param name="endpoints"><span data-ttu-id="d8e76-110">エンドポイントのセット。</span><span class="sxs-lookup"><span data-stu-id="d8e76-110">The set of endpoints.</span></span></param>
        <param name="stsEndpoints"><span data-ttu-id="d8e76-111">セキュリティ トークン サービス エンドポイントのセット。</span><span class="sxs-lookup"><span data-stu-id="d8e76-111">The set of security token service endpoints.</span></span></param>
        <param name="runtimePort"><span data-ttu-id="d8e76-112">ランタイム ポートです。</span><span class="sxs-lookup"><span data-stu-id="d8e76-112">The runtime port.</span></span></param>
        <param name="managementPort"><span data-ttu-id="d8e76-113">管理ポートです。</span><span class="sxs-lookup"><span data-stu-id="d8e76-113">The management port.</span></span></param>
        <param name="domain"><span data-ttu-id="d8e76-114">接続を確立するドメインです。</span><span class="sxs-lookup"><span data-stu-id="d8e76-114">The domain where the connection will be established.</span></span></param>
        <param name="user"><span data-ttu-id="d8e76-115">認証ユーザー。</span><span class="sxs-lookup"><span data-stu-id="d8e76-115">The authentication user.</span></span></param>
        <param name="password"><span data-ttu-id="d8e76-116">認証のパスワード。</span><span class="sxs-lookup"><span data-stu-id="d8e76-116">The authentication password.</span></span></param>
        <summary><span data-ttu-id="d8e76-117">認証の資格情報を使用して接続文字列を作成します。</span><span class="sxs-lookup"><span data-stu-id="d8e76-117">Creates a connection string using authentication credentials.</span></span></summary>
        <returns><span data-ttu-id="d8e76-118">作成したサービス バス接続文字列。</span><span class="sxs-lookup"><span data-stu-id="d8e76-118">The created service bus connection string.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateUsingSharedAccessKey">
      <MemberSignature Language="C#" Value="public static string CreateUsingSharedAccessKey (Uri endpoint, string keyName, string key);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string CreateUsingSharedAccessKey(class System.Uri endpoint, string keyName, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.CreateUsingSharedAccessKey(System.Uri,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateUsingSharedAccessKey (endpoint As Uri, keyName As String, key As String) As String" />
      <MemberSignature Language="F#" Value="static member CreateUsingSharedAccessKey : Uri * string * string -&gt; string" Usage="Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.CreateUsingSharedAccessKey (endpoint, keyName, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpoint" Type="System.Uri" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="endpoint"><span data-ttu-id="d8e76-119">エンドポイント。</span><span class="sxs-lookup"><span data-stu-id="d8e76-119">The endpoint.</span></span></param>
        <param name="keyName"><span data-ttu-id="d8e76-120">共有アクセス キーの名前。</span><span class="sxs-lookup"><span data-stu-id="d8e76-120">The name of the shared access key.</span></span></param>
        <param name="key"><span data-ttu-id="d8e76-121">共有アクセス キー。</span><span class="sxs-lookup"><span data-stu-id="d8e76-121">The shared access key.</span></span></param>
        <summary><span data-ttu-id="d8e76-122">共有アクセス キーを使用して接続文字列を作成します。</span><span class="sxs-lookup"><span data-stu-id="d8e76-122">Create a connection string using the shared access key.</span></span></summary>
        <returns><span data-ttu-id="d8e76-123">共有アクセス キーを使用して作成された接続。</span><span class="sxs-lookup"><span data-stu-id="d8e76-123">The created connection using the shared access key.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateUsingSharedAccessKey">
      <MemberSignature Language="C#" Value="public static string CreateUsingSharedAccessKey (System.Collections.Generic.IEnumerable&lt;Uri&gt; endpoints, int runtimePort, int managementPort, string keyName, string key);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string CreateUsingSharedAccessKey(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; endpoints, int32 runtimePort, int32 managementPort, string keyName, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.CreateUsingSharedAccessKey(System.Collections.Generic.IEnumerable{System.Uri},System.Int32,System.Int32,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateUsingSharedAccessKey (endpoints As IEnumerable(Of Uri), runtimePort As Integer, managementPort As Integer, keyName As String, key As String) As String" />
      <MemberSignature Language="F#" Value="static member CreateUsingSharedAccessKey : seq&lt;Uri&gt; * int * int * string * string -&gt; string" Usage="Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.CreateUsingSharedAccessKey (endpoints, runtimePort, managementPort, keyName, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpoints" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="runtimePort" Type="System.Int32" />
        <Parameter Name="managementPort" Type="System.Int32" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="endpoints"><span data-ttu-id="d8e76-124">エンドポイントのセット。</span><span class="sxs-lookup"><span data-stu-id="d8e76-124">The set of endpoints.</span></span></param>
        <param name="runtimePort"><span data-ttu-id="d8e76-125">ランタイム ポートです。</span><span class="sxs-lookup"><span data-stu-id="d8e76-125">The runtime port.</span></span></param>
        <param name="managementPort"><span data-ttu-id="d8e76-126">管理ポートです。</span><span class="sxs-lookup"><span data-stu-id="d8e76-126">The management port.</span></span></param>
        <param name="keyName"><span data-ttu-id="d8e76-127">共有アクセス キーの名前。</span><span class="sxs-lookup"><span data-stu-id="d8e76-127">The name of the shared access key.</span></span></param>
        <param name="key"><span data-ttu-id="d8e76-128">共有アクセス キー</span><span class="sxs-lookup"><span data-stu-id="d8e76-128">The shared access key</span></span></param>
        <summary><span data-ttu-id="d8e76-129">共有アクセス キーを使用して接続文字列を作成します。</span><span class="sxs-lookup"><span data-stu-id="d8e76-129">Create a connection string using the shared access key.</span></span></summary>
        <returns><span data-ttu-id="d8e76-130">共有アクセス キーを使用して作成された接続。</span><span class="sxs-lookup"><span data-stu-id="d8e76-130">The created connection using the shared access key.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateUsingSharedAccessSignature">
      <MemberSignature Language="C#" Value="public static string CreateUsingSharedAccessSignature (Uri endpoint, string entityPath, string publisher, string sharedAccessSignature);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string CreateUsingSharedAccessSignature(class System.Uri endpoint, string entityPath, string publisher, string sharedAccessSignature) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.CreateUsingSharedAccessSignature(System.Uri,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateUsingSharedAccessSignature (endpoint As Uri, entityPath As String, publisher As String, sharedAccessSignature As String) As String" />
      <MemberSignature Language="F#" Value="static member CreateUsingSharedAccessSignature : Uri * string * string * string -&gt; string" Usage="Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.CreateUsingSharedAccessSignature (endpoint, entityPath, publisher, sharedAccessSignature)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpoint" Type="System.Uri" />
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="publisher" Type="System.String" />
        <Parameter Name="sharedAccessSignature" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="endpoint"><span data-ttu-id="d8e76-131">エンドポイント。</span><span class="sxs-lookup"><span data-stu-id="d8e76-131">The endpoint.</span></span></param>
        <param name="entityPath"><span data-ttu-id="d8e76-132">メッセージング エンティティへのパス。</span><span class="sxs-lookup"><span data-stu-id="d8e76-132">The path to the messaging entity.</span></span></param>
        <param name="publisher"><span data-ttu-id="d8e76-133">パブリッシャーの id。</span><span class="sxs-lookup"><span data-stu-id="d8e76-133">The publisher ID.</span></span></param>
        <param name="sharedAccessSignature"><span data-ttu-id="d8e76-134">SAS キー。</span><span class="sxs-lookup"><span data-stu-id="d8e76-134">The SAS key.</span></span></param>
        <summary><span data-ttu-id="d8e76-135">SAS の資格情報を使用して接続文字列を作成します。</span><span class="sxs-lookup"><span data-stu-id="d8e76-135">Creates a connection string using SAS credentials.</span></span></summary>
        <returns><span data-ttu-id="d8e76-136"><see cref="T:System.String" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="d8e76-136">Returns <see cref="T:System.String" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateUsingSharedSecret">
      <MemberSignature Language="C#" Value="public static string CreateUsingSharedSecret (Uri endpoint, string issuer, string issuerSecret);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string CreateUsingSharedSecret(class System.Uri endpoint, string issuer, string issuerSecret) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.CreateUsingSharedSecret(System.Uri,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateUsingSharedSecret (endpoint As Uri, issuer As String, issuerSecret As String) As String" />
      <MemberSignature Language="F#" Value="static member CreateUsingSharedSecret : Uri * string * string -&gt; string" Usage="Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.CreateUsingSharedSecret (endpoint, issuer, issuerSecret)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpoint" Type="System.Uri" />
        <Parameter Name="issuer" Type="System.String" />
        <Parameter Name="issuerSecret" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="endpoint"><span data-ttu-id="d8e76-137">エンドポイント。</span><span class="sxs-lookup"><span data-stu-id="d8e76-137">The endpoint.</span></span></param>
        <param name="issuer"><span data-ttu-id="d8e76-138">発行者</span><span class="sxs-lookup"><span data-stu-id="d8e76-138">The issuer</span></span></param>
        <param name="issuerSecret"><span data-ttu-id="d8e76-139">発行者のシークレット。</span><span class="sxs-lookup"><span data-stu-id="d8e76-139">The issuer secret.</span></span></param>
        <summary><span data-ttu-id="d8e76-140">共有シークレット資格情報を使用して接続文字列を作成します。</span><span class="sxs-lookup"><span data-stu-id="d8e76-140">Creates a connection string using the shared secret credentials.</span></span></summary>
        <returns><span data-ttu-id="d8e76-141">共有シークレット資格情報を使用して作成された接続。</span><span class="sxs-lookup"><span data-stu-id="d8e76-141">The created connection using the shared secret credentials.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateUsingSharedSecret">
      <MemberSignature Language="C#" Value="public static string CreateUsingSharedSecret (System.Collections.Generic.IEnumerable&lt;Uri&gt; endpoints, System.Collections.Generic.IEnumerable&lt;Uri&gt; stsEndpoints, int runtimePort, int managementPort, string issuer, string issuerSecret);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string CreateUsingSharedSecret(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; endpoints, class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; stsEndpoints, int32 runtimePort, int32 managementPort, string issuer, string issuerSecret) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.CreateUsingSharedSecret(System.Collections.Generic.IEnumerable{System.Uri},System.Collections.Generic.IEnumerable{System.Uri},System.Int32,System.Int32,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateUsingSharedSecret (endpoints As IEnumerable(Of Uri), stsEndpoints As IEnumerable(Of Uri), runtimePort As Integer, managementPort As Integer, issuer As String, issuerSecret As String) As String" />
      <MemberSignature Language="F#" Value="static member CreateUsingSharedSecret : seq&lt;Uri&gt; * seq&lt;Uri&gt; * int * int * string * string -&gt; string" Usage="Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.CreateUsingSharedSecret (endpoints, stsEndpoints, runtimePort, managementPort, issuer, issuerSecret)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpoints" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="stsEndpoints" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="runtimePort" Type="System.Int32" />
        <Parameter Name="managementPort" Type="System.Int32" />
        <Parameter Name="issuer" Type="System.String" />
        <Parameter Name="issuerSecret" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="endpoints"><span data-ttu-id="d8e76-142">エンドポイント。</span><span class="sxs-lookup"><span data-stu-id="d8e76-142">The endpoints.</span></span></param>
        <param name="stsEndpoints"><span data-ttu-id="d8e76-143">セキュリティ トークン サービス エンドポイントのセット。</span><span class="sxs-lookup"><span data-stu-id="d8e76-143">The set of security token service endpoints.</span></span></param>
        <param name="runtimePort"><span data-ttu-id="d8e76-144">ランタイム ポートです。</span><span class="sxs-lookup"><span data-stu-id="d8e76-144">The runtime port.</span></span></param>
        <param name="managementPort"><span data-ttu-id="d8e76-145">管理ポートです。</span><span class="sxs-lookup"><span data-stu-id="d8e76-145">The management port.</span></span></param>
        <param name="issuer"><span data-ttu-id="d8e76-146">発行者。</span><span class="sxs-lookup"><span data-stu-id="d8e76-146">The issuer.</span></span></param>
        <param name="issuerSecret"><span data-ttu-id="d8e76-147">発行者のシークレット。</span><span class="sxs-lookup"><span data-stu-id="d8e76-147">The issuer secret.</span></span></param>
        <summary><span data-ttu-id="d8e76-148">共有シークレット資格情報を使用して接続文字列を作成します。</span><span class="sxs-lookup"><span data-stu-id="d8e76-148">Creates a connection string using the shared secret credentials.</span></span></summary>
        <returns><span data-ttu-id="d8e76-149">共有シークレット資格情報を使用して作成された接続。</span><span class="sxs-lookup"><span data-stu-id="d8e76-149">The created connection using the shared secret credentials.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateUsingWindowsCredential">
      <MemberSignature Language="C#" Value="public static string CreateUsingWindowsCredential (System.Collections.Generic.IEnumerable&lt;Uri&gt; endpoints, System.Collections.Generic.IEnumerable&lt;Uri&gt; stsEndpoints, int runtimePort, int managementPort, string domain, string user, System.Security.SecureString password);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string CreateUsingWindowsCredential(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; endpoints, class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; stsEndpoints, int32 runtimePort, int32 managementPort, string domain, string user, class System.Security.SecureString password) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.CreateUsingWindowsCredential(System.Collections.Generic.IEnumerable{System.Uri},System.Collections.Generic.IEnumerable{System.Uri},System.Int32,System.Int32,System.String,System.String,System.Security.SecureString)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateUsingWindowsCredential (endpoints As IEnumerable(Of Uri), stsEndpoints As IEnumerable(Of Uri), runtimePort As Integer, managementPort As Integer, domain As String, user As String, password As SecureString) As String" />
      <MemberSignature Language="F#" Value="static member CreateUsingWindowsCredential : seq&lt;Uri&gt; * seq&lt;Uri&gt; * int * int * string * string * System.Security.SecureString -&gt; string" Usage="Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.CreateUsingWindowsCredential (endpoints, stsEndpoints, runtimePort, managementPort, domain, user, password)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpoints" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="stsEndpoints" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="runtimePort" Type="System.Int32" />
        <Parameter Name="managementPort" Type="System.Int32" />
        <Parameter Name="domain" Type="System.String" />
        <Parameter Name="user" Type="System.String" />
        <Parameter Name="password" Type="System.Security.SecureString" />
      </Parameters>
      <Docs>
        <param name="endpoints"><span data-ttu-id="d8e76-150">一連のエンドポイント</span><span class="sxs-lookup"><span data-stu-id="d8e76-150">The set of endpoints</span></span></param>
        <param name="stsEndpoints"><span data-ttu-id="d8e76-151">セキュリティ トークン サービス エンドポイントのセット。</span><span class="sxs-lookup"><span data-stu-id="d8e76-151">The set of security token service endpoints.</span></span></param>
        <param name="runtimePort"><span data-ttu-id="d8e76-152">ランタイム ポートです。</span><span class="sxs-lookup"><span data-stu-id="d8e76-152">The runtime port.</span></span></param>
        <param name="managementPort"><span data-ttu-id="d8e76-153">管理ポートです。</span><span class="sxs-lookup"><span data-stu-id="d8e76-153">The management port.</span></span></param>
        <param name="domain"><span data-ttu-id="d8e76-154">接続を確立するドメインです。</span><span class="sxs-lookup"><span data-stu-id="d8e76-154">The domain where the connection will be established.</span></span></param>
        <param name="user"><span data-ttu-id="d8e76-155">ユーザー。</span><span class="sxs-lookup"><span data-stu-id="d8e76-155">The user.</span></span></param>
        <param name="password"><span data-ttu-id="d8e76-156">Windows のパスワード。</span><span class="sxs-lookup"><span data-stu-id="d8e76-156">The windows password.</span></span></param>
        <summary><span data-ttu-id="d8e76-157">Windows 資格情報を使用して接続文字列を作成します。</span><span class="sxs-lookup"><span data-stu-id="d8e76-157">Creates a connection string using Windows credentials.</span></span></summary>
        <returns><span data-ttu-id="d8e76-158">作成された接続文字列。</span><span class="sxs-lookup"><span data-stu-id="d8e76-158">The created connection string.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableAmqpLinkRedirect">
      <MemberSignature Language="C#" Value="public bool EnableAmqpLinkRedirect { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableAmqpLinkRedirect" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.EnableAmqpLinkRedirect" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableAmqpLinkRedirect As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableAmqpLinkRedirect : bool with get, set" Usage="Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.EnableAmqpLinkRedirect" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Endpoints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.HashSet&lt;Uri&gt; Endpoints { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.HashSet`1&lt;class System.Uri&gt; Endpoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.Endpoints" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Endpoints As HashSet(Of Uri)" />
      <MemberSignature Language="F#" Value="member this.Endpoints : System.Collections.Generic.HashSet&lt;Uri&gt;" Usage="Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.Endpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.HashSet&lt;System.Uri&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="d8e76-159">サービス エンドポイントのコレクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="d8e76-159">Gets a collection of service endpoints.</span></span> <span data-ttu-id="d8e76-160">各エンドポイントは、同じ Service Bus 名前空間を参照する必要があります。</span><span class="sxs-lookup"><span data-stu-id="d8e76-160">Each endpoint must reference the same Service Bus namespace.</span></span></summary>
        <value><span data-ttu-id="d8e76-161">エンドポイントのセット。</span><span class="sxs-lookup"><span data-stu-id="d8e76-161">A set of endpoints.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EntityPath">
      <MemberSignature Language="C#" Value="public string EntityPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EntityPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.EntityPath" />
      <MemberSignature Language="VB.NET" Value="Public Property EntityPath As String" />
      <MemberSignature Language="F#" Value="member this.EntityPath : string with get, set" Usage="Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.EntityPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="d8e76-162">エンティティ パスを取得または設定、 <see cref="P:Microsoft.ServiceBus.Messaging.QueueDescription.Path" />、 <see cref="P:Microsoft.ServiceBus.Messaging.TopicDescription.Path" />、および<see cref="P:Microsoft.ServiceBus.Messaging.EventHubDescription.Path" />プロパティです。</span><span class="sxs-lookup"><span data-stu-id="d8e76-162">Gets or sets the entity path for the <see cref="P:Microsoft.ServiceBus.Messaging.QueueDescription.Path" />, <see cref="P:Microsoft.ServiceBus.Messaging.TopicDescription.Path" />, and <see cref="P:Microsoft.ServiceBus.Messaging.EventHubDescription.Path" /> properties.</span></span></summary>
        <value><span data-ttu-id="d8e76-163"><see cref="T:System.String" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="d8e76-163">Returns <see cref="T:System.String" />.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAbsoluteManagementEndpoints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Uri&gt; GetAbsoluteManagementEndpoints ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IList`1&lt;class System.Uri&gt; GetAbsoluteManagementEndpoints() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.GetAbsoluteManagementEndpoints" />
      <MemberSignature Language="VB.NET" Value="Public Function GetAbsoluteManagementEndpoints () As IList(Of Uri)" />
      <MemberSignature Language="F#" Value="member this.GetAbsoluteManagementEndpoints : unit -&gt; System.Collections.Generic.IList&lt;Uri&gt;" Usage="serviceBusConnectionStringBuilder.GetAbsoluteManagementEndpoints " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Uri&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="d8e76-164">絶対管理エンドポイントを取得します。</span><span class="sxs-lookup"><span data-stu-id="d8e76-164">Retrieves the absolute management endpoints.</span></span></summary>
        <returns><span data-ttu-id="d8e76-165">絶対管理エンドポイント</span><span class="sxs-lookup"><span data-stu-id="d8e76-165">The absolute management endpoints</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAbsoluteRuntimeEndpoints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Uri&gt; GetAbsoluteRuntimeEndpoints ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IList`1&lt;class System.Uri&gt; GetAbsoluteRuntimeEndpoints() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.GetAbsoluteRuntimeEndpoints" />
      <MemberSignature Language="VB.NET" Value="Public Function GetAbsoluteRuntimeEndpoints () As IList(Of Uri)" />
      <MemberSignature Language="F#" Value="member this.GetAbsoluteRuntimeEndpoints : unit -&gt; System.Collections.Generic.IList&lt;Uri&gt;" Usage="serviceBusConnectionStringBuilder.GetAbsoluteRuntimeEndpoints " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Uri&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="d8e76-166">絶対ランタイム エンドポイントを取得します。</span><span class="sxs-lookup"><span data-stu-id="d8e76-166">Retrieves the absolute runtime endpoints.</span></span></summary>
        <returns><span data-ttu-id="d8e76-167">絶対ランタイムのエンドポイント。</span><span class="sxs-lookup"><span data-stu-id="d8e76-167">The absolute runtime endpoints.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ManagementPort">
      <MemberSignature Language="C#" Value="public int ManagementPort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ManagementPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.ManagementPort" />
      <MemberSignature Language="VB.NET" Value="Public Property ManagementPort As Integer" />
      <MemberSignature Language="F#" Value="member this.ManagementPort : int with get, set" Usage="Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.ManagementPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="d8e76-168">取得または管理操作用の TCP ポート番号を設定します。</span><span class="sxs-lookup"><span data-stu-id="d8e76-168">Gets or sets the TCP port number for management operations.</span></span></summary>
        <value><span data-ttu-id="d8e76-169">管理ポートです。</span><span class="sxs-lookup"><span data-stu-id="d8e76-169">The management port.</span></span></value>
        <remarks><span data-ttu-id="d8e76-170">これは、サーバーのシナリオでのみ使用します。</span><span class="sxs-lookup"><span data-stu-id="d8e76-170">This is only used in server scenario.</span></span> <span data-ttu-id="d8e76-171">Azure サービスへの接続文字列を生成するときに、既定値にこの残してください。</span><span class="sxs-lookup"><span data-stu-id="d8e76-171">When generating connection string for Azure service, this should be left at its default value.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="OAuthDomain">
      <MemberSignature Language="C#" Value="public string OAuthDomain { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OAuthDomain" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.OAuthDomain" />
      <MemberSignature Language="VB.NET" Value="Public Property OAuthDomain As String" />
      <MemberSignature Language="F#" Value="member this.OAuthDomain : string with get, set" Usage="Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.OAuthDomain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="d8e76-172">取得または認証のドメインの接続を設定します。</span><span class="sxs-lookup"><span data-stu-id="d8e76-172">Gets or sets the authentication domain for the connection.</span></span></summary>
        <value><span data-ttu-id="d8e76-173">接続の認証のドメイン。</span><span class="sxs-lookup"><span data-stu-id="d8e76-173">The authentication domain for the connection.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OAuthPassword">
      <MemberSignature Language="C#" Value="public System.Security.SecureString OAuthPassword { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Security.SecureString OAuthPassword" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.OAuthPassword" />
      <MemberSignature Language="VB.NET" Value="Public Property OAuthPassword As SecureString" />
      <MemberSignature Language="F#" Value="member this.OAuthPassword : System.Security.SecureString with get, set" Usage="Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.OAuthPassword" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Security.SecureString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="d8e76-174">取得または接続の認証のパスワードを設定します。</span><span class="sxs-lookup"><span data-stu-id="d8e76-174">Gets or sets the authentication password for the connection.</span></span></summary>
        <value><span data-ttu-id="d8e76-175">接続の認証のパスワード。</span><span class="sxs-lookup"><span data-stu-id="d8e76-175">The authentication password for the connection.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OAuthUsername">
      <MemberSignature Language="C#" Value="public string OAuthUsername { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OAuthUsername" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.OAuthUsername" />
      <MemberSignature Language="VB.NET" Value="Public Property OAuthUsername As String" />
      <MemberSignature Language="F#" Value="member this.OAuthUsername : string with get, set" Usage="Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.OAuthUsername" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="d8e76-176">取得または接続の認証ユーザー名を設定します。</span><span class="sxs-lookup"><span data-stu-id="d8e76-176">Gets or sets the authentication user name for the connection.</span></span></summary>
        <value><span data-ttu-id="d8e76-177">接続の認証ユーザー名。</span><span class="sxs-lookup"><span data-stu-id="d8e76-177">The authentication user name for the connection.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan OperationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan OperationTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.OperationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.OperationTimeout : TimeSpan with get, set" Usage="Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.OperationTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="d8e76-178">取得または設定、<see cref="T:System.TimeSpan" />メッセージング操作が開始がタイムアウトになるまでの時間を指定します。</span><span class="sxs-lookup"><span data-stu-id="d8e76-178">Gets or sets the <see cref="T:System.TimeSpan" /> that specifies how long the messaging operation has to complete before timing out.</span></span></summary>
        <value><span data-ttu-id="d8e76-179"><see cref="T:System.TimeSpan" />メッセージング操作が開始がタイムアウトになるまでの時間を指定します。既定値は、1 分です。</span><span class="sxs-lookup"><span data-stu-id="d8e76-179">The <see cref="T:System.TimeSpan" /> that specifies how long the messaging operation has to complete before timing out. The default value is one minute.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Publisher">
      <MemberSignature Language="C#" Value="public string Publisher { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Publisher" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.Publisher" />
      <MemberSignature Language="VB.NET" Value="Public Property Publisher As String" />
      <MemberSignature Language="F#" Value="member this.Publisher : string with get, set" Usage="Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.Publisher" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="d8e76-180">取得またはパブリッシャーの識別子を設定します。</span><span class="sxs-lookup"><span data-stu-id="d8e76-180">Get or sets the publisher identifier.</span></span></summary>
        <value><span data-ttu-id="d8e76-181"><see cref="T:System.String" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="d8e76-181">Returns <see cref="T:System.String" />.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RuntimePort">
      <MemberSignature Language="C#" Value="public int RuntimePort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 RuntimePort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.RuntimePort" />
      <MemberSignature Language="VB.NET" Value="Public Property RuntimePort As Integer" />
      <MemberSignature Language="F#" Value="member this.RuntimePort : int with get, set" Usage="Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.RuntimePort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="d8e76-182">取得またはランタイム操作用の TCP ポート番号を設定します。</span><span class="sxs-lookup"><span data-stu-id="d8e76-182">Gets or sets the TCP port number for runtime operation.</span></span></summary>
        <value><span data-ttu-id="d8e76-183">ランタイム ポートです。</span><span class="sxs-lookup"><span data-stu-id="d8e76-183">The runtime port.</span></span></value>
        <remarks><span data-ttu-id="d8e76-184">これは、サーバーのシナリオでのみ使用します。</span><span class="sxs-lookup"><span data-stu-id="d8e76-184">This is only used in server scenario.</span></span> <span data-ttu-id="d8e76-185">Azure サービスへの接続文字列を生成するときに、既定値にこの残してください。</span><span class="sxs-lookup"><span data-stu-id="d8e76-185">When generating connection string for Azure service, this should be left at its default value.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessKey">
      <MemberSignature Language="C#" Value="public string SharedAccessKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedAccessKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.SharedAccessKey" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedAccessKey As String" />
      <MemberSignature Language="F#" Value="member this.SharedAccessKey : string with get, set" Usage="Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.SharedAccessKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="d8e76-186">取得または接続の認証用の共有アクセス キーを設定します。</span><span class="sxs-lookup"><span data-stu-id="d8e76-186">Gets or sets the shared access key for the connection authentication.</span></span></summary>
        <value><span data-ttu-id="d8e76-187">接続の認証用の共有アクセス キー。</span><span class="sxs-lookup"><span data-stu-id="d8e76-187">The shared access key for the connection authentication.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessKeyName">
      <MemberSignature Language="C#" Value="public string SharedAccessKeyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedAccessKeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.SharedAccessKeyName" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedAccessKeyName As String" />
      <MemberSignature Language="F#" Value="member this.SharedAccessKeyName : string with get, set" Usage="Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.SharedAccessKeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="d8e76-188">取得または共有アクセス キーの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="d8e76-188">Gets or sets the name of the shared access key.</span></span></summary>
        <value><span data-ttu-id="d8e76-189">共有アクセス キーの名前。</span><span class="sxs-lookup"><span data-stu-id="d8e76-189">The name of the shared access key.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessSignature">
      <MemberSignature Language="C#" Value="public string SharedAccessSignature { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedAccessSignature" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.SharedAccessSignature" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedAccessSignature As String" />
      <MemberSignature Language="F#" Value="member this.SharedAccessSignature : string with get, set" Usage="Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.SharedAccessSignature" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="d8e76-190">取得または SAS アクセス トークンを設定します。</span><span class="sxs-lookup"><span data-stu-id="d8e76-190">Gets or sets the SAS access token.</span></span></summary>
        <value><span data-ttu-id="d8e76-191"><see cref="T:System.String" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="d8e76-191">Returns <see cref="T:System.String" />.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedSecretIssuerName">
      <MemberSignature Language="C#" Value="public string SharedSecretIssuerName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedSecretIssuerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.SharedSecretIssuerName" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedSecretIssuerName As String" />
      <MemberSignature Language="F#" Value="member this.SharedSecretIssuerName : string with get, set" Usage="Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.SharedSecretIssuerName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="d8e76-192">取得または共有シークレットの発行者名を設定します。</span><span class="sxs-lookup"><span data-stu-id="d8e76-192">Gets or sets the shared secret issuer name.</span></span></summary>
        <value><span data-ttu-id="d8e76-193">共有シークレットの発行者の名前。</span><span class="sxs-lookup"><span data-stu-id="d8e76-193">The shared secret issuer name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedSecretIssuerSecret">
      <MemberSignature Language="C#" Value="public string SharedSecretIssuerSecret { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedSecretIssuerSecret" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.SharedSecretIssuerSecret" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedSecretIssuerSecret As String" />
      <MemberSignature Language="F#" Value="member this.SharedSecretIssuerSecret : string with get, set" Usage="Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.SharedSecretIssuerSecret" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="d8e76-194">取得または共有シークレットの発行者のシークレットを設定します。</span><span class="sxs-lookup"><span data-stu-id="d8e76-194">Gets or sets the shared secret issuer secret.</span></span></summary>
        <value><span data-ttu-id="d8e76-195">共有シークレットの発行者のシークレット。</span><span class="sxs-lookup"><span data-stu-id="d8e76-195">The shared secret issuer secret.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StsEndpoints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.HashSet&lt;Uri&gt; StsEndpoints { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.HashSet`1&lt;class System.Uri&gt; StsEndpoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.StsEndpoints" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StsEndpoints As HashSet(Of Uri)" />
      <MemberSignature Language="F#" Value="member this.StsEndpoints : System.Collections.Generic.HashSet&lt;Uri&gt;" Usage="Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.StsEndpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.HashSet&lt;System.Uri&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="d8e76-196">STS エンドポイントのセットを取得します。</span><span class="sxs-lookup"><span data-stu-id="d8e76-196">Gets a set of STS endpoints.</span></span></summary>
        <value><span data-ttu-id="d8e76-197">STS エンドポイントのセット。</span><span class="sxs-lookup"><span data-stu-id="d8e76-197">A set of STS endpoints.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="serviceBusConnectionStringBuilder.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="d8e76-198">現在のオブジェクトを表す文字列を返します。</span><span class="sxs-lookup"><span data-stu-id="d8e76-198">Returns a string that represents the current object.</span></span></summary>
        <returns><span data-ttu-id="d8e76-199">現在のオブジェクトを表す文字列。</span><span class="sxs-lookup"><span data-stu-id="d8e76-199">A string that represents the current object.</span></span></returns>
        <remarks>To be added.</remarks>
        <code>
                <span data-ttu-id="d8e76-200">次のサンプル コードには、既存//接続文字列を Amqp を使用するトランスポートの種類の変更は、//フォーム var ビルダーの文字列で、新しい接続文字列を返す新しい ServiceBusConnectionStringBuilder(connectionString); を =ビルダー。TransportType TransportType.Amqp; を =Console.WriteLine (ビルダー。ToString()) です。</span><span class="sxs-lookup"><span data-stu-id="d8e76-200">// The following sample code takes an existing // connection string, change the transport type to use Amqp, // and return the new connection string in string form var bulider = new ServiceBusConnectionStringBuilder(connectionString); bulider.TransportType = TransportType.Amqp; Console.WriteLine(bulider.ToString());</span></span>
                </code>
      </Docs>
    </Member>
    <Member MemberName="TransportType">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.TransportType TransportType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.Messaging.TransportType TransportType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.TransportType" />
      <MemberSignature Language="VB.NET" Value="Public Property TransportType As TransportType" />
      <MemberSignature Language="F#" Value="member this.TransportType : Microsoft.ServiceBus.Messaging.TransportType with get, set" Usage="Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.TransportType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.TransportType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="d8e76-201">取得またはクライアントのメッセージング エンティティに使用するトランスポートの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="d8e76-201">Gets or sets the transport type to be used for client messaging entities.</span></span></summary>
        <value><span data-ttu-id="d8e76-202">接続に関連付けられているトランスポートの種類。</span><span class="sxs-lookup"><span data-stu-id="d8e76-202">The transport type associated with the connection.</span></span></value>
        <remarks><span data-ttu-id="d8e76-203">かどうか設定されていない、既定値は<see cref="F:Microsoft.ServiceBus.Messaging.TransportType.Amqp" />の<see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" />、既定値は、それ以外の場合<see cref="F:Microsoft.ServiceBus.Messaging.TransportType.NetMessaging" /></span><span class="sxs-lookup"><span data-stu-id="d8e76-203">If not set, default is <see cref="F:Microsoft.ServiceBus.Messaging.TransportType.Amqp" /> for <see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" />, otherwise default is <see cref="F:Microsoft.ServiceBus.Messaging.TransportType.NetMessaging" /></span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="WindowsCredentialDomain">
      <MemberSignature Language="C#" Value="public string WindowsCredentialDomain { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WindowsCredentialDomain" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.WindowsCredentialDomain" />
      <MemberSignature Language="VB.NET" Value="Public Property WindowsCredentialDomain As String" />
      <MemberSignature Language="F#" Value="member this.WindowsCredentialDomain : string with get, set" Usage="Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.WindowsCredentialDomain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="d8e76-204">取得または Windows 資格情報のドメインを設定します。</span><span class="sxs-lookup"><span data-stu-id="d8e76-204">Gets or sets the Windows credential domain.</span></span></summary>
        <value><span data-ttu-id="d8e76-205">Windows では、ドメイン資格情報します。</span><span class="sxs-lookup"><span data-stu-id="d8e76-205">The Windows credential domain.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WindowsCredentialPassword">
      <MemberSignature Language="C#" Value="public System.Security.SecureString WindowsCredentialPassword { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Security.SecureString WindowsCredentialPassword" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.WindowsCredentialPassword" />
      <MemberSignature Language="VB.NET" Value="Public Property WindowsCredentialPassword As SecureString" />
      <MemberSignature Language="F#" Value="member this.WindowsCredentialPassword : System.Security.SecureString with get, set" Usage="Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.WindowsCredentialPassword" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Security.SecureString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="d8e76-206">取得または Windows 資格情報のパスワードを設定します。</span><span class="sxs-lookup"><span data-stu-id="d8e76-206">Gets or sets the Windows credential password.</span></span></summary>
        <value><span data-ttu-id="d8e76-207">Windows 資格情報のパスワード。</span><span class="sxs-lookup"><span data-stu-id="d8e76-207">The Windows credential password.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WindowsCredentialUsername">
      <MemberSignature Language="C#" Value="public string WindowsCredentialUsername { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WindowsCredentialUsername" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.WindowsCredentialUsername" />
      <MemberSignature Language="VB.NET" Value="Public Property WindowsCredentialUsername As String" />
      <MemberSignature Language="F#" Value="member this.WindowsCredentialUsername : string with get, set" Usage="Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.WindowsCredentialUsername" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="d8e76-208">取得または Windows 資格情報のユーザー名を設定します。</span><span class="sxs-lookup"><span data-stu-id="d8e76-208">Gets or sets the Windows credential user name.</span></span></summary>
        <value><span data-ttu-id="d8e76-209">Windows 資格情報のユーザー名。</span><span class="sxs-lookup"><span data-stu-id="d8e76-209">The Windows credential user name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>