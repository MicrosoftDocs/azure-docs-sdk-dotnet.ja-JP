<Type Name="OnPremisesCassandraLinkedService" FullName="Microsoft.Azure.Management.DataFactories.Models.OnPremisesCassandraLinkedService">
  <TypeSignature Language="C#" Value="public class OnPremisesCassandraLinkedService : Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OnPremisesCassandraLinkedService extends Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.OnPremisesCassandraLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class OnPremisesCassandraLinkedService&#xA;Inherits LinkedServiceTypeProperties" />
  <TypeSignature Language="F#" Value="type OnPremisesCassandraLinkedService = class&#xA;    inherit LinkedServiceTypeProperties" />
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
      <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfTypeName("OnPremisesCassandra")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="a529d-101">内部設置型 Cassandra データベースの場合です。</span><span class="sxs-lookup"><span data-stu-id="a529d-101">An on-premises Cassandra database.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OnPremisesCassandraLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.OnPremisesCassandraLinkedService.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a529d-102"><see cref="T:Microsoft.Azure.Management.DataFactories.Models.OnPremisesCassandraLinkedService" />の新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a529d-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.Management.DataFactories.Models.OnPremisesCassandraLinkedService" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OnPremisesCassandraLinkedService (string host, string authenticationType, string gatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string host, string authenticationType, string gatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.OnPremisesCassandraLinkedService.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (host As String, authenticationType As String, gatewayName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Models.OnPremisesCassandraLinkedService : string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Models.OnPremisesCassandraLinkedService" Usage="new Microsoft.Azure.Management.DataFactories.Models.OnPremisesCassandraLinkedService (host, authenticationType, gatewayName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="host" Type="System.String" />
        <Parameter Name="authenticationType" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="host">To be added.</param>
        <param name="authenticationType">To be added.</param>
        <param name="gatewayName">To be added.</param>
        <summary>
            <span data-ttu-id="a529d-103">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Management.DataFactories.Models.OnPremisesCassandraLinkedService" />必須の引数を持つクラス。</span><span class="sxs-lookup"><span data-stu-id="a529d-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.Management.DataFactories.Models.OnPremisesCassandraLinkedService" /> class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationType">
      <MemberSignature Language="C#" Value="public string AuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.OnPremisesCassandraLinkedService.AuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationType As String" />
      <MemberSignature Language="F#" Value="member this.AuthenticationType : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.OnPremisesCassandraLinkedService.AuthenticationType" />
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
            <span data-ttu-id="a529d-104">必須。</span><span class="sxs-lookup"><span data-stu-id="a529d-104">Required.</span></span> <span data-ttu-id="a529d-105">Cassandra データベースへの接続に使用する認証の種類。</span><span class="sxs-lookup"><span data-stu-id="a529d-105">The authentication type to be used to connect to the Cassandra database.</span></span> <span data-ttu-id="a529d-106">基本認証または匿名にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="a529d-106">Must be Basic or Anonymous.</span></span> 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptedCredential">
      <MemberSignature Language="C#" Value="public string EncryptedCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EncryptedCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.OnPremisesCassandraLinkedService.EncryptedCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptedCredential As String" />
      <MemberSignature Language="F#" Value="member this.EncryptedCredential : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.OnPremisesCassandraLinkedService.EncryptedCredential" />
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
            <span data-ttu-id="a529d-107">省略可能。</span><span class="sxs-lookup"><span data-stu-id="a529d-107">Optional.</span></span> <span data-ttu-id="a529d-108">基本認証の暗号化された資格情報です。</span><span class="sxs-lookup"><span data-stu-id="a529d-108">The encrypted credential for Basic authentication.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GatewayName">
      <MemberSignature Language="C#" Value="public string GatewayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GatewayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.OnPremisesCassandraLinkedService.GatewayName" />
      <MemberSignature Language="VB.NET" Value="Public Property GatewayName As String" />
      <MemberSignature Language="F#" Value="member this.GatewayName : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.OnPremisesCassandraLinkedService.GatewayName" />
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
            <span data-ttu-id="a529d-109">必須。</span><span class="sxs-lookup"><span data-stu-id="a529d-109">Required.</span></span> <span data-ttu-id="a529d-110">オンプレミス ゲートウェイの名前です。</span><span class="sxs-lookup"><span data-stu-id="a529d-110">The on-premises gateway name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Host">
      <MemberSignature Language="C#" Value="public string Host { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Host" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.OnPremisesCassandraLinkedService.Host" />
      <MemberSignature Language="VB.NET" Value="Public Property Host As String" />
      <MemberSignature Language="F#" Value="member this.Host : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.OnPremisesCassandraLinkedService.Host" />
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
            <span data-ttu-id="a529d-111">必須。</span><span class="sxs-lookup"><span data-stu-id="a529d-111">Required.</span></span> <span data-ttu-id="a529d-112">1 つ以上の IP アドレスまたは Cassandra サーバーのホスト名です。</span><span class="sxs-lookup"><span data-stu-id="a529d-112">One or more IP addresses or host names of the Cassandra server.</span></span>
            <span data-ttu-id="a529d-113">複数のサーバーに接続する場合は、IP アドレスまたはホスト名のコンマ区切りのリストを指定します。</span><span class="sxs-lookup"><span data-stu-id="a529d-113">Specify a comma-separated list of IP addresses and/or host names if attempting to connect to multiple servers.</span></span>
            <span data-ttu-id="a529d-114">各サーバーは、レプリカです。</span><span class="sxs-lookup"><span data-stu-id="a529d-114">Each server is a replica.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.OnPremisesCassandraLinkedService.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.OnPremisesCassandraLinkedService.Password" />
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
            <span data-ttu-id="a529d-115">省略可能。</span><span class="sxs-lookup"><span data-stu-id="a529d-115">Optional.</span></span> <span data-ttu-id="a529d-116">基本認証のパスワード。</span><span class="sxs-lookup"><span data-stu-id="a529d-116">The password for Basic authentication.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Port">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Port { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Port" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.OnPremisesCassandraLinkedService.Port" />
      <MemberSignature Language="VB.NET" Value="Public Property Port As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Port : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.OnPremisesCassandraLinkedService.Port" />
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
            <span data-ttu-id="a529d-117">省略可能。</span><span class="sxs-lookup"><span data-stu-id="a529d-117">Optional.</span></span> <span data-ttu-id="a529d-118">Cassandra サーバーがクライアント接続をリッスンするように使用する TCP ポート番号。</span><span class="sxs-lookup"><span data-stu-id="a529d-118">The TCP port number that the Cassandra server uses to listen for client connections.</span></span> <span data-ttu-id="a529d-119">既定値は、9042 です。</span><span class="sxs-lookup"><span data-stu-id="a529d-119">The default value is 9042.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Username">
      <MemberSignature Language="C#" Value="public string Username { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Username" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.OnPremisesCassandraLinkedService.Username" />
      <MemberSignature Language="VB.NET" Value="Public Property Username As String" />
      <MemberSignature Language="F#" Value="member this.Username : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.OnPremisesCassandraLinkedService.Username" />
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
            <span data-ttu-id="a529d-120">省略可能。</span><span class="sxs-lookup"><span data-stu-id="a529d-120">Optional.</span></span> <span data-ttu-id="a529d-121">基本認証のユーザー名。</span><span class="sxs-lookup"><span data-stu-id="a529d-121">The username for Basic authentication.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>