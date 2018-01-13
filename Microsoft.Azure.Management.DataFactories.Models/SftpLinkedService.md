<Type Name="SftpLinkedService" FullName="Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService">
  <TypeSignature Language="C#" Value="public class SftpLinkedService : Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SftpLinkedService extends Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class SftpLinkedService&#xA;Inherits LinkedServiceTypeProperties" />
  <TypeSignature Language="F#" Value="type SftpLinkedService = class&#xA;    inherit LinkedServiceTypeProperties" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfTypeName("Sftp")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="3cf52-101">リンクされたサービス サーバーの SSH ファイル転送プロトコル (SFTP)。</span><span class="sxs-lookup"><span data-stu-id="3cf52-101">A linked service for an SSH File Transfer Protocol (SFTP) server.</span></span> 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SftpLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3cf52-102"><see cref="T:Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3cf52-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SftpLinkedService (string host, string authenticationType, string username);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string host, string authenticationType, string username) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (host As String, authenticationType As String, username As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService : string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService" Usage="new Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService (host, authenticationType, username)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="host" Type="System.String" />
        <Parameter Name="authenticationType" Type="System.String" />
        <Parameter Name="username" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="host">To be added.</param>
        <param name="authenticationType">To be added.</param>
        <param name="username">To be added.</param>
        <summary>
            <span data-ttu-id="3cf52-103">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService" />必須の引数を持つクラス。</span><span class="sxs-lookup"><span data-stu-id="3cf52-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService" /> class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationType">
      <MemberSignature Language="C#" Value="public string AuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService.AuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationType As String" />
      <MemberSignature Language="F#" Value="member this.AuthenticationType : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService.AuthenticationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfRequired</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3cf52-104">必須。</span><span class="sxs-lookup"><span data-stu-id="3cf52-104">Required.</span></span> <span data-ttu-id="3cf52-105">SFTP サーバーへの接続に使用する認証の種類。</span><span class="sxs-lookup"><span data-stu-id="3cf52-105">The authentication type to be used to connect to the SFTP server.</span></span> <span data-ttu-id="3cf52-106">基本認証または SshPublicKey 必要があります。</span><span class="sxs-lookup"><span data-stu-id="3cf52-106">Must be Basic or SshPublicKey.</span></span> 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptedCredential">
      <MemberSignature Language="C#" Value="public string EncryptedCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EncryptedCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService.EncryptedCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptedCredential As String" />
      <MemberSignature Language="F#" Value="member this.EncryptedCredential : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService.EncryptedCredential" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3cf52-107">省略可能。</span><span class="sxs-lookup"><span data-stu-id="3cf52-107">Optional.</span></span> <span data-ttu-id="3cf52-108">基本認証または SshPublicKey 認証の暗号化された資格情報です。</span><span class="sxs-lookup"><span data-stu-id="3cf52-108">The encrypted credential for Basic or SshPublicKey authentication.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GatewayName">
      <MemberSignature Language="C#" Value="public string GatewayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GatewayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService.GatewayName" />
      <MemberSignature Language="VB.NET" Value="Public Property GatewayName As String" />
      <MemberSignature Language="F#" Value="member this.GatewayName : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService.GatewayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3cf52-109">省略可能。</span><span class="sxs-lookup"><span data-stu-id="3cf52-109">Optional.</span></span> <span data-ttu-id="3cf52-110">オンプレミス ゲートウェイの名前です。</span><span class="sxs-lookup"><span data-stu-id="3cf52-110">The on-premises gateway name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Host">
      <MemberSignature Language="C#" Value="public string Host { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Host" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService.Host" />
      <MemberSignature Language="VB.NET" Value="Public Property Host As String" />
      <MemberSignature Language="F#" Value="member this.Host : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService.Host" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfRequired</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3cf52-111">必須。</span><span class="sxs-lookup"><span data-stu-id="3cf52-111">Required.</span></span> <span data-ttu-id="3cf52-112">SFTP サーバーのホスト名です。</span><span class="sxs-lookup"><span data-stu-id="3cf52-112">The SFTP server host name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostKeyFingerprint">
      <MemberSignature Language="C#" Value="public string HostKeyFingerprint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HostKeyFingerprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService.HostKeyFingerprint" />
      <MemberSignature Language="VB.NET" Value="Public Property HostKeyFingerprint As String" />
      <MemberSignature Language="F#" Value="member this.HostKeyFingerprint : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService.HostKeyFingerprint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3cf52-113">省略可能。</span><span class="sxs-lookup"><span data-stu-id="3cf52-113">Optional.</span></span> <span data-ttu-id="3cf52-114">ホストは、SFTP サーバーの指紋をキーします。</span><span class="sxs-lookup"><span data-stu-id="3cf52-114">The host key finger-print of the SFTP server.</span></span>
            <span data-ttu-id="3cf52-115">SkipHostKeyValidation が false の場合は、HostKeyFingerprint を指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="3cf52-115">When SkipHostKeyValidation is false, HostKeyFingerprint should be specified.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PassPhrase">
      <MemberSignature Language="C#" Value="public string PassPhrase { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PassPhrase" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService.PassPhrase" />
      <MemberSignature Language="VB.NET" Value="Public Property PassPhrase As String" />
      <MemberSignature Language="F#" Value="member this.PassPhrase : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService.PassPhrase" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3cf52-116">省略可能。</span><span class="sxs-lookup"><span data-stu-id="3cf52-116">Optional.</span></span> <span data-ttu-id="3cf52-117">SSH 秘密キーが暗号化されている場合、SSH 秘密キーの暗号化を解除するパスワードです。</span><span class="sxs-lookup"><span data-stu-id="3cf52-117">The password to decrypt the SSH private key if the SSH private key is encrypted.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3cf52-118">省略可能。</span><span class="sxs-lookup"><span data-stu-id="3cf52-118">Optional.</span></span> <span data-ttu-id="3cf52-119">基本認証用の SFTP サーバーにログオンするパスワードです。</span><span class="sxs-lookup"><span data-stu-id="3cf52-119">Password to logon the SFTP server for Basic authentication.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Port">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Port { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Port" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService.Port" />
      <MemberSignature Language="VB.NET" Value="Public Property Port As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Port : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService.Port" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3cf52-120">省略可能。</span><span class="sxs-lookup"><span data-stu-id="3cf52-120">Optional.</span></span> <span data-ttu-id="3cf52-121">SFTP サーバーがクライアント接続のリッスンに使用する TCP ポート番号。</span><span class="sxs-lookup"><span data-stu-id="3cf52-121">The TCP port number that the SFTP server uses to listen for client connections.</span></span> <span data-ttu-id="3cf52-122">既定値は 22 です。</span><span class="sxs-lookup"><span data-stu-id="3cf52-122">Default value is 22.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrivateKeyContent">
      <MemberSignature Language="C#" Value="public string PrivateKeyContent { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrivateKeyContent" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService.PrivateKeyContent" />
      <MemberSignature Language="VB.NET" Value="Public Property PrivateKeyContent As String" />
      <MemberSignature Language="F#" Value="member this.PrivateKeyContent : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService.PrivateKeyContent" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3cf52-123">省略可能。</span><span class="sxs-lookup"><span data-stu-id="3cf52-123">Optional.</span></span> <span data-ttu-id="3cf52-124">SshPublicKey 認証用の SSH プライベートのキー コンテンツを Base64 にエンコードされます。</span><span class="sxs-lookup"><span data-stu-id="3cf52-124">Base64 encoded SSH private key content for SshPublicKey authentication.</span></span>
            <span data-ttu-id="3cf52-125">SshPublicKey 認証でのコピーを内部設置型、PrivateKeyPath または PrivateKeyContent のいずれかを指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="3cf52-125">For on-premises copy with SshPublicKey authentication, either PrivateKeyPath or PrivateKeyContent should be specified.</span></span>
            <span data-ttu-id="3cf52-126">SSH 秘密キーは、OpenSSH 形式にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="3cf52-126">SSH private key should be OpenSSH format.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrivateKeyPath">
      <MemberSignature Language="C#" Value="public string PrivateKeyPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrivateKeyPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService.PrivateKeyPath" />
      <MemberSignature Language="VB.NET" Value="Public Property PrivateKeyPath As String" />
      <MemberSignature Language="F#" Value="member this.PrivateKeyPath : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService.PrivateKeyPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3cf52-127">省略可能。</span><span class="sxs-lookup"><span data-stu-id="3cf52-127">Optional.</span></span> <span data-ttu-id="3cf52-128">SshPublicKey の認証に SSH 秘密キー ファイルのパス。</span><span class="sxs-lookup"><span data-stu-id="3cf52-128">The SSH private key file path for SshPublicKey authentication.</span></span> <span data-ttu-id="3cf52-129">内部設置型のコピーに対してのみ有効です。</span><span class="sxs-lookup"><span data-stu-id="3cf52-129">Only valid for on-premises copy.</span></span>
            <span data-ttu-id="3cf52-130">SshPublicKey 認証でのコピーを内部設置型、PrivateKeyPath または PrivateKeyContent のいずれかを指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="3cf52-130">For on-premises copy with SshPublicKey authentication, either PrivateKeyPath or PrivateKeyContent should be specified.</span></span>
            <span data-ttu-id="3cf52-131">SSH 秘密キーは、OpenSSH 形式にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="3cf52-131">SSH private key should be OpenSSH format.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SkipHostKeyValidation">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; SkipHostKeyValidation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; SkipHostKeyValidation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService.SkipHostKeyValidation" />
      <MemberSignature Language="VB.NET" Value="Public Property SkipHostKeyValidation As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.SkipHostKeyValidation : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService.SkipHostKeyValidation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3cf52-132">省略可能。</span><span class="sxs-lookup"><span data-stu-id="3cf52-132">Optional.</span></span> <span data-ttu-id="3cf52-133">True の場合は、SSH ホスト キーの検証をスキップします。</span><span class="sxs-lookup"><span data-stu-id="3cf52-133">If true, skip the SSH host key validation.</span></span> <span data-ttu-id="3cf52-134">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="3cf52-134">Default value is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Username">
      <MemberSignature Language="C#" Value="public string Username { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Username" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService.Username" />
      <MemberSignature Language="VB.NET" Value="Public Property Username As String" />
      <MemberSignature Language="F#" Value="member this.Username : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService.Username" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3cf52-135">省略可能。</span><span class="sxs-lookup"><span data-stu-id="3cf52-135">Optional.</span></span> <span data-ttu-id="3cf52-136">SFTP サーバーにログオンするために使用するユーザー名。</span><span class="sxs-lookup"><span data-stu-id="3cf52-136">The username used to log on to the SFTP server.</span></span> <span data-ttu-id="3cf52-137">EncryptedCredential が null の場合、そのことが必要です。</span><span class="sxs-lookup"><span data-stu-id="3cf52-137">It is required when EncryptedCredential is null.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>