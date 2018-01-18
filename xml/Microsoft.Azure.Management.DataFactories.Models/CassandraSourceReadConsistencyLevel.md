<Type Name="CassandraSourceReadConsistencyLevel" FullName="Microsoft.Azure.Management.DataFactories.Models.CassandraSourceReadConsistencyLevel">
  <TypeSignature Language="C#" Value="public static class CassandraSourceReadConsistencyLevel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit CassandraSourceReadConsistencyLevel extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.CassandraSourceReadConsistencyLevel" />
  <TypeSignature Language="VB.NET" Value="Public Class CassandraSourceReadConsistencyLevel" />
  <TypeSignature Language="F#" Value="type CassandraSourceReadConsistencyLevel = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="936ef-101">一貫性レベル Cassandra データベースに接続するときにします。</span><span class="sxs-lookup"><span data-stu-id="936ef-101">Consistency level when connecting to the Cassandra database.</span></span>
            <span data-ttu-id="936ef-102">プロパティ<see cref="T:Microsoft.Azure.Management.DataFactories.Models.CassandraSource" />です。</span><span class="sxs-lookup"><span data-stu-id="936ef-102">A property of <see cref="T:Microsoft.Azure.Management.DataFactories.Models.CassandraSource" />.</span></span>
            <span data-ttu-id="936ef-103">参照: http://docs.datastax.com/en/cassandra/2.0/cassandra/dml/dml_config_consistency_c.html です。</span><span class="sxs-lookup"><span data-stu-id="936ef-103">Reference: http://docs.datastax.com/en/cassandra/2.0/cassandra/dml/dml_config_consistency_c.html.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="All">
      <MemberSignature Language="C#" Value="public const string All;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string All" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.DataFactories.Models.CassandraSourceReadConsistencyLevel.All" />
      <MemberSignature Language="VB.NET" Value="Public Const All As String " />
      <MemberSignature Language="F#" Value="val mutable All : string" Usage="Microsoft.Azure.Management.DataFactories.Models.CassandraSourceReadConsistencyLevel.All" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="936ef-104">すべてのレプリカが応答した後は、レコードを返します。</span><span class="sxs-lookup"><span data-stu-id="936ef-104">Returns the record after all replicas have responded.</span></span>
            <span data-ttu-id="936ef-105">レプリカが応答しない場合は、読み取り操作は失敗します。</span><span class="sxs-lookup"><span data-stu-id="936ef-105">The read operation will fail if a replica does not respond.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EachQuorum">
      <MemberSignature Language="C#" Value="public const string EachQuorum;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string EachQuorum" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.DataFactories.Models.CassandraSourceReadConsistencyLevel.EachQuorum" />
      <MemberSignature Language="VB.NET" Value="Public Const EachQuorum As String " />
      <MemberSignature Language="F#" Value="val mutable EachQuorum : string" Usage="Microsoft.Azure.Management.DataFactories.Models.CassandraSourceReadConsistencyLevel.EachQuorum" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="936ef-106">クラスターの各データ センター内のレプリカのクォーラムが応答した後は、レコードを返します。</span><span class="sxs-lookup"><span data-stu-id="936ef-106">Returns the record once a quorum of replicas in each data center of the cluster has responded.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocalOne">
      <MemberSignature Language="C#" Value="public const string LocalOne;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string LocalOne" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.DataFactories.Models.CassandraSourceReadConsistencyLevel.LocalOne" />
      <MemberSignature Language="VB.NET" Value="Public Const LocalOne As String " />
      <MemberSignature Language="F#" Value="val mutable LocalOne : string" Usage="Microsoft.Azure.Management.DataFactories.Models.CassandraSourceReadConsistencyLevel.LocalOne" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="936ef-107">ローカル データ センターに最も近いレプリカからの応答を返します。</span><span class="sxs-lookup"><span data-stu-id="936ef-107">Returns a response from the closest replica in the local data center.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocalQuorum">
      <MemberSignature Language="C#" Value="public const string LocalQuorum;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string LocalQuorum" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.DataFactories.Models.CassandraSourceReadConsistencyLevel.LocalQuorum" />
      <MemberSignature Language="VB.NET" Value="Public Const LocalQuorum As String " />
      <MemberSignature Language="F#" Value="val mutable LocalQuorum : string" Usage="Microsoft.Azure.Management.DataFactories.Models.CassandraSourceReadConsistencyLevel.LocalQuorum" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="936ef-108">コーディネーターが報告された、現在のデータ センター内のレプリカのクォーラムの後にレコードを返します。</span><span class="sxs-lookup"><span data-stu-id="936ef-108">Returns the record after a quorum of replicas in the current data center as the coordinator has reported.</span></span>
            <span data-ttu-id="936ef-109">間のデータ センターの通信の遅延を回避できます。</span><span class="sxs-lookup"><span data-stu-id="936ef-109">Avoids latency of inter-data center communication.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocalSerial">
      <MemberSignature Language="C#" Value="public const string LocalSerial;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string LocalSerial" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.DataFactories.Models.CassandraSourceReadConsistencyLevel.LocalSerial" />
      <MemberSignature Language="VB.NET" Value="Public Const LocalSerial As String " />
      <MemberSignature Language="F#" Value="val mutable LocalSerial : string" Usage="Microsoft.Azure.Management.DataFactories.Models.CassandraSourceReadConsistencyLevel.LocalSerial" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="936ef-110">シリアル ポートの場合は、データ センターに限られた問題と同じです。</span><span class="sxs-lookup"><span data-stu-id="936ef-110">Same as SERIAL, but confined to the data center.</span></span> <span data-ttu-id="936ef-111">LOCAL_QUORUM に似ています。</span><span class="sxs-lookup"><span data-stu-id="936ef-111">Similar to LOCAL_QUORUM.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="One">
      <MemberSignature Language="C#" Value="public const string One;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string One" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.DataFactories.Models.CassandraSourceReadConsistencyLevel.One" />
      <MemberSignature Language="VB.NET" Value="Public Const One As String " />
      <MemberSignature Language="F#" Value="val mutable One : string" Usage="Microsoft.Azure.Management.DataFactories.Models.CassandraSourceReadConsistencyLevel.One" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="936ef-112">Snitch によって決定される、最も近いレプリカからの応答を返します。</span><span class="sxs-lookup"><span data-stu-id="936ef-112">Returns a response from the closest replica, as determined by the snitch.</span></span>
            <span data-ttu-id="936ef-113">既定では、読み取りの修復は、他のレプリカの整合性を取るために、バック グラウンドで実行されます。</span><span class="sxs-lookup"><span data-stu-id="936ef-113">By default, a read repair runs in the background to make the other replicas consistent.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Quorum">
      <MemberSignature Language="C#" Value="public const string Quorum;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string Quorum" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.DataFactories.Models.CassandraSourceReadConsistencyLevel.Quorum" />
      <MemberSignature Language="VB.NET" Value="Public Const Quorum As String " />
      <MemberSignature Language="F#" Value="val mutable Quorum : string" Usage="Microsoft.Azure.Management.DataFactories.Models.CassandraSourceReadConsistencyLevel.Quorum" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="936ef-114">レプリカのクォーラムは、任意のデータ センターから応答した後は、レコードを返します。</span><span class="sxs-lookup"><span data-stu-id="936ef-114">Returns the record after a quorum of replicas has responded from any data center.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Serial">
      <MemberSignature Language="C#" Value="public const string Serial;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string Serial" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.DataFactories.Models.CassandraSourceReadConsistencyLevel.Serial" />
      <MemberSignature Language="VB.NET" Value="Public Const Serial As String " />
      <MemberSignature Language="F#" Value="val mutable Serial : string" Usage="Microsoft.Azure.Management.DataFactories.Models.CassandraSourceReadConsistencyLevel.Serial" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="936ef-115">新しく追加または更新を提案せず、データの状態を現在 (および場合によってコミットされていない) の読み取りを許可します。</span><span class="sxs-lookup"><span data-stu-id="936ef-115">Allows reading the current (and possibly uncommitted) state of data without proposing a new addition or update.</span></span>
            <span data-ttu-id="936ef-116">シリアル読み取りには、進行中のコミットされていないトランザクションが検出されると、読み取りの一部として、トランザクションはコミットします。</span><span class="sxs-lookup"><span data-stu-id="936ef-116">If a SERIAL read finds an uncommitted transaction in progress, it will commit the transaction as part of the read.</span></span> <span data-ttu-id="936ef-117">クォーラムに似ています。</span><span class="sxs-lookup"><span data-stu-id="936ef-117">Similar to QUORUM.</span></span> 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Three">
      <MemberSignature Language="C#" Value="public const string Three;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string Three" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.DataFactories.Models.CassandraSourceReadConsistencyLevel.Three" />
      <MemberSignature Language="VB.NET" Value="Public Const Three As String " />
      <MemberSignature Language="F#" Value="val mutable Three : string" Usage="Microsoft.Azure.Management.DataFactories.Models.CassandraSourceReadConsistencyLevel.Three" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="936ef-118">最も近いレプリカのうち、3 つの最新のデータを返します。</span><span class="sxs-lookup"><span data-stu-id="936ef-118">Returns the most recent data from three of the closest replicas.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Two">
      <MemberSignature Language="C#" Value="public const string Two;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string Two" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.DataFactories.Models.CassandraSourceReadConsistencyLevel.Two" />
      <MemberSignature Language="VB.NET" Value="Public Const Two As String " />
      <MemberSignature Language="F#" Value="val mutable Two : string" Usage="Microsoft.Azure.Management.DataFactories.Models.CassandraSourceReadConsistencyLevel.Two" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="936ef-119">2 つの最も近いレプリカから、最新のデータを返します。</span><span class="sxs-lookup"><span data-stu-id="936ef-119">Returns the most recent data from two of the closest replicas.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>