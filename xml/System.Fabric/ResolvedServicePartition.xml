<Type Name="ResolvedServicePartition" FullName="System.Fabric.ResolvedServicePartition">
  <TypeSignature Language="C#" Value="public sealed class ResolvedServicePartition" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ResolvedServicePartition extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ResolvedServicePartition" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ResolvedServicePartition" />
  <TypeSignature Language="F#" Value="type ResolvedServicePartition = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>
            <span data-ttu-id="ca439-101">解決されたサービスと一連のパーティションにアクセスするために使用するエンドポイントのパーティションに関する情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="ca439-101">Contains information about the partition of the service that was resolved and the set of endpoints that can be used to access the partition.</span></span></para>
    </summary>
    <remarks>
      <para>
            <span data-ttu-id="ca439-102">解決済みのサービス パーティションを取得する呼び出しの結果<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />およびその他のオーバー ロードします。</span><span class="sxs-lookup"><span data-stu-id="ca439-102">The resolved service partition is obtained as a result of calling <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" /> and the other overloads.</span></span>
            </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="CompareVersion">
      <MemberSignature Language="C#" Value="public int CompareVersion (System.Fabric.ResolvedServicePartition other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance int32 CompareVersion(class System.Fabric.ResolvedServicePartition other) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ResolvedServicePartition.CompareVersion(System.Fabric.ResolvedServicePartition)" />
      <MemberSignature Language="VB.NET" Value="Public Function CompareVersion (other As ResolvedServicePartition) As Integer" />
      <MemberSignature Language="F#" Value="member this.CompareVersion : System.Fabric.ResolvedServicePartition -&gt; int" Usage="resolvedServicePartition.CompareVersion other" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="System.Fabric.ResolvedServicePartition" />
      </Parameters>
      <Docs>
        <param name="other">
          <para><span data-ttu-id="ca439-103">その他の解決済みのサービス パーティションを比較します。</span><span class="sxs-lookup"><span data-stu-id="ca439-103">The other resolved service partition to compare.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="ca439-104">解決済みのサービスの 2 つのパーティションを比較し、これは新しいを識別します。</span><span class="sxs-lookup"><span data-stu-id="ca439-104">Compares two resolved service partitions and identifies which is newer.</span></span> </para>
        </summary>
        <returns>
          <para><span data-ttu-id="ca439-105"><see cref="T:System.Int32" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="ca439-105">Returns <see cref="T:System.Int32" />.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="ca439-106"><see cref="M:System.Fabric.ResolvedServicePartition.CompareVersion(System.Fabric.ResolvedServicePartition)" />メソッドはパラメーターを使用して、解決済みのサービス パーティション (RSP) の引数で使用<paramref name="other" />RSP はより最新の状態を識別するユーザーを有効にします。</span><span class="sxs-lookup"><span data-stu-id="ca439-106">The <see cref="M:System.Fabric.ResolvedServicePartition.CompareVersion(System.Fabric.ResolvedServicePartition)" /> method takes in a resolved service partition (RSP) argument with the parameter <paramref name="other" /> to enable the user to identify which RSP is more up-to-date.</span></span> <span data-ttu-id="ca439-107">返される値は 0 では、次の 2 つの RSPs 同じバージョンであることを示します。</span><span class="sxs-lookup"><span data-stu-id="ca439-107">A returned value of 0 indicates that the two RSPs have the same version.</span></span> <span data-ttu-id="ca439-108">1 は、その他の RSP が古いバージョンであることを示します。</span><span class="sxs-lookup"><span data-stu-id="ca439-108">1 indicates that the other RSP has an older version.</span></span> <span data-ttu-id="ca439-109">-1 は、その他の RSP が新しいバージョンであることを示します。</span><span class="sxs-lookup"><span data-stu-id="ca439-109">-1 indicates that the other RSP has a newer version.</span></span> </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="ca439-110">2 つ<see cref="T:System.Fabric.ResolvedServicePartition" />オブジェクト別のサービス パーティションからのものです。</span><span class="sxs-lookup"><span data-stu-id="ca439-110">The two <see cref="T:System.Fabric.ResolvedServicePartition" /> objects are from different service partitions.</span></span> <span data-ttu-id="ca439-111">これは、呼び出しを解決する 2 つのパーティション分割し、サービスが削除され、同じ名前で再作成される場合に発生することができます。</span><span class="sxs-lookup"><span data-stu-id="ca439-111">This can happen if the service is deleted and re-created with the same name and partitioning between two resolve calls.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="Endpoints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.ICollection&lt;System.Fabric.ResolvedServiceEndpoint&gt; Endpoints { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.ICollection`1&lt;class System.Fabric.ResolvedServiceEndpoint&gt; Endpoints" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ResolvedServicePartition.Endpoints" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Endpoints As ICollection(Of ResolvedServiceEndpoint)" />
      <MemberSignature Language="F#" Value="member this.Endpoints : System.Collections.Generic.ICollection&lt;System.Fabric.ResolvedServiceEndpoint&gt;" Usage="System.Fabric.ResolvedServicePartition.Endpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.ICollection&lt;System.Fabric.ResolvedServiceEndpoint&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="ca439-112">サービス パーティションのエンドポイントを取得します。</span><span class="sxs-lookup"><span data-stu-id="ca439-112">Gets the endpoints of the service partition.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="ca439-113">コレクション<see cref="T:System.Fabric.ResolvedServiceEndpoint" />指定したサービス パーティション用です。</span><span class="sxs-lookup"><span data-stu-id="ca439-113">A collection of <see cref="T:System.Fabric.ResolvedServiceEndpoint" /> for the specified service partition.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="ca439-114">解決済みのサービス エンドポイントには、ステートフル サービス レプリカまたはステートレス サービス インスタンスと、このレプリカがアクセスできるアドレス ロールが含まれています。</span><span class="sxs-lookup"><span data-stu-id="ca439-114">A resolved service endpoint contains the role of the stateful service replica or stateless service instance and the address where this replica can be reached.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEndpoint">
      <MemberSignature Language="C#" Value="public System.Fabric.ResolvedServiceEndpoint GetEndpoint ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Fabric.ResolvedServiceEndpoint GetEndpoint() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ResolvedServicePartition.GetEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEndpoint () As ResolvedServiceEndpoint" />
      <MemberSignature Language="F#" Value="member this.GetEndpoint : unit -&gt; System.Fabric.ResolvedServiceEndpoint" Usage="resolvedServicePartition.GetEndpoint " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ResolvedServiceEndpoint</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="ca439-115">すべてのエンドポイントのコレクションではなく、単一のエンドポイントを返します。</span><span class="sxs-lookup"><span data-stu-id="ca439-115">Returns a single endpoint, instead of a collection of all endpoints.</span></span> </para>
        </summary>
        <returns>
          <para><span data-ttu-id="ca439-116"><see cref="T:System.Fabric.ResolvedServiceEndpoint" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="ca439-116">Returns <see cref="T:System.Fabric.ResolvedServiceEndpoint" />.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="ca439-117">多くの場合、だけのすべてのエンドポイントではなく単一のエンドポイントです。</span><span class="sxs-lookup"><span data-stu-id="ca439-117">Many times, you only need a single endpoint instead of all the endpoints.</span></span> <span data-ttu-id="ca439-118">サービスがステートレスの場合は、ランダムなエンドポイントを返します。</span><span class="sxs-lookup"><span data-stu-id="ca439-118">If the service is stateless, it returns a random endpoint.</span></span> <span data-ttu-id="ca439-119">サービスがステートフルなサービスの場合よりも、サービス パーティションのプライマリ レプリカがリッスンするエンドポイントを返します。</span><span class="sxs-lookup"><span data-stu-id="ca439-119">If the service is a stateful service, than it returns the endpoint to which the Primary replica of the service partition listens.</span></span> <span data-ttu-id="ca439-120">現在プライマリ レプリカが存在しない場合にスローに注意してください<see cref="T:System.Fabric.FabricException" />です。</span><span class="sxs-lookup"><span data-stu-id="ca439-120">Note that if the Primary replica currently does not exist, it throws <see cref="T:System.Fabric.FabricException" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Info">
      <MemberSignature Language="C#" Value="public System.Fabric.ServicePartitionInformation Info { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.ServicePartitionInformation Info" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ResolvedServicePartition.Info" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Info As ServicePartitionInformation" />
      <MemberSignature Language="F#" Value="member this.Info : System.Fabric.ServicePartitionInformation" Usage="System.Fabric.ResolvedServicePartition.Info" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ServicePartitionInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="ca439-121">解決されたサービスのパーティションに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="ca439-121">Gets information about the partition of the service that was resolved.</span></span></para>
        </summary>
        <value><span data-ttu-id="ca439-122">解決されたか、サービスのパーティションに関する情報。</span><span class="sxs-lookup"><span data-stu-id="ca439-122">The information about the partition of the service that was resolved.</span></span></value>
        <remarks>
          <para>
            <span data-ttu-id="ca439-123">別のサービス パーティションを指定できます<see cref="T:System.Fabric.ServicePartitionKind" />です。</span><span class="sxs-lookup"><span data-stu-id="ca439-123">The service partition can be of different <see cref="T:System.Fabric.ServicePartitionKind" />.</span></span>
            <span data-ttu-id="ca439-124">サービス パーティションについては、パーティションに関する詳細な情報を取得する場合は、正しい派生型にキャストできます。</span><span class="sxs-lookup"><span data-stu-id="ca439-124">You can cast the service partition information to the correct derived type to get detailed information about the partition.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceName">
      <MemberSignature Language="C#" Value="public Uri ServiceName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ResolvedServicePartition.ServiceName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceName As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceName : Uri" Usage="System.Fabric.ResolvedServicePartition.ServiceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="ca439-125">サービス インスタンスの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="ca439-125">Gets the name of the service instance.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="ca439-126">サービス インスタンスの名前です。</span><span class="sxs-lookup"><span data-stu-id="ca439-126">The name of the service instance.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>