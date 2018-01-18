<Type Name="ServiceBusConnectionStringBuilder" FullName="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder">
  <TypeSignature Language="C#" Value="public class ServiceBusConnectionStringBuilder" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServiceBusConnectionStringBuilder extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceBusConnectionStringBuilder" />
  <TypeSignature Language="F#" Value="type ServiceBusConnectionStringBuilder = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="144d8-101">作成および接続文字列の内容を管理する簡単な方法を提供します。</span><span class="sxs-lookup"><span data-stu-id="144d8-101">Provides a simple way to create and manage the contents of connection strings.</span></span> <span data-ttu-id="144d8-102">このクラスは、クライアントのメッセージング エンティティを作成するための接続文字列を構築するために使用できます。</span><span class="sxs-lookup"><span data-stu-id="144d8-102">You can use this class to construct a connection string for creating client messaging entities.</span></span> <span data-ttu-id="144d8-103">既存の接続文字列で基本的な検証を実行するも使用できます。</span><span class="sxs-lookup"><span data-stu-id="144d8-103">It can also be used to perform basic validation on an existing connection string.</span></span></summary>
    <remarks>To be added.</remarks>
    <code>
                <span data-ttu-id="144d8-104">次のサンプル コードには、既存//接続文字列を Amqp を使用するトランスポートの種類の変更は、//フォーム var ビルダーの文字列で、新しい接続文字列を返す新しい ServiceBusConnectionStringBuilder(connectionString); を =ビルダー。TransportType TransportType.Amqp; を =Console.WriteLine (ビルダー。ToString()) です。</span><span class="sxs-lookup"><span data-stu-id="144d8-104">// The following sample code takes an existing // connection string, change the transport type to use Amqp, // and return the new connection string in string form var bulider = new ServiceBusConnectionStringBuilder(connectionString); bulider.TransportType = TransportType.Amqp; Console.WriteLine(bulider.ToString());</span></span>
                </code>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceBusConnectionStringBuilder ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="144d8-105"><see cref="T:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="144d8-105">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceBusConnectionStringBuilder (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (connectionString As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder : string -&gt; Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder" Usage="new Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder connectionString" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="144d8-106">接続文字列、Azure 管理ポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="144d8-106">The connection string, which you can obtain from the Azure Management Portal.</span></span></param>
        <summary><span data-ttu-id="144d8-107">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder" />指定した既存の接続文字列を持つクラス。</span><span class="sxs-lookup"><span data-stu-id="144d8-107">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder" /> class with a specified existing connection string.</span></span></summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Configuration.ConfigurationErrorsException"><span data-ttu-id="144d8-108">接続文字列にエンドポイントがない場合にスローします。接続文字列には、トークン プロバイダーを作成するための十分な情報はありません。</span><span class="sxs-lookup"><span data-stu-id="144d8-108">Throws if The connection string is missing endpoints.The connection string does not have enough information to form a token provider.</span></span> <span data-ttu-id="144d8-109">たとえば、SasIssuer 名が SasIssuer キーではないを指定した場合に発生します。<see cref="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.OperationTimeout" />値は有効ではありません<see cref="T:System.TimeSpan" />形式です。<see cref="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.RuntimePort" />または<see cref="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.ManagementPort" />値は整数形式ではありません。</span><span class="sxs-lookup"><span data-stu-id="144d8-109">For example, this can happen if you supplied a SasIssuer name but not a SasIssuer key.The <see cref="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.OperationTimeout" /> value is not in a valid <see cref="T:System.TimeSpan" /> format.The <see cref="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.RuntimePort" /> or <see cref="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.ManagementPort" /> values are not in an integer format.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CreateUsingOAuthCredential">
      <MemberSignature Language="C#" Value="public static string CreateUsingOAuthCredential (System.Collections.Generic.IEnumerable&lt;Uri&gt; endpoints, System.Collections.Generic.IEnumerable&lt;Uri&gt; stsEndpoints, int runtimePort, int managementPort, string domain, string user, System.Security.SecureString password);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string CreateUsingOAuthCredential(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; endpoints, class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; stsEndpoints, int32 runtimePort, int32 managementPort, string domain, string user, class System.Security.SecureString password) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.CreateUsingOAuthCredential(System.Collections.Generic.IEnumerable{System.Uri},System.Collections.Generic.IEnumerable{System.Uri},System.Int32,System.Int32,System.String,System.String,System.Security.SecureString)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateUsingOAuthCredential (endpoints As IEnumerable(Of Uri), stsEndpoints As IEnumerable(Of Uri), runtimePort As Integer, managementPort As Integer, domain As String, user As String, password As SecureString) As String" />
      <MemberSignature Language="F#" Value="static member CreateUsingOAuthCredential : seq&lt;Uri&gt; * seq&lt;Uri&gt; * int * int * string * string * System.Security.SecureString -&gt; string" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.CreateUsingOAuthCredential (endpoints, stsEndpoints, runtimePort, managementPort, domain, user, password)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
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
        <param name="endpoints"><span data-ttu-id="144d8-110">エンドポイントのセット。</span><span class="sxs-lookup"><span data-stu-id="144d8-110">The set of endpoints.</span></span></param>
        <param name="stsEndpoints"><span data-ttu-id="144d8-111">セキュリティ トークン サービス エンドポイントのセット。</span><span class="sxs-lookup"><span data-stu-id="144d8-111">The set of security token service endpoints.</span></span></param>
        <param name="runtimePort"><span data-ttu-id="144d8-112">ランタイム ポートです。</span><span class="sxs-lookup"><span data-stu-id="144d8-112">The runtime port.</span></span></param>
        <param name="managementPort"><span data-ttu-id="144d8-113">管理ポートです。</span><span class="sxs-lookup"><span data-stu-id="144d8-113">The management port.</span></span></param>
        <param name="domain"><span data-ttu-id="144d8-114">接続を確立するドメインです。</span><span class="sxs-lookup"><span data-stu-id="144d8-114">The domain where the connection will be established.</span></span></param>
        <param name="user"><span data-ttu-id="144d8-115">認証ユーザー。</span><span class="sxs-lookup"><span data-stu-id="144d8-115">The authentication user.</span></span></param>
        <param name="password"><span data-ttu-id="144d8-116">認証のパスワード。</span><span class="sxs-lookup"><span data-stu-id="144d8-116">The authentication password.</span></span></param>
        <summary><span data-ttu-id="144d8-117">認証の資格情報を使用して接続文字列を作成します。</span><span class="sxs-lookup"><span data-stu-id="144d8-117">Creates a connection string using authentication credentials.</span></span></summary>
        <returns><span data-ttu-id="144d8-118">作成したサービス バス接続文字列。</span><span class="sxs-lookup"><span data-stu-id="144d8-118">The created service bus connection string.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="144d8-119">エンドポイントまたはユーザーまたはパスワード</span><span class="sxs-lookup"><span data-stu-id="144d8-119">endpoints or user or password</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateUsingSharedAccessKey">
      <MemberSignature Language="C#" Value="public static string CreateUsingSharedAccessKey (Uri endpoint, string keyName, string key);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string CreateUsingSharedAccessKey(class System.Uri endpoint, string keyName, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.CreateUsingSharedAccessKey(System.Uri,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateUsingSharedAccessKey (endpoint As Uri, keyName As String, key As String) As String" />
      <MemberSignature Language="F#" Value="static member CreateUsingSharedAccessKey : Uri * string * string -&gt; string" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.CreateUsingSharedAccessKey (endpoint, keyName, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
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
        <param name="endpoint"><span data-ttu-id="144d8-120">エンドポイント。</span><span class="sxs-lookup"><span data-stu-id="144d8-120">The endpoint.</span></span></param>
        <param name="keyName"><span data-ttu-id="144d8-121">共有アクセス キーの名前。</span><span class="sxs-lookup"><span data-stu-id="144d8-121">The name of the shared access key.</span></span></param>
        <param name="key"><span data-ttu-id="144d8-122">共有アクセス キー。</span><span class="sxs-lookup"><span data-stu-id="144d8-122">The shared access key.</span></span></param>
        <summary><span data-ttu-id="144d8-123">共有アクセス キーを使用して接続文字列を作成します。</span><span class="sxs-lookup"><span data-stu-id="144d8-123">Create a connection string using the shared access key.</span></span></summary>
        <returns><span data-ttu-id="144d8-124">共有アクセス キーを使用して作成された接続。</span><span class="sxs-lookup"><span data-stu-id="144d8-124">The created connection using the shared access key.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateUsingSharedAccessKey">
      <MemberSignature Language="C#" Value="public static string CreateUsingSharedAccessKey (System.Collections.Generic.IEnumerable&lt;Uri&gt; endpoints, int runtimePort, int managementPort, string keyName, string key);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string CreateUsingSharedAccessKey(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; endpoints, int32 runtimePort, int32 managementPort, string keyName, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.CreateUsingSharedAccessKey(System.Collections.Generic.IEnumerable{System.Uri},System.Int32,System.Int32,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateUsingSharedAccessKey (endpoints As IEnumerable(Of Uri), runtimePort As Integer, managementPort As Integer, keyName As String, key As String) As String" />
      <MemberSignature Language="F#" Value="static member CreateUsingSharedAccessKey : seq&lt;Uri&gt; * int * int * string * string -&gt; string" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.CreateUsingSharedAccessKey (endpoints, runtimePort, managementPort, keyName, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
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
        <param name="endpoints"><span data-ttu-id="144d8-125">エンドポイントのセット。</span><span class="sxs-lookup"><span data-stu-id="144d8-125">The set of endpoints.</span></span></param>
        <param name="runtimePort"><span data-ttu-id="144d8-126">ランタイム ポートです。</span><span class="sxs-lookup"><span data-stu-id="144d8-126">The runtime port.</span></span></param>
        <param name="managementPort"><span data-ttu-id="144d8-127">管理ポートです。</span><span class="sxs-lookup"><span data-stu-id="144d8-127">The management port.</span></span></param>
        <param name="keyName"><span data-ttu-id="144d8-128">共有アクセス キーの名前。</span><span class="sxs-lookup"><span data-stu-id="144d8-128">The name of the shared access key.</span></span></param>
        <param name="key"><span data-ttu-id="144d8-129">共有アクセス キー</span><span class="sxs-lookup"><span data-stu-id="144d8-129">The shared access key</span></span></param>
        <summary><span data-ttu-id="144d8-130">共有アクセス キーを使用して接続文字列を作成します。</span><span class="sxs-lookup"><span data-stu-id="144d8-130">Create a connection string using the shared access key.</span></span></summary>
        <returns><span data-ttu-id="144d8-131">共有アクセス キーを使用して作成された接続。</span><span class="sxs-lookup"><span data-stu-id="144d8-131">The created connection using the shared access key.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateUsingSharedSecret">
      <MemberSignature Language="C#" Value="public static string CreateUsingSharedSecret (Uri endpoint, string issuer, string issuerSecret);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string CreateUsingSharedSecret(class System.Uri endpoint, string issuer, string issuerSecret) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.CreateUsingSharedSecret(System.Uri,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateUsingSharedSecret (endpoint As Uri, issuer As String, issuerSecret As String) As String" />
      <MemberSignature Language="F#" Value="static member CreateUsingSharedSecret : Uri * string * string -&gt; string" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.CreateUsingSharedSecret (endpoint, issuer, issuerSecret)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
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
        <param name="endpoint"><span data-ttu-id="144d8-132">エンドポイント。</span><span class="sxs-lookup"><span data-stu-id="144d8-132">The endpoint.</span></span></param>
        <param name="issuer"><span data-ttu-id="144d8-133">発行者</span><span class="sxs-lookup"><span data-stu-id="144d8-133">The issuer</span></span></param>
        <param name="issuerSecret"><span data-ttu-id="144d8-134">発行者のシークレット。</span><span class="sxs-lookup"><span data-stu-id="144d8-134">The issuer secret.</span></span></param>
        <summary><span data-ttu-id="144d8-135">共有シークレット資格情報を使用して接続文字列を作成します。</span><span class="sxs-lookup"><span data-stu-id="144d8-135">Creates a connection string using the shared secret credentials.</span></span></summary>
        <returns><span data-ttu-id="144d8-136">共有シークレット資格情報を使用して作成された接続。</span><span class="sxs-lookup"><span data-stu-id="144d8-136">The created connection using the shared secret credentials.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="144d8-137">エンドポイントまたは発行者または issuerSecret</span><span class="sxs-lookup"><span data-stu-id="144d8-137">endpoint or issuer or issuerSecret</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateUsingSharedSecret">
      <MemberSignature Language="C#" Value="public static string CreateUsingSharedSecret (System.Collections.Generic.IEnumerable&lt;Uri&gt; endpoints, System.Collections.Generic.IEnumerable&lt;Uri&gt; stsEndpoints, int runtimePort, int managementPort, string issuer, string issuerSecret);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string CreateUsingSharedSecret(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; endpoints, class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; stsEndpoints, int32 runtimePort, int32 managementPort, string issuer, string issuerSecret) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.CreateUsingSharedSecret(System.Collections.Generic.IEnumerable{System.Uri},System.Collections.Generic.IEnumerable{System.Uri},System.Int32,System.Int32,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateUsingSharedSecret (endpoints As IEnumerable(Of Uri), stsEndpoints As IEnumerable(Of Uri), runtimePort As Integer, managementPort As Integer, issuer As String, issuerSecret As String) As String" />
      <MemberSignature Language="F#" Value="static member CreateUsingSharedSecret : seq&lt;Uri&gt; * seq&lt;Uri&gt; * int * int * string * string -&gt; string" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.CreateUsingSharedSecret (endpoints, stsEndpoints, runtimePort, managementPort, issuer, issuerSecret)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
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
        <param name="endpoints"><span data-ttu-id="144d8-138">エンドポイント。</span><span class="sxs-lookup"><span data-stu-id="144d8-138">The endpoints.</span></span></param>
        <param name="stsEndpoints"><span data-ttu-id="144d8-139">セキュリティ トークン サービス エンドポイントのセット。</span><span class="sxs-lookup"><span data-stu-id="144d8-139">The set of security token service endpoints.</span></span></param>
        <param name="runtimePort"><span data-ttu-id="144d8-140">ランタイム ポートです。</span><span class="sxs-lookup"><span data-stu-id="144d8-140">The runtime port.</span></span></param>
        <param name="managementPort"><span data-ttu-id="144d8-141">管理ポートです。</span><span class="sxs-lookup"><span data-stu-id="144d8-141">The management port.</span></span></param>
        <param name="issuer"><span data-ttu-id="144d8-142">発行者。</span><span class="sxs-lookup"><span data-stu-id="144d8-142">The issuer.</span></span></param>
        <param name="issuerSecret"><span data-ttu-id="144d8-143">発行者のシークレット。</span><span class="sxs-lookup"><span data-stu-id="144d8-143">The issuer secret.</span></span></param>
        <summary><span data-ttu-id="144d8-144">共有シークレット資格情報を使用して接続文字列を作成します。</span><span class="sxs-lookup"><span data-stu-id="144d8-144">Creates a connection string using the shared secret credentials.</span></span></summary>
        <returns><span data-ttu-id="144d8-145">共有シークレット資格情報を使用して作成された接続。</span><span class="sxs-lookup"><span data-stu-id="144d8-145">The created connection using the shared secret credentials.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="144d8-146">エンドポイントまたは発行者または issuerSecret</span><span class="sxs-lookup"><span data-stu-id="144d8-146">endpoints or issuer or issuerSecret</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateUsingWindowsCredential">
      <MemberSignature Language="C#" Value="public static string CreateUsingWindowsCredential (System.Collections.Generic.IEnumerable&lt;Uri&gt; endpoints, System.Collections.Generic.IEnumerable&lt;Uri&gt; stsEndpoints, int runtimePort, int managementPort, string domain, string user, System.Security.SecureString password);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string CreateUsingWindowsCredential(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; endpoints, class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; stsEndpoints, int32 runtimePort, int32 managementPort, string domain, string user, class System.Security.SecureString password) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.CreateUsingWindowsCredential(System.Collections.Generic.IEnumerable{System.Uri},System.Collections.Generic.IEnumerable{System.Uri},System.Int32,System.Int32,System.String,System.String,System.Security.SecureString)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateUsingWindowsCredential (endpoints As IEnumerable(Of Uri), stsEndpoints As IEnumerable(Of Uri), runtimePort As Integer, managementPort As Integer, domain As String, user As String, password As SecureString) As String" />
      <MemberSignature Language="F#" Value="static member CreateUsingWindowsCredential : seq&lt;Uri&gt; * seq&lt;Uri&gt; * int * int * string * string * System.Security.SecureString -&gt; string" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.CreateUsingWindowsCredential (endpoints, stsEndpoints, runtimePort, managementPort, domain, user, password)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
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
        <param name="endpoints"><span data-ttu-id="144d8-147">一連のエンドポイント</span><span class="sxs-lookup"><span data-stu-id="144d8-147">The set of endpoints</span></span></param>
        <param name="stsEndpoints"><span data-ttu-id="144d8-148">セキュリティ トークン サービス エンドポイントのセット。</span><span class="sxs-lookup"><span data-stu-id="144d8-148">The set of security token service endpoints.</span></span></param>
        <param name="runtimePort"><span data-ttu-id="144d8-149">ランタイム ポートです。</span><span class="sxs-lookup"><span data-stu-id="144d8-149">The runtime port.</span></span></param>
        <param name="managementPort"><span data-ttu-id="144d8-150">管理ポートです。</span><span class="sxs-lookup"><span data-stu-id="144d8-150">The management port.</span></span></param>
        <param name="domain"><span data-ttu-id="144d8-151">接続を確立するドメインです。</span><span class="sxs-lookup"><span data-stu-id="144d8-151">The domain where the connection will be established.</span></span></param>
        <param name="user"><span data-ttu-id="144d8-152">ユーザー。</span><span class="sxs-lookup"><span data-stu-id="144d8-152">The user.</span></span></param>
        <param name="password"><span data-ttu-id="144d8-153">Windows のパスワード。</span><span class="sxs-lookup"><span data-stu-id="144d8-153">The windows password.</span></span></param>
        <summary><span data-ttu-id="144d8-154">Windows 資格情報を使用して接続文字列を作成します。</span><span class="sxs-lookup"><span data-stu-id="144d8-154">Creates a connection string using Windows credentials.</span></span></summary>
        <returns><span data-ttu-id="144d8-155">作成された接続文字列。</span><span class="sxs-lookup"><span data-stu-id="144d8-155">The created connection string.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="144d8-156">エンドポイントまたはユーザーまたはパスワード</span><span class="sxs-lookup"><span data-stu-id="144d8-156">endpoints or user or password</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="Endpoints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.HashSet&lt;Uri&gt; Endpoints { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.HashSet`1&lt;class System.Uri&gt; Endpoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.Endpoints" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Endpoints As HashSet(Of Uri)" />
      <MemberSignature Language="F#" Value="member this.Endpoints : System.Collections.Generic.HashSet&lt;Uri&gt;" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.Endpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.HashSet&lt;System.Uri&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="144d8-157">サービス エンドポイントのコレクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="144d8-157">Gets a collection of service endpoints.</span></span> <span data-ttu-id="144d8-158">各エンドポイントは、同じ Service Bus 名前空間を参照する必要があります。</span><span class="sxs-lookup"><span data-stu-id="144d8-158">Each endpoint must reference the same Service Bus namespace.</span></span></summary>
        <value><span data-ttu-id="144d8-159">エンドポイントのセット。</span><span class="sxs-lookup"><span data-stu-id="144d8-159">A set of endpoints.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAbsoluteManagementEndpoints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Uri&gt; GetAbsoluteManagementEndpoints ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IList`1&lt;class System.Uri&gt; GetAbsoluteManagementEndpoints() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.GetAbsoluteManagementEndpoints" />
      <MemberSignature Language="VB.NET" Value="Public Function GetAbsoluteManagementEndpoints () As IList(Of Uri)" />
      <MemberSignature Language="F#" Value="member this.GetAbsoluteManagementEndpoints : unit -&gt; System.Collections.Generic.IList&lt;Uri&gt;" Usage="serviceBusConnectionStringBuilder.GetAbsoluteManagementEndpoints " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Uri&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="144d8-160">絶対管理エンドポイントを取得します。</span><span class="sxs-lookup"><span data-stu-id="144d8-160">Retrieves the absolute management endpoints.</span></span></summary>
        <returns><span data-ttu-id="144d8-161">絶対管理エンドポイント</span><span class="sxs-lookup"><span data-stu-id="144d8-161">The absolute management endpoints</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAbsoluteRuntimeEndpoints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Uri&gt; GetAbsoluteRuntimeEndpoints ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IList`1&lt;class System.Uri&gt; GetAbsoluteRuntimeEndpoints() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.GetAbsoluteRuntimeEndpoints" />
      <MemberSignature Language="VB.NET" Value="Public Function GetAbsoluteRuntimeEndpoints () As IList(Of Uri)" />
      <MemberSignature Language="F#" Value="member this.GetAbsoluteRuntimeEndpoints : unit -&gt; System.Collections.Generic.IList&lt;Uri&gt;" Usage="serviceBusConnectionStringBuilder.GetAbsoluteRuntimeEndpoints " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Uri&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="144d8-162">絶対ランタイム エンドポイントを取得します。</span><span class="sxs-lookup"><span data-stu-id="144d8-162">Retrieves the absolute runtime endpoints.</span></span></summary>
        <returns><span data-ttu-id="144d8-163">絶対ランタイムのエンドポイント。</span><span class="sxs-lookup"><span data-stu-id="144d8-163">The absolute runtime endpoints.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ManagementPort">
      <MemberSignature Language="C#" Value="public int ManagementPort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ManagementPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.ManagementPort" />
      <MemberSignature Language="VB.NET" Value="Public Property ManagementPort As Integer" />
      <MemberSignature Language="F#" Value="member this.ManagementPort : int with get, set" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.ManagementPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="144d8-164">取得または管理操作用の TCP ポート番号を設定します。</span><span class="sxs-lookup"><span data-stu-id="144d8-164">Gets or sets the TCP port number for management operations.</span></span></summary>
        <value><span data-ttu-id="144d8-165">管理ポートです。</span><span class="sxs-lookup"><span data-stu-id="144d8-165">The management port.</span></span></value>
        <remarks><span data-ttu-id="144d8-166">これは、サーバーのシナリオでのみ使用します。</span><span class="sxs-lookup"><span data-stu-id="144d8-166">This is only used in server scenario.</span></span> <span data-ttu-id="144d8-167">Azure サービスへの接続文字列を生成するときにこれを既定値です。 残してください。</span><span class="sxs-lookup"><span data-stu-id="144d8-167">When generating connection string for azure service, this should be left at its default value;.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="OAuthDomain">
      <MemberSignature Language="C#" Value="public string OAuthDomain { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OAuthDomain" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.OAuthDomain" />
      <MemberSignature Language="VB.NET" Value="Public Property OAuthDomain As String" />
      <MemberSignature Language="F#" Value="member this.OAuthDomain : string with get, set" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.OAuthDomain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="144d8-168">取得または認証のドメインの接続を設定します。</span><span class="sxs-lookup"><span data-stu-id="144d8-168">Gets or sets the authentication domain for the connection.</span></span></summary>
        <value><span data-ttu-id="144d8-169">接続の認証のドメイン。</span><span class="sxs-lookup"><span data-stu-id="144d8-169">The authentication domain for the connection.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OAuthPassword">
      <MemberSignature Language="C#" Value="public System.Security.SecureString OAuthPassword { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Security.SecureString OAuthPassword" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.OAuthPassword" />
      <MemberSignature Language="VB.NET" Value="Public Property OAuthPassword As SecureString" />
      <MemberSignature Language="F#" Value="member this.OAuthPassword : System.Security.SecureString with get, set" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.OAuthPassword" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Security.SecureString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="144d8-170">取得または接続の認証のパスワードを設定します。</span><span class="sxs-lookup"><span data-stu-id="144d8-170">Gets or sets the authentication password for the connection.</span></span></summary>
        <value><span data-ttu-id="144d8-171">接続の認証のパスワード。</span><span class="sxs-lookup"><span data-stu-id="144d8-171">The authentication password for the connection.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OAuthUsername">
      <MemberSignature Language="C#" Value="public string OAuthUsername { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OAuthUsername" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.OAuthUsername" />
      <MemberSignature Language="VB.NET" Value="Public Property OAuthUsername As String" />
      <MemberSignature Language="F#" Value="member this.OAuthUsername : string with get, set" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.OAuthUsername" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="144d8-172">取得または接続の認証ユーザー名を設定します。</span><span class="sxs-lookup"><span data-stu-id="144d8-172">Gets or sets the authentication user name for the connection.</span></span></summary>
        <value><span data-ttu-id="144d8-173">接続の認証ユーザー名。</span><span class="sxs-lookup"><span data-stu-id="144d8-173">The authentication user name for the connection.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan OperationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan OperationTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.OperationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.OperationTimeout : TimeSpan with get, set" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.OperationTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="144d8-174">取得または設定、<see cref="T:System.TimeSpan" />メッセージング操作が開始がタイムアウトになるまでの時間を指定します。</span><span class="sxs-lookup"><span data-stu-id="144d8-174">Gets or sets the <see cref="T:System.TimeSpan" /> that specifies how long the messaging operation has to complete before timing out.</span></span></summary>
        <value><span data-ttu-id="144d8-175"><see cref="T:System.TimeSpan" />メッセージング操作が開始がタイムアウトになるまでの時間を指定します。既定値は、1 分です。</span><span class="sxs-lookup"><span data-stu-id="144d8-175">The <see cref="T:System.TimeSpan" /> that specifies how long the messaging operation has to complete before timing out. The default value is one minute.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RuntimePort">
      <MemberSignature Language="C#" Value="public int RuntimePort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 RuntimePort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.RuntimePort" />
      <MemberSignature Language="VB.NET" Value="Public Property RuntimePort As Integer" />
      <MemberSignature Language="F#" Value="member this.RuntimePort : int with get, set" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.RuntimePort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="144d8-176">取得またはランタイム操作用の TCP ポート番号を設定します。</span><span class="sxs-lookup"><span data-stu-id="144d8-176">Gets or sets the TCP port number for runtime operation.</span></span></summary>
        <value><span data-ttu-id="144d8-177">ランタイム ポートです。</span><span class="sxs-lookup"><span data-stu-id="144d8-177">The runtime port.</span></span></value>
        <remarks><span data-ttu-id="144d8-178">これは、サーバーのシナリオでのみ使用します。</span><span class="sxs-lookup"><span data-stu-id="144d8-178">This is only used in server scenario.</span></span> <span data-ttu-id="144d8-179">Azure サービスへの接続文字列を生成するときにこれを既定値です。 残してください。</span><span class="sxs-lookup"><span data-stu-id="144d8-179">When generating connection string for azure service, this should be left at its default value;.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessKey">
      <MemberSignature Language="C#" Value="public string SharedAccessKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedAccessKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.SharedAccessKey" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedAccessKey As String" />
      <MemberSignature Language="F#" Value="member this.SharedAccessKey : string with get, set" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.SharedAccessKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="144d8-180">取得または接続の認証用の共有アクセス キーを設定します。</span><span class="sxs-lookup"><span data-stu-id="144d8-180">Gets or sets the shared access key for the connection authentication.</span></span></summary>
        <value><span data-ttu-id="144d8-181">接続の認証用の共有アクセス キー。</span><span class="sxs-lookup"><span data-stu-id="144d8-181">The shared access key for the connection authentication.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessKeyName">
      <MemberSignature Language="C#" Value="public string SharedAccessKeyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedAccessKeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.SharedAccessKeyName" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedAccessKeyName As String" />
      <MemberSignature Language="F#" Value="member this.SharedAccessKeyName : string with get, set" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.SharedAccessKeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="144d8-182">取得または共有アクセス キーの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="144d8-182">Gets or sets the name of the shared access key.</span></span></summary>
        <value><span data-ttu-id="144d8-183">共有アクセス キーの名前。</span><span class="sxs-lookup"><span data-stu-id="144d8-183">The name of the shared access key.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedSecretIssuerName">
      <MemberSignature Language="C#" Value="public string SharedSecretIssuerName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedSecretIssuerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.SharedSecretIssuerName" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedSecretIssuerName As String" />
      <MemberSignature Language="F#" Value="member this.SharedSecretIssuerName : string with get, set" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.SharedSecretIssuerName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="144d8-184">取得または共有シークレットの発行者名を設定します。</span><span class="sxs-lookup"><span data-stu-id="144d8-184">Gets or sets the shared secret issuer name.</span></span></summary>
        <value><span data-ttu-id="144d8-185">共有シークレットの発行者の名前。</span><span class="sxs-lookup"><span data-stu-id="144d8-185">The shared secret issuer name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedSecretIssuerSecret">
      <MemberSignature Language="C#" Value="public string SharedSecretIssuerSecret { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedSecretIssuerSecret" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.SharedSecretIssuerSecret" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedSecretIssuerSecret As String" />
      <MemberSignature Language="F#" Value="member this.SharedSecretIssuerSecret : string with get, set" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.SharedSecretIssuerSecret" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="144d8-186">取得または共有シークレットの発行者のシークレットを設定します。</span><span class="sxs-lookup"><span data-stu-id="144d8-186">Gets or sets the shared secret issuer secret.</span></span></summary>
        <value><span data-ttu-id="144d8-187">共有シークレットの発行者のシークレット。</span><span class="sxs-lookup"><span data-stu-id="144d8-187">The shared secret issuer secret.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StsEndpoints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.HashSet&lt;Uri&gt; StsEndpoints { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.HashSet`1&lt;class System.Uri&gt; StsEndpoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.StsEndpoints" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StsEndpoints As HashSet(Of Uri)" />
      <MemberSignature Language="F#" Value="member this.StsEndpoints : System.Collections.Generic.HashSet&lt;Uri&gt;" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.StsEndpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.HashSet&lt;System.Uri&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="144d8-188">STS エンドポイントのセットを取得します。</span><span class="sxs-lookup"><span data-stu-id="144d8-188">Gets a set of STS endpoints.</span></span></summary>
        <value><span data-ttu-id="144d8-189">STS エンドポイントのセット。</span><span class="sxs-lookup"><span data-stu-id="144d8-189">A set of STS endpoints.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="serviceBusConnectionStringBuilder.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="144d8-190">現在のオブジェクトを表す文字列を返します。</span><span class="sxs-lookup"><span data-stu-id="144d8-190">Returns a string that represents the current object.</span></span></summary>
        <returns><span data-ttu-id="144d8-191">現在のオブジェクトを表す文字列。</span><span class="sxs-lookup"><span data-stu-id="144d8-191">A string that represents the current object.</span></span></returns>
        <remarks>To be added.</remarks>
        <code>
                <span data-ttu-id="144d8-192">次のサンプル コードには、既存//接続文字列を Amqp を使用するトランスポートの種類の変更は、//フォーム var ビルダーの文字列で、新しい接続文字列を返す新しい ServiceBusConnectionStringBuilder(connectionString); を =ビルダー。TransportType TransportType.Amqp; を =Console.WriteLine (ビルダー。ToString()) です。</span><span class="sxs-lookup"><span data-stu-id="144d8-192">// The following sample code takes an existing // connection string, change the transport type to use Amqp, // and return the new connection string in string form var bulider = new ServiceBusConnectionStringBuilder(connectionString); bulider.TransportType = TransportType.Amqp; Console.WriteLine(bulider.ToString());</span></span>
                </code>
      </Docs>
    </Member>
    <Member MemberName="WindowsCredentialDomain">
      <MemberSignature Language="C#" Value="public string WindowsCredentialDomain { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WindowsCredentialDomain" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.WindowsCredentialDomain" />
      <MemberSignature Language="VB.NET" Value="Public Property WindowsCredentialDomain As String" />
      <MemberSignature Language="F#" Value="member this.WindowsCredentialDomain : string with get, set" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.WindowsCredentialDomain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="144d8-193">取得または Windows 資格情報のドメインを設定します。</span><span class="sxs-lookup"><span data-stu-id="144d8-193">Gets or sets the Windows credential domain.</span></span></summary>
        <value><span data-ttu-id="144d8-194">Windows では、ドメイン資格情報します。</span><span class="sxs-lookup"><span data-stu-id="144d8-194">The Windows credential domain.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WindowsCredentialPassword">
      <MemberSignature Language="C#" Value="public System.Security.SecureString WindowsCredentialPassword { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Security.SecureString WindowsCredentialPassword" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.WindowsCredentialPassword" />
      <MemberSignature Language="VB.NET" Value="Public Property WindowsCredentialPassword As SecureString" />
      <MemberSignature Language="F#" Value="member this.WindowsCredentialPassword : System.Security.SecureString with get, set" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.WindowsCredentialPassword" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Security.SecureString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="144d8-195">取得または Windows 資格情報のパスワードを設定します。</span><span class="sxs-lookup"><span data-stu-id="144d8-195">Gets or sets the Windows credential password.</span></span></summary>
        <value><span data-ttu-id="144d8-196">Windows 資格情報のパスワード。</span><span class="sxs-lookup"><span data-stu-id="144d8-196">The Windows credential password.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WindowsCredentialUsername">
      <MemberSignature Language="C#" Value="public string WindowsCredentialUsername { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WindowsCredentialUsername" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.WindowsCredentialUsername" />
      <MemberSignature Language="VB.NET" Value="Public Property WindowsCredentialUsername As String" />
      <MemberSignature Language="F#" Value="member this.WindowsCredentialUsername : string with get, set" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.WindowsCredentialUsername" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="144d8-197">取得または Windows 資格情報のユーザー名を設定します。</span><span class="sxs-lookup"><span data-stu-id="144d8-197">Gets or sets the Windows credential user name.</span></span></summary>
        <value><span data-ttu-id="144d8-198">Windows 資格情報のユーザー名。</span><span class="sxs-lookup"><span data-stu-id="144d8-198">The Windows credential user name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>