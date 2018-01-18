<Type Name="ShardLocation" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation">
  <TypeSignature Language="C#" Value="public sealed class ShardLocation : IEquatable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit ShardLocation extends System.Object implements class System.IEquatable`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ShardLocation&#xA;Implements IEquatable(Of ShardLocation)" />
  <TypeSignature Language="F#" Value="type ShardLocation = class&#xA;    interface IEquatable&lt;ShardLocation&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
    <AssemblyVersion>1.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IEquatable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="83bdd-101">そのサーバー名とデータベース名の観点から、シャードの場所を表します。</span><span class="sxs-lookup"><span data-stu-id="83bdd-101">Represents the location of a shard in terms of its server name and database name.</span></span> <span data-ttu-id="83bdd-102">シャードへの接続を管理し、シャードの他の操作をサポートするために使用されます。</span><span class="sxs-lookup"><span data-stu-id="83bdd-102">This is used to manage connections to the shard and to support other operations on shards.</span></span>
            <span data-ttu-id="83bdd-103">なく、<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard" />シャードの場所が、シャード マップに登録されていません。</span><span class="sxs-lookup"><span data-stu-id="83bdd-103">As opposed to a <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard" />, a shard location is not registered with the shard map.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ShardLocation (string server, string database);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string server, string database) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (server As String, database As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation : string * string -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation (server, database)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="server" Type="System.String" />
        <Parameter Name="database" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="server"><span data-ttu-id="83bdd-104">シャードのデータベース サーバーの完全修飾ホスト名です。</span><span class="sxs-lookup"><span data-stu-id="83bdd-104">Fully qualified hostname of the server for the shard database.</span></span></param>
        <param name="database"><span data-ttu-id="83bdd-105">シャードのデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="83bdd-105">Name of the shard database.</span></span></param>
        <summary>
            <span data-ttu-id="83bdd-106">アドレスと、シャードを識別するデータベースの指定を許可するコンス トラクターです。</span><span class="sxs-lookup"><span data-stu-id="83bdd-106">Constructor that allows specification of address and database to identify a shard.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ShardLocation (string server, string database, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.SqlProtocol protocol);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string server, string database, valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.SqlProtocol protocol) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation.#ctor(System.String,System.String,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.SqlProtocol)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (server As String, database As String, protocol As SqlProtocol)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation : string * string * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.SqlProtocol -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation (server, database, protocol)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="server" Type="System.String" />
        <Parameter Name="database" Type="System.String" />
        <Parameter Name="protocol" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.SqlProtocol" />
      </Parameters>
      <Docs>
        <param name="server"><span data-ttu-id="83bdd-107">シャードのデータベース サーバーの完全修飾ホスト名です。</span><span class="sxs-lookup"><span data-stu-id="83bdd-107">Fully qualified hostname of the server for the shard database.</span></span></param>
        <param name="database"><span data-ttu-id="83bdd-108">シャードのデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="83bdd-108">Name of the shard database.</span></span></param>
        <param name="protocol"><span data-ttu-id="83bdd-109">接続に使用するプロトコルを転送します。</span><span class="sxs-lookup"><span data-stu-id="83bdd-109">Transport protcol used for the connection.</span></span></param>
        <summary>
            <span data-ttu-id="83bdd-110">アドレスと、シャードを識別するデータベースの指定を許可するコンス トラクターです。</span><span class="sxs-lookup"><span data-stu-id="83bdd-110">Constructor that allows specification of address and database to identify a shard.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ShardLocation (string server, string database, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.SqlProtocol protocol, int port);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string server, string database, valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.SqlProtocol protocol, int32 port) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation.#ctor(System.String,System.String,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.SqlProtocol,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (server As String, database As String, protocol As SqlProtocol, port As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation : string * string * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.SqlProtocol * int -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation (server, database, protocol, port)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="server" Type="System.String" />
        <Parameter Name="database" Type="System.String" />
        <Parameter Name="protocol" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.SqlProtocol" />
        <Parameter Name="port" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="server"><span data-ttu-id="83bdd-111">シャードのデータベース サーバーの完全修飾ホスト名です。</span><span class="sxs-lookup"><span data-stu-id="83bdd-111">Fully qualified hostname of the server for the shard database.</span></span></param>
        <param name="database"><span data-ttu-id="83bdd-112">シャードのデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="83bdd-112">Name of the shard database.</span></span></param>
        <param name="protocol"><span data-ttu-id="83bdd-113">接続に使用するプロトコルを転送します。</span><span class="sxs-lookup"><span data-stu-id="83bdd-113">Transport protcol used for the connection.</span></span></param>
        <param name="port"><span data-ttu-id="83bdd-114">TCP/IP 接続のポート番号。</span><span class="sxs-lookup"><span data-stu-id="83bdd-114">Port number for TCP/IP connections.</span></span> <span data-ttu-id="83bdd-115">指定された既定のポートを使用する場合は 0 を指定<paramref name="protocol" />です。</span><span class="sxs-lookup"><span data-stu-id="83bdd-115">Specify 0 to use the default port for the specified <paramref name="protocol" />.</span></span></param>
        <summary>
            <span data-ttu-id="83bdd-116">プロトコル、アドレス、ポート、およびシャードを識別するデータベースの指定を許可するコンス トラクターです。</span><span class="sxs-lookup"><span data-stu-id="83bdd-116">Constructor that allows specification of protocol, address, port and database to identify a shard.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Database">
      <MemberSignature Language="C#" Value="public string Database { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Database" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation.Database" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Database As String" />
      <MemberSignature Language="F#" Value="member this.Database : string" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation.Database" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="83bdd-117">シャードのデータベース名を取得します。</span><span class="sxs-lookup"><span data-stu-id="83bdd-117">Gets the database name of the shard.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataSource">
      <MemberSignature Language="C#" Value="public string DataSource { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DataSource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation.DataSource" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DataSource As String" />
      <MemberSignature Language="F#" Value="member this.DataSource : string" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation.DataSource" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="83bdd-118">データ ソース プロパティの接続文字列を構築するために使用できるデータ ソース名。</span><span class="sxs-lookup"><span data-stu-id="83bdd-118">DataSource name which can be used to construct connection string Data Source property.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation.Equals(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As ShardLocation) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation -&gt; bool" Usage="shardLocation.Equals other" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IEquatable`1.Equals(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" />
      </Parameters>
      <Docs>
        <param name="other"><span data-ttu-id="83bdd-119">比較する ShardLocation です。</span><span class="sxs-lookup"><span data-stu-id="83bdd-119">ShardLocation to compare with.</span></span></param>
        <summary>
            <span data-ttu-id="83bdd-120">他の等値比較を実行 ShardLocation を指定します。</span><span class="sxs-lookup"><span data-stu-id="83bdd-120">Performs equality comparison with another given ShardLocation.</span></span>
            </summary>
        <returns><span data-ttu-id="83bdd-121">True の場合は、同じ場所、false それ以外の場合。</span><span class="sxs-lookup"><span data-stu-id="83bdd-121">True if same locations, false otherwise.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="shardLocation.Equals obj" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="obj"><span data-ttu-id="83bdd-122">現在のオブジェクトと比較するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="83bdd-122">The object to compare with the current object.</span></span></param>
        <summary>
            <span data-ttu-id="83bdd-123">指定したオブジェクトが、現在のオブジェクトと等しいかどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="83bdd-123">Determines whether the specified object is equal to the current object.</span></span>
            </summary>
        <returns><span data-ttu-id="83bdd-124">指定したオブジェクトが現在のオブジェクトと等しい場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="83bdd-124">True if the specified object is equal to the current object; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="shardLocation.GetHashCode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="83bdd-125">このインスタンスのハッシュ コードを計算します。</span><span class="sxs-lookup"><span data-stu-id="83bdd-125">Calculates the hash code for this instance.</span></span>
            </summary>
        <returns><span data-ttu-id="83bdd-126">オブジェクトのハッシュ コード。</span><span class="sxs-lookup"><span data-stu-id="83bdd-126">Hash code for the object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Port">
      <MemberSignature Language="C#" Value="public int Port { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Port" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation.Port" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Port As Integer" />
      <MemberSignature Language="F#" Value="member this.Port : int" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation.Port" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="83bdd-127">TCP/IP プロトコルの通信ポート。</span><span class="sxs-lookup"><span data-stu-id="83bdd-127">Communication port for TCP/IP protocol.</span></span> <span data-ttu-id="83bdd-128">ポートが指定されていない場合は、0 を返します。</span><span class="sxs-lookup"><span data-stu-id="83bdd-128">If no port is specified, the property returns 0.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Protocol">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.SqlProtocol Protocol { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.SqlProtocol Protocol" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation.Protocol" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Protocol As SqlProtocol" />
      <MemberSignature Language="F#" Value="member this.Protocol : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.SqlProtocol" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation.Protocol" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.SqlProtocol</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="83bdd-129">プロトコルの名前プレフィックスです。</span><span class="sxs-lookup"><span data-stu-id="83bdd-129">Protocol name prefix.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Server">
      <MemberSignature Language="C#" Value="public string Server { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Server" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation.Server" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Server As String" />
      <MemberSignature Language="F#" Value="member this.Server : string" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation.Server" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="83bdd-130">シャードのデータベースのサーバーの完全修飾ホスト名を取得します。</span><span class="sxs-lookup"><span data-stu-id="83bdd-130">Gets the fully qualified hostname of the server for the shard database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="shardLocation.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="83bdd-131">シャードの場所をその文字列形式に変換します。</span><span class="sxs-lookup"><span data-stu-id="83bdd-131">Converts the shard location to its string representation.</span></span>
            </summary>
        <returns><span data-ttu-id="83bdd-132">シャードの場所の文字列表現。</span><span class="sxs-lookup"><span data-stu-id="83bdd-132">String representation of shard location.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>