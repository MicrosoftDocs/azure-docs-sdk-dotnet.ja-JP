<Type Name="OnPremisesMongoDbLinkedService" FullName="Microsoft.Azure.Management.DataFactories.Models.OnPremisesMongoDbLinkedService">
  <TypeSignature Language="C#" Value="public class OnPremisesMongoDbLinkedService : Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OnPremisesMongoDbLinkedService extends Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.OnPremisesMongoDbLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class OnPremisesMongoDbLinkedService&#xA;Inherits LinkedServiceTypeProperties" />
  <TypeSignature Language="F#" Value="type OnPremisesMongoDbLinkedService = class&#xA;    inherit LinkedServiceTypeProperties" />
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
      <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfTypeName("OnPremisesMongoDb")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="c13d5-101">内部設置型 MongoDB データベースの場合です。</span><span class="sxs-lookup"><span data-stu-id="c13d5-101">An on-premises MongoDB database.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OnPremisesMongoDbLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.OnPremisesMongoDbLinkedService.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c13d5-102"><see cref="T:Microsoft.Azure.Management.DataFactories.Models.OnPremisesMongoDbLinkedService" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c13d5-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.Management.DataFactories.Models.OnPremisesMongoDbLinkedService" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OnPremisesMongoDbLinkedService (string server, string authenticationType, string databaseName, string gatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string server, string authenticationType, string databaseName, string gatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.OnPremisesMongoDbLinkedService.#ctor(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (server As String, authenticationType As String, databaseName As String, gatewayName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Models.OnPremisesMongoDbLinkedService : string * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Models.OnPremisesMongoDbLinkedService" Usage="new Microsoft.Azure.Management.DataFactories.Models.OnPremisesMongoDbLinkedService (server, authenticationType, databaseName, gatewayName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="server" Type="System.String" />
        <Parameter Name="authenticationType" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="server">To be added.</param>
        <param name="authenticationType">To be added.</param>
        <param name="databaseName">To be added.</param>
        <param name="gatewayName">To be added.</param>
        <summary>
            <span data-ttu-id="c13d5-103">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Management.DataFactories.Models.OnPremisesMongoDbLinkedService" />必須の引数を持つクラス。</span><span class="sxs-lookup"><span data-stu-id="c13d5-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.Management.DataFactories.Models.OnPremisesMongoDbLinkedService" /> class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationType">
      <MemberSignature Language="C#" Value="public string AuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.OnPremisesMongoDbLinkedService.AuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationType As String" />
      <MemberSignature Language="F#" Value="member this.AuthenticationType : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.OnPremisesMongoDbLinkedService.AuthenticationType" />
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
            <span data-ttu-id="c13d5-104">必須。</span><span class="sxs-lookup"><span data-stu-id="c13d5-104">Required.</span></span> <span data-ttu-id="c13d5-105">MongoDB データベースへの接続に使用する認証の種類。</span><span class="sxs-lookup"><span data-stu-id="c13d5-105">The authentication type to be used to connect to the MongoDB database.</span></span> <span data-ttu-id="c13d5-106">基本認証または匿名にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="c13d5-106">Must be Basic or Anonymous.</span></span> 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthSource">
      <MemberSignature Language="C#" Value="public string AuthSource { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthSource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.OnPremisesMongoDbLinkedService.AuthSource" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthSource As String" />
      <MemberSignature Language="F#" Value="member this.AuthSource : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.OnPremisesMongoDbLinkedService.AuthSource" />
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
            <span data-ttu-id="c13d5-107">省略可能。</span><span class="sxs-lookup"><span data-stu-id="c13d5-107">Optional.</span></span> <span data-ttu-id="c13d5-108">使用して、資格情報を確認する MongoDB データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="c13d5-108">The name of the MongoDB database that you want to use to check your credentials.</span></span> <span data-ttu-id="c13d5-109">既定値は管理者</span><span class="sxs-lookup"><span data-stu-id="c13d5-109">The default is admin.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseName">
      <MemberSignature Language="C#" Value="public string DatabaseName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DatabaseName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.OnPremisesMongoDbLinkedService.DatabaseName" />
      <MemberSignature Language="VB.NET" Value="Public Property DatabaseName As String" />
      <MemberSignature Language="F#" Value="member this.DatabaseName : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.OnPremisesMongoDbLinkedService.DatabaseName" />
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
            <span data-ttu-id="c13d5-110">必須。</span><span class="sxs-lookup"><span data-stu-id="c13d5-110">Required.</span></span> <span data-ttu-id="c13d5-111">アクセスする MongoDB データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="c13d5-111">The name of the MongoDB database that you want to access.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptedCredential">
      <MemberSignature Language="C#" Value="public string EncryptedCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EncryptedCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.OnPremisesMongoDbLinkedService.EncryptedCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptedCredential As String" />
      <MemberSignature Language="F#" Value="member this.EncryptedCredential : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.OnPremisesMongoDbLinkedService.EncryptedCredential" />
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
            <span data-ttu-id="c13d5-112">省略可能。</span><span class="sxs-lookup"><span data-stu-id="c13d5-112">Optional.</span></span> <span data-ttu-id="c13d5-113">基本認証の暗号化された資格情報です。</span><span class="sxs-lookup"><span data-stu-id="c13d5-113">The encrypted credential for Basic authentication.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GatewayName">
      <MemberSignature Language="C#" Value="public string GatewayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GatewayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.OnPremisesMongoDbLinkedService.GatewayName" />
      <MemberSignature Language="VB.NET" Value="Public Property GatewayName As String" />
      <MemberSignature Language="F#" Value="member this.GatewayName : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.OnPremisesMongoDbLinkedService.GatewayName" />
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
            <span data-ttu-id="c13d5-114">必須。</span><span class="sxs-lookup"><span data-stu-id="c13d5-114">Required.</span></span> <span data-ttu-id="c13d5-115">オンプレミス ゲートウェイの名前です。</span><span class="sxs-lookup"><span data-stu-id="c13d5-115">The on-premises gateway name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.OnPremisesMongoDbLinkedService.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.OnPremisesMongoDbLinkedService.Password" />
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
            <span data-ttu-id="c13d5-116">省略可能。</span><span class="sxs-lookup"><span data-stu-id="c13d5-116">Optional.</span></span> <span data-ttu-id="c13d5-117">基本認証のパスワード。</span><span class="sxs-lookup"><span data-stu-id="c13d5-117">The password for Basic authentication.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Port">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Port { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Port" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.OnPremisesMongoDbLinkedService.Port" />
      <MemberSignature Language="VB.NET" Value="Public Property Port As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Port : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.OnPremisesMongoDbLinkedService.Port" />
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
            <span data-ttu-id="c13d5-118">省略可能。</span><span class="sxs-lookup"><span data-stu-id="c13d5-118">Optional.</span></span> <span data-ttu-id="c13d5-119">MongoDB サーバーがクライアント接続をリッスンするように使用する TCP ポート番号。</span><span class="sxs-lookup"><span data-stu-id="c13d5-119">The TCP port number that the MongoDB server uses to listen for client connections.</span></span> <span data-ttu-id="c13d5-120">既定値は、27017 です。</span><span class="sxs-lookup"><span data-stu-id="c13d5-120">The default value is 27017.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Server">
      <MemberSignature Language="C#" Value="public string Server { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Server" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.OnPremisesMongoDbLinkedService.Server" />
      <MemberSignature Language="VB.NET" Value="Public Property Server As String" />
      <MemberSignature Language="F#" Value="member this.Server : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.OnPremisesMongoDbLinkedService.Server" />
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
            <span data-ttu-id="c13d5-121">必須。</span><span class="sxs-lookup"><span data-stu-id="c13d5-121">Required.</span></span> <span data-ttu-id="c13d5-122">IP アドレスまたは MongoDB サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="c13d5-122">The IP address or name of the MongoDB server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Username">
      <MemberSignature Language="C#" Value="public string Username { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Username" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.OnPremisesMongoDbLinkedService.Username" />
      <MemberSignature Language="VB.NET" Value="Public Property Username As String" />
      <MemberSignature Language="F#" Value="member this.Username : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.OnPremisesMongoDbLinkedService.Username" />
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
            <span data-ttu-id="c13d5-123">省略可能。</span><span class="sxs-lookup"><span data-stu-id="c13d5-123">Optional.</span></span> <span data-ttu-id="c13d5-124">基本認証のユーザー名。</span><span class="sxs-lookup"><span data-stu-id="c13d5-124">The username for Basic authentication.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>