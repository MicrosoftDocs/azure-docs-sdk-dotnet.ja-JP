<Type Name="ClusterHealth" FullName="System.Fabric.Health.ClusterHealth">
  <TypeSignature Language="C#" Value="public sealed class ClusterHealth : System.Fabric.Health.EntityHealth" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ClusterHealth extends System.Fabric.Health.EntityHealth" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ClusterHealth" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ClusterHealth&#xA;Inherits EntityHealth" />
  <TypeSignature Language="F#" Value="type ClusterHealth = class&#xA;    inherit EntityHealth" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Health.EntityHealth</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="2a4a1-101">によって返される、クラスターの正常性を表す<see cref="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthAsync(System.Fabric.Description.ClusterHealthQueryDescription)" />です。</span><span class="sxs-lookup"><span data-stu-id="2a4a1-101">Represents the health of the cluster, as returned by <see cref="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthAsync(System.Fabric.Description.ClusterHealthQueryDescription)" />.</span></span>
            <span data-ttu-id="2a4a1-102">集計されたクラスターのヘルス状態、アプリケーションのヘルス状態、ノードの正常性状態だけでなく正常性イベント、正常性評価および状態の統計が含まれます。</span><span class="sxs-lookup"><span data-stu-id="2a4a1-102">Contains the cluster aggregated health state, the application health states, the node health states as well as health events, health evaluation, and health statistics.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplicationHealthStates">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.ApplicationHealthState&gt; ApplicationHealthStates { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.ApplicationHealthState&gt; ApplicationHealthStates" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ClusterHealth.ApplicationHealthStates" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationHealthStates As IList(Of ApplicationHealthState)" />
      <MemberSignature Language="F#" Value="member this.ApplicationHealthStates : System.Collections.Generic.IList&lt;System.Fabric.Health.ApplicationHealthState&gt;" Usage="System.Fabric.Health.ClusterHealth.ApplicationHealthStates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.ApplicationHealthState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="2a4a1-103">Health store にクラスターにあるアプリケーションの正常性状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="2a4a1-103">Gets the cluster application health states as found in the health store.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="2a4a1-104">Health store に検出されるようクラスター アプリケーションです。</span><span class="sxs-lookup"><span data-stu-id="2a4a1-104">The cluster applications as found in the health store.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
        <para><span data-ttu-id="2a4a1-105">すべてのアプリケーションを評価すると、集計されたクラスターの正常性を決定します。</span><span class="sxs-lookup"><span data-stu-id="2a4a1-105">All applications are evaluated to determine the cluster aggregated health.</span></span></para>
        <para><span data-ttu-id="2a4a1-106">アプリケーションを尊重でのみ、 <see cref="P:System.Fabric.Description.ClusterHealthQueryDescription.ApplicationsFilter" /> (指定した場合) が返されます。</span><span class="sxs-lookup"><span data-stu-id="2a4a1-106">Only applications that respect the <see cref="P:System.Fabric.Description.ClusterHealthQueryDescription.ApplicationsFilter" /> (if specified) are returned.</span></span> <span data-ttu-id="2a4a1-107">入力のフィルターが指定されていない場合は、すべてのアプリケーションが返されます。</span><span class="sxs-lookup"><span data-stu-id="2a4a1-107">If the input filter is not specified, all applications are returned.</span></span></para>
      </Docs>
    </Member>
    <Member MemberName="HealthStatistics">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthStatistics HealthStatistics { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.HealthStatistics HealthStatistics" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ClusterHealth.HealthStatistics" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthStatistics As HealthStatistics" />
      <MemberSignature Language="F#" Value="member this.HealthStatistics : System.Fabric.Health.HealthStatistics" Usage="System.Fabric.Health.ClusterHealth.HealthStatistics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthStatistics</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2a4a1-108">クラスター エンティティの数が、に関する情報を含むクラスター状態統計を取得<see cref="F:System.Fabric.Health.HealthState.Ok" />、 <see cref="F:System.Fabric.Health.HealthState.Warning" />、および<see cref="F:System.Fabric.Health.HealthState.Error" />状態です。</span><span class="sxs-lookup"><span data-stu-id="2a4a1-108">Gets the cluster health statistics, which contain information about how many cluster entities are in <see cref="F:System.Fabric.Health.HealthState.Ok" />, <see cref="F:System.Fabric.Health.HealthState.Warning" />, and <see cref="F:System.Fabric.Health.HealthState.Error" /> state.</span></span>
            </summary>
        <value><span data-ttu-id="2a4a1-109">クラスターの正常性統計です。</span><span class="sxs-lookup"><span data-stu-id="2a4a1-109">The cluster health statistics.</span></span></value>
        <remarks>
          <para>
            <span data-ttu-id="2a4a1-110">クラスターの状態の統計情報にはクラスター エンティティの数が、 <see cref="F:System.Fabric.Health.HealthState.Ok" />、 <see cref="F:System.Fabric.Health.HealthState.Warning" />、および<see cref="F:System.Fabric.Health.HealthState.Error" />状態です。</span><span class="sxs-lookup"><span data-stu-id="2a4a1-110">The cluster health statistics contain information about how many cluster entities are in <see cref="F:System.Fabric.Health.HealthState.Ok" />, <see cref="F:System.Fabric.Health.HealthState.Warning" />, and <see cref="F:System.Fabric.Health.HealthState.Error" /> state.</span></span>
            <span data-ttu-id="2a4a1-111">クエリを返す場合 null または空にすることできます、<see cref="T:System.Fabric.Health.ClusterHealth" />指定<see cref="T:System.Fabric.Health.ClusterHealthStatisticsFilter" />正常性の統計情報を除外します。</span><span class="sxs-lookup"><span data-stu-id="2a4a1-111">It can be null or empty if the query that returns the <see cref="T:System.Fabric.Health.ClusterHealth" /> specified <see cref="T:System.Fabric.Health.ClusterHealthStatisticsFilter" /> to exclude health statistics.</span></span>
            <span data-ttu-id="2a4a1-112">既定では、正常性クエリには、システム アプリケーションに関する統計情報が含まれていない統計情報が返されます。 アプリケーション、サービス、パーティション、レプリカの数が、アプリケーションを展開し、展開済みサービス パッケージには、唯一のユーザー エンティティが含まれます。</span><span class="sxs-lookup"><span data-stu-id="2a4a1-112">By default, the health query returns statistics that do not include statistics about the system application: the number of applications, services, partitions, replicas, deployed applications, and deployed service packages contain only user entities.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeHealthStates">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.NodeHealthState&gt; NodeHealthStates { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.NodeHealthState&gt; NodeHealthStates" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ClusterHealth.NodeHealthStates" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeHealthStates As IList(Of NodeHealthState)" />
      <MemberSignature Language="F#" Value="member this.NodeHealthStates : System.Collections.Generic.IList&lt;System.Fabric.Health.NodeHealthState&gt;" Usage="System.Fabric.Health.ClusterHealth.NodeHealthStates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.NodeHealthState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="2a4a1-113">Health store にクラスターにあるノードの正常性状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="2a4a1-113">Gets the cluster node health states as found in the health store.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="2a4a1-114">Health store に検出されるようクラスター ノードです。</span><span class="sxs-lookup"><span data-stu-id="2a4a1-114">The cluster nodes as found in the health store.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
        <para><span data-ttu-id="2a4a1-115">すべてのノードを評価すると、集計されたクラスターの正常性を決定します。</span><span class="sxs-lookup"><span data-stu-id="2a4a1-115">All nodes are evaluated to determine the cluster aggregated health.</span></span></para>
        <para><span data-ttu-id="2a4a1-116">尊重いるノードに対してのみ、 <see cref="P:System.Fabric.Description.ClusterHealthQueryDescription.NodesFilter" /> (指定した場合) が返されます。</span><span class="sxs-lookup"><span data-stu-id="2a4a1-116">Only nodes that respect the <see cref="P:System.Fabric.Description.ClusterHealthQueryDescription.NodesFilter" /> (if specified) are returned.</span></span> <span data-ttu-id="2a4a1-117">入力のフィルターが指定されていない場合は、すべてのノードが返されます。</span><span class="sxs-lookup"><span data-stu-id="2a4a1-117">If the input filter is not specified, all nodes are returned.</span></span></para>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ClusterHealth.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="clusterHealth.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2a4a1-118">文字列表現を取得、<see cref="T:System.Fabric.Health.ClusterHealth" />です。</span><span class="sxs-lookup"><span data-stu-id="2a4a1-118">Gets a string representation of the <see cref="T:System.Fabric.Health.ClusterHealth" />.</span></span>
            </summary>
        <returns><span data-ttu-id="2a4a1-119"><see cref="T:System.Fabric.Health.ClusterHealth" /> の文字列形式。</span><span class="sxs-lookup"><span data-stu-id="2a4a1-119">A string representation of the <see cref="T:System.Fabric.Health.ClusterHealth" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>