<Type Name="Shard" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard">
  <TypeSignature Language="C#" Value="public sealed class Shard : IEquatable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit Shard extends System.Object implements class System.IEquatable`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class Shard&#xA;Implements IEquatable(Of Shard)" />
  <TypeSignature Language="F#" Value="type Shard = class&#xA;    interface IShardProvider&lt;ShardLocation&gt;&#xA;    interface IShardProvider&#xA;    interface ICloneable&lt;Shard&gt;&#xA;    interface IEquatable&lt;Shard&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
    <AssemblyVersion>1.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IEquatable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="49552-101">単一のシャードの表現。</span><span class="sxs-lookup"><span data-stu-id="49552-101">Representation of a single shard.</span></span> <span data-ttu-id="49552-102">シャードは、基本的にデータ ソース ロケーターつまり<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" />シャードのマップに登録されています。</span><span class="sxs-lookup"><span data-stu-id="49552-102">Shards are basically locators for data sources i.e. <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" />s that have been registered with a shard map.</span></span> <span data-ttu-id="49552-103">シャードは、マッピングのターゲットとしてマッピングで使用されます (を参照してください<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1" />と<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1" />)。</span><span class="sxs-lookup"><span data-stu-id="49552-103">Shards are used in mapping as targets of mappings (see <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1" /> and <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1" />).</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Function Clone () As Shard" />
      <MemberSignature Language="F#" Value="abstract member Clone : unit -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard&#xA;override this.Clone : unit -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard" Usage="shard.Clone " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ICloneable`1.Clone</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="49552-104">インスタンスを複製します。</span><span class="sxs-lookup"><span data-stu-id="49552-104">Clones the instance.</span></span>
            </summary>
        <returns><span data-ttu-id="49552-105">インスタンスのクローンを作成します。</span><span class="sxs-lookup"><span data-stu-id="49552-105">Clone of the instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard.Equals(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As Shard) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard -&gt; bool" Usage="shard.Equals other" />
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
        <Parameter Name="other" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard" />
      </Parameters>
      <Docs>
        <param name="other"><span data-ttu-id="49552-106">比較するシャードです。</span><span class="sxs-lookup"><span data-stu-id="49552-106">Shard to compare with.</span></span></param>
        <summary>
            <span data-ttu-id="49552-107">等値比較を実行のシャードを指定します。</span><span class="sxs-lookup"><span data-stu-id="49552-107">Performs equality comparison with given Shard.</span></span>
            </summary>
        <returns><span data-ttu-id="49552-108">このオブジェクトは、それ以外の場合は false、他のオブジェクトと等しい場合は true。</span><span class="sxs-lookup"><span data-stu-id="49552-108">True if this object is equal to other object, false otherwise.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="shard.Equals obj" />
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
        <param name="obj"><span data-ttu-id="49552-109">現在のオブジェクトと比較するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="49552-109">The object to compare with the current object.</span></span></param>
        <summary>
            <span data-ttu-id="49552-110">指定したオブジェクトが、現在のオブジェクトと等しいかどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="49552-110">Determines whether the specified object is equal to the current object.</span></span>
            </summary>
        <returns><span data-ttu-id="49552-111">指定したオブジェクトが現在のオブジェクトと等しい場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="49552-111">True if the specified object is equal to the current object; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="shard.GetHashCode " />
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
            <span data-ttu-id="49552-112">このインスタンスのハッシュ コードを計算します。</span><span class="sxs-lookup"><span data-stu-id="49552-112">Calculates the hash code for this instance.</span></span>
            </summary>
        <returns><span data-ttu-id="49552-113">オブジェクトのハッシュ コード。</span><span class="sxs-lookup"><span data-stu-id="49552-113">Hash code for the object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation Location { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard.Location" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Location As ShardLocation" />
      <MemberSignature Language="F#" Value="member this.Location : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="49552-114">シャードの場所を取得します。</span><span class="sxs-lookup"><span data-stu-id="49552-114">Gets Location of the shard.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenConnection">
      <MemberSignature Language="C#" Value="public System.Data.SqlClient.SqlConnection OpenConnection (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Data.SqlClient.SqlConnection OpenConnection(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard.OpenConnection(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function OpenConnection (connectionString As String) As SqlConnection" />
      <MemberSignature Language="F#" Value="member this.OpenConnection : string -&gt; System.Data.SqlClient.SqlConnection" Usage="shard.OpenConnection connectionString" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Data.SqlClient.SqlConnection</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString">
            <span data-ttu-id="49552-115">SQL Server 資格情報または統合セキュリティの設定などの資格情報で接続文字列です。</span><span class="sxs-lookup"><span data-stu-id="49552-115">Connection string with credential information such as SQL Server credentials or Integrated Security settings.</span></span> <span data-ttu-id="49552-116">サーバーと、データベース、シャードの名前のホスト名は、キーの参照操作から取得されます。</span><span class="sxs-lookup"><span data-stu-id="49552-116">The hostname of the server and the database name for the shard are obtained from the lookup operation for key.</span></span>
            </param>
        <summary>
            <span data-ttu-id="49552-117">開き、通常<see cref="T:System.Data.SqlClient.SqlConnection" />指定のシャードと<see cref="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions.Validate" />です。</span><span class="sxs-lookup"><span data-stu-id="49552-117">Opens a regular <see cref="T:System.Data.SqlClient.SqlConnection" /> to the specified shard, with <see cref="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions.Validate" />.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="49552-118">なお、<see cref="T:System.Data.SqlClient.SqlConnection" />この呼び出しによって返されるオブジェクトが一時的なエラーから保護されていません。</span><span class="sxs-lookup"><span data-stu-id="49552-118">Note that the <see cref="T:System.Data.SqlClient.SqlConnection" /> object returned by this call is not protected against transient faults.</span></span> <span data-ttu-id="49552-119">呼び出し元は、transient fault handling Microsoft Patterns and Practices チームからの Enterprise Library の機能を使用して、アプリケーション コードで、たとえば、一時的なエラーへの接続を保護するベスト プラクティスに従う必要があります。</span><span class="sxs-lookup"><span data-stu-id="49552-119">Callers should follow best practices to protect the connection against transient faults in their application code, e.g., by using the transient fault handling functionality in the Enterprise Library from Microsoft Patterns and Practices team.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenConnection">
      <MemberSignature Language="C#" Value="public System.Data.SqlClient.SqlConnection OpenConnection (string connectionString, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Data.SqlClient.SqlConnection OpenConnection(string connectionString, valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard.OpenConnection(System.String,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function OpenConnection (connectionString As String, options As ConnectionOptions) As SqlConnection" />
      <MemberSignature Language="F#" Value="member this.OpenConnection : string * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions -&gt; System.Data.SqlClient.SqlConnection" Usage="shard.OpenConnection (connectionString, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Data.SqlClient.SqlConnection</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions" />
      </Parameters>
      <Docs>
        <param name="connectionString">
            <span data-ttu-id="49552-120">SQL Server 資格情報または統合セキュリティの設定などの資格情報で接続文字列です。</span><span class="sxs-lookup"><span data-stu-id="49552-120">Connection string with credential information such as SQL Server credentials or Integrated Security settings.</span></span> <span data-ttu-id="49552-121">サーバーと、データベース、シャードの名前のホスト名は、キーの参照操作から取得されます。</span><span class="sxs-lookup"><span data-stu-id="49552-121">The hostname of the server and the database name for the shard are obtained from the lookup operation for key.</span></span>
            </param>
        <param name="options"><span data-ttu-id="49552-122">検証操作で実行するためのオプションには、接続が開かれます。</span><span class="sxs-lookup"><span data-stu-id="49552-122">Options for validation operations to perform on opened connection.</span></span></param>
        <summary>
            <span data-ttu-id="49552-123">開き、通常<see cref="T:System.Data.SqlClient.SqlConnection" />指定のシャードにします。</span><span class="sxs-lookup"><span data-stu-id="49552-123">Opens a regular <see cref="T:System.Data.SqlClient.SqlConnection" /> to the specified shard.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="49552-124">なお、<see cref="T:System.Data.SqlClient.SqlConnection" />この呼び出しによって返されるオブジェクトが一時的なエラーから保護されていません。</span><span class="sxs-lookup"><span data-stu-id="49552-124">Note that the <see cref="T:System.Data.SqlClient.SqlConnection" /> object returned by this call is not protected against transient faults.</span></span> <span data-ttu-id="49552-125">呼び出し元は、transient fault handling Microsoft Patterns and Practices チームからの Enterprise Library の機能を使用して、アプリケーション コードで、たとえば、一時的なエラーへの接続を保護するベスト プラクティスに従う必要があります。</span><span class="sxs-lookup"><span data-stu-id="49552-125">Callers should follow best practices to protect the connection against transient faults in their application code, e.g., by using the transient fault handling functionality in the Enterprise Library from Microsoft Patterns and Practices team.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenConnectionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Data.SqlClient.SqlConnection&gt; OpenConnectionAsync (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Data.SqlClient.SqlConnection&gt; OpenConnectionAsync(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard.OpenConnectionAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function OpenConnectionAsync (connectionString As String) As Task(Of SqlConnection)" />
      <MemberSignature Language="F#" Value="member this.OpenConnectionAsync : string -&gt; System.Threading.Tasks.Task&lt;System.Data.SqlClient.SqlConnection&gt;" Usage="shard.OpenConnectionAsync connectionString" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Data.SqlClient.SqlConnection&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString">
            <span data-ttu-id="49552-126">SQL Server 資格情報または統合セキュリティの設定などの資格情報で接続文字列です。</span><span class="sxs-lookup"><span data-stu-id="49552-126">Connection string with credential information such as SQL Server credentials or Integrated Security settings.</span></span> <span data-ttu-id="49552-127">サーバーと、データベース、シャードの名前のホスト名は、キーの参照操作から取得されます。</span><span class="sxs-lookup"><span data-stu-id="49552-127">The hostname of the server and the database name for the shard are obtained from the lookup operation for key.</span></span>
            </param>
        <summary>
            <span data-ttu-id="49552-128">非同期的に開き、通常<see cref="T:System.Data.SqlClient.SqlConnection" />指定のシャードと<see cref="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions.Validate" />です。</span><span class="sxs-lookup"><span data-stu-id="49552-128">Asynchronously opens a regular <see cref="T:System.Data.SqlClient.SqlConnection" /> to the specified shard, with <see cref="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions.Validate" />.</span></span>
            </summary>
        <returns><span data-ttu-id="49552-129">開かれた SqlConnection をカプセル化タスク</span><span class="sxs-lookup"><span data-stu-id="49552-129">A Task encapsulating an opened SqlConnection</span></span></returns>
        <remarks>
            <span data-ttu-id="49552-130">なお、<see cref="T:System.Data.SqlClient.SqlConnection" />この呼び出しによって返されるオブジェクトが一時的なエラーから保護されていません。</span><span class="sxs-lookup"><span data-stu-id="49552-130">Note that the <see cref="T:System.Data.SqlClient.SqlConnection" /> object returned by this call is not protected against transient faults.</span></span> <span data-ttu-id="49552-131">呼び出し元は、transient fault handling Microsoft Patterns and Practices チームからの Enterprise Library の機能を使用して、アプリケーション コードで、たとえば、一時的なエラーへの接続を保護するベスト プラクティスに従う必要があります。</span><span class="sxs-lookup"><span data-stu-id="49552-131">Callers should follow best practices to protect the connection against transient faults in their application code, e.g., by using the transient fault handling functionality in the Enterprise Library from Microsoft Patterns and Practices team.</span></span>
            <span data-ttu-id="49552-132">使用状況以外のすべてのエラーは返されたタスクによって伝達されます。</span><span class="sxs-lookup"><span data-stu-id="49552-132">All non-usage errors will be propagated via the returned Task.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenConnectionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Data.SqlClient.SqlConnection&gt; OpenConnectionAsync (string connectionString, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Data.SqlClient.SqlConnection&gt; OpenConnectionAsync(string connectionString, valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard.OpenConnectionAsync(System.String,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function OpenConnectionAsync (connectionString As String, options As ConnectionOptions) As Task(Of SqlConnection)" />
      <MemberSignature Language="F#" Value="member this.OpenConnectionAsync : string * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions -&gt; System.Threading.Tasks.Task&lt;System.Data.SqlClient.SqlConnection&gt;" Usage="shard.OpenConnectionAsync (connectionString, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Data.SqlClient.SqlConnection&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions" />
      </Parameters>
      <Docs>
        <param name="connectionString">
            <span data-ttu-id="49552-133">SQL Server 資格情報または統合セキュリティの設定などの資格情報で接続文字列です。</span><span class="sxs-lookup"><span data-stu-id="49552-133">Connection string with credential information such as SQL Server credentials or Integrated Security settings.</span></span> <span data-ttu-id="49552-134">サーバーと、データベース、シャードの名前のホスト名は、キーの参照操作から取得されます。</span><span class="sxs-lookup"><span data-stu-id="49552-134">The hostname of the server and the database name for the shard are obtained from the lookup operation for key.</span></span>
            </param>
        <param name="options"><span data-ttu-id="49552-135">検証操作で実行するためのオプションには、接続が開かれます。</span><span class="sxs-lookup"><span data-stu-id="49552-135">Options for validation operations to perform on opened connection.</span></span></param>
        <summary>
            <span data-ttu-id="49552-136">非同期的に、通常<see cref="T:System.Data.SqlClient.SqlConnection" />指定のシャードにします。</span><span class="sxs-lookup"><span data-stu-id="49552-136">Asynchronously a regular <see cref="T:System.Data.SqlClient.SqlConnection" /> to the specified shard.</span></span>
            </summary>
        <returns><span data-ttu-id="49552-137">開かれた SqlConnection をカプセル化タスク</span><span class="sxs-lookup"><span data-stu-id="49552-137">A Task encapsulating an opened SqlConnection</span></span></returns>
        <remarks>
            <span data-ttu-id="49552-138">なお、<see cref="T:System.Data.SqlClient.SqlConnection" />この呼び出しによって返されるオブジェクトが一時的なエラーから保護されていません。</span><span class="sxs-lookup"><span data-stu-id="49552-138">Note that the <see cref="T:System.Data.SqlClient.SqlConnection" /> object returned by this call is not protected against transient faults.</span></span> <span data-ttu-id="49552-139">呼び出し元は、transient fault handling Microsoft Patterns and Practices チームからの Enterprise Library の機能を使用して、アプリケーション コードで、たとえば、一時的なエラーへの接続を保護するベスト プラクティスに従う必要があります。</span><span class="sxs-lookup"><span data-stu-id="49552-139">Callers should follow best practices to protect the connection against transient faults in their application code, e.g., by using the transient fault handling functionality in the Enterprise Library from Microsoft Patterns and Practices team.</span></span>
            <span data-ttu-id="49552-140">使用状況以外のすべてのエラーは返されたタスクによって伝達されます。</span><span class="sxs-lookup"><span data-stu-id="49552-140">All non-usage errors will be propagated via the returned Task.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="shard.ToString " />
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
            <span data-ttu-id="49552-141">オブジェクトを文字列形式に変換します。</span><span class="sxs-lookup"><span data-stu-id="49552-141">Converts the object to its string representation.</span></span>
            </summary>
        <returns><span data-ttu-id="49552-142">オブジェクトの文字列表現。</span><span class="sxs-lookup"><span data-stu-id="49552-142">String representation of the object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>