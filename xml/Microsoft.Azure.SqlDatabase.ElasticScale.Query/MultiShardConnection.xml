<Type Name="MultiShardConnection" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardConnection">
  <TypeSignature Language="C#" Value="public sealed class MultiShardConnection : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit MultiShardConnection extends System.Object implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardConnection" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class MultiShardConnection&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type MultiShardConnection = class&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
    <AssemblyVersion>1.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Naming", "CA1704:IdentifiersShouldBeSpelledCorrectly", MessageId="Multi")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="f0842-101">シャードのセットへの接続を表し、シャード セット全体に対してクエリを処理する機能を提供します。</span><span class="sxs-lookup"><span data-stu-id="f0842-101">Represents a connection to a set of shards and provides the ability to process queries across the shard set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiShardConnection (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard&gt; shards, string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard&gt; shards, string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardConnection.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (shards As IEnumerable(Of Shard), connectionString As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardConnection : seq&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard&gt; * string -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardConnection" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardConnection (shards, connectionString)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="shards" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard&gt;" />
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="shards"><span data-ttu-id="f0842-102">コレクション<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard" />s のこの接続のインスタンスを使用します。</span><span class="sxs-lookup"><span data-stu-id="f0842-102">The collection of <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard" />s used for this connection instances.</span></span></param>
        <param name="connectionString">
            <span data-ttu-id="f0842-103">これらの資格情報への接続に使用される、 <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard" />s。</span><span class="sxs-lookup"><span data-stu-id="f0842-103">These credentials will be used to connect to the <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard" />s.</span></span> <span data-ttu-id="f0842-104">同じ資格情報は、すべてのシャードで使用されます。</span><span class="sxs-lookup"><span data-stu-id="f0842-104">The same credentials are used on all shards.</span></span> <span data-ttu-id="f0842-105">そのため、すべてのシャードは、コマンドの実行にこれらの資格情報の適切なアクセス許可を提供する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f0842-105">Therefore, all shards need to provide the appropriate permissions for these credentials to execute the command.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f0842-106"><see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardConnection" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f0842-106">Initializes a new instance of the <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardConnection" /> class.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="f0842-107">複数のアクティブな結果セット (MARS) はサポートされていませんし、シャードの処理には無効になります。</span><span class="sxs-lookup"><span data-stu-id="f0842-107">Multiple Active Result Sets (MARS) are not supported and are disabled for any processing at the shards.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiShardConnection (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; shardLocations, string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; shardLocations, string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardConnection.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (shardLocations As IEnumerable(Of ShardLocation), connectionString As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardConnection : seq&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; * string -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardConnection" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardConnection (shardLocations, connectionString)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="shardLocations" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt;" />
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="shardLocations"><span data-ttu-id="f0842-108">コレクション<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" />s のこの接続のインスタンスを使用します。</span><span class="sxs-lookup"><span data-stu-id="f0842-108">The collection of <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" />s used for this connection instances.</span></span></param>
        <param name="connectionString">
            <span data-ttu-id="f0842-109">これらの資格情報への接続に使用される、 <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard" />s。</span><span class="sxs-lookup"><span data-stu-id="f0842-109">These credentials will be used to connect to the <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard" />s.</span></span> <span data-ttu-id="f0842-110">同じ資格情報は、すべてのシャードで使用されます。</span><span class="sxs-lookup"><span data-stu-id="f0842-110">The same credentials are used on all shards.</span></span> <span data-ttu-id="f0842-111">そのため、すべてのシャードは、コマンドの実行にこれらの資格情報の適切なアクセス許可を提供する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f0842-111">Therefore, all shards need to provide the appropriate permissions for these credentials to execute the command.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f0842-112"><see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardConnection" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f0842-112">Initializes a new instance of the <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardConnection" /> class.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="f0842-113">複数のアクティブな結果セット (MARS) はサポートされていませんし、シャードの処理には無効になります。</span><span class="sxs-lookup"><span data-stu-id="f0842-113">Multiple Active Result Sets (MARS) are not supported and are disabled for any processing at the shards.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateCommand">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand CreateCommand ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand CreateCommand() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardConnection.CreateCommand" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateCommand () As MultiShardCommand" />
      <MemberSignature Language="F#" Value="member this.CreateCommand : unit -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand" Usage="multiShardConnection.CreateCommand " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f0842-114">作成して返します、<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f0842-114">Creates and returns a <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand" /> object.</span></span> <span data-ttu-id="f0842-115"><see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand" />オブジェクトは、接続で指定されたすべてのシャードに対してコマンドを実行し、使用できます。</span><span class="sxs-lookup"><span data-stu-id="f0842-115">The <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand" /> object can then be used to execute a command against all shards specified in the connection.</span></span>
            </summary>
        <returns><span data-ttu-id="f0842-116"><see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand" />で<see cref="P:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.CommandText" />を null に設定します。</span><span class="sxs-lookup"><span data-stu-id="f0842-116">the <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand" /> with <see cref="P:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.CommandText" /> set to null.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardConnection.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="multiShardConnection.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f0842-117">このオブジェクトによって使用されているすべてのリソースを解放します。</span><span class="sxs-lookup"><span data-stu-id="f0842-117">Releases all resources used by this object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ShardLocations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; ShardLocations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; ShardLocations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardConnection.ShardLocations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ShardLocations As IEnumerable(Of ShardLocation)" />
      <MemberSignature Language="F#" Value="member this.ShardLocations : seq&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt;" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardConnection.ShardLocations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f0842-118">コレクションを取得<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" />この接続に関連付けられています。</span><span class="sxs-lookup"><span data-stu-id="f0842-118">Gets the collection of <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" />s associated with this connection.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Shards">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard&gt; Shards { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard&gt; Shards" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardConnection.Shards" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Shards As IEnumerable(Of Shard)" />
      <MemberSignature Language="F#" Value="member this.Shards : seq&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard&gt;" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardConnection.Shards" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f0842-119">コレクションを取得<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard" />この接続に関連付けられています。</span><span class="sxs-lookup"><span data-stu-id="f0842-119">Gets the collection of <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard" />s associated with this connection.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>