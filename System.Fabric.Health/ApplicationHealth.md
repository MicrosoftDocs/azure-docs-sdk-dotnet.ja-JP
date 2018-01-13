<Type Name="ApplicationHealth" FullName="System.Fabric.Health.ApplicationHealth">
  <TypeSignature Language="C#" Value="public sealed class ApplicationHealth : System.Fabric.Health.EntityHealth" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationHealth extends System.Fabric.Health.EntityHealth" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ApplicationHealth" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationHealth&#xA;Inherits EntityHealth" />
  <TypeSignature Language="F#" Value="type ApplicationHealth = class&#xA;    inherit EntityHealth" />
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
      <para><span data-ttu-id="2bae4-101">によって返されるアプリケーションの正常性を示します<see cref="M:System.Fabric.FabricClient.HealthClient.GetApplicationHealthAsync(System.Fabric.Description.ApplicationHealthQueryDescription)" />です。</span><span class="sxs-lookup"><span data-stu-id="2bae4-101">Describes the health of an application as returned by <see cref="M:System.Fabric.FabricClient.HealthClient.GetApplicationHealthAsync(System.Fabric.Description.ApplicationHealthQueryDescription)" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealth.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.Health.ApplicationHealth.ApplicationName" />
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
          <para><span data-ttu-id="2bae4-102">アプリケーションを一意に識別するアプリケーション名を取得します。</span><span class="sxs-lookup"><span data-stu-id="2bae4-102">Gets the application name, which uniquely identifies the application .</span></span> </para>
        </summary>
        <value>
          <para><span data-ttu-id="2bae4-103">アプリケーション名。</span><span class="sxs-lookup"><span data-stu-id="2bae4-103">The application name.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeployedApplicationHealthStates">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.DeployedApplicationHealthState&gt; DeployedApplicationHealthStates { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.DeployedApplicationHealthState&gt; DeployedApplicationHealthStates" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealth.DeployedApplicationHealthStates" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeployedApplicationHealthStates As IList(Of DeployedApplicationHealthState)" />
      <MemberSignature Language="F#" Value="member this.DeployedApplicationHealthStates : System.Collections.Generic.IList&lt;System.Fabric.Health.DeployedApplicationHealthState&gt;" Usage="System.Fabric.Health.ApplicationHealth.DeployedApplicationHealthStates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.DeployedApplicationHealthState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="2bae4-104">Health store に検出されるように、現在のアプリケーションの展開済みアプリケーションの正常性状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="2bae4-104">Gets the deployed application health states for the current application as found in the health store.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="2bae4-105">health store に検出されるよう、現在のアプリケーション用のアプリケーションを展開します。</span><span class="sxs-lookup"><span data-stu-id="2bae4-105">deployed applications for the current application as found in the health store.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
        <para><span data-ttu-id="2bae4-106">配置されているすべてのアプリケーションを評価して、アプリケーションで集計された正常性を決定します。</span><span class="sxs-lookup"><span data-stu-id="2bae4-106">All deployed applications are evaluated to determine the application aggregated health.</span></span></para>
        <para><span data-ttu-id="2bae4-107">考慮するアプリケーション展開のみ、 <see cref="P:System.Fabric.Description.ApplicationHealthQueryDescription.DeployedApplicationsFilter" /> (指定した場合) が返されます。</span><span class="sxs-lookup"><span data-stu-id="2bae4-107">Only deployed applications that respect the <see cref="P:System.Fabric.Description.ApplicationHealthQueryDescription.DeployedApplicationsFilter" /> (if specified) are returned.</span></span> <span data-ttu-id="2bae4-108">入力のフィルターが指定されていない場合は、配置されているすべてのアプリケーションが返されます。</span><span class="sxs-lookup"><span data-stu-id="2bae4-108">If the input filter is not specified, all deployed applications are returned.</span></span></para>
      </Docs>
    </Member>
    <Member MemberName="HealthStatistics">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthStatistics HealthStatistics { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.HealthStatistics HealthStatistics" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealth.HealthStatistics" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthStatistics As HealthStatistics" />
      <MemberSignature Language="F#" Value="member this.HealthStatistics : System.Fabric.Health.HealthStatistics" Usage="System.Fabric.Health.ApplicationHealth.HealthStatistics" />
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
            <span data-ttu-id="2bae4-109">アプリケーションのエンティティの数が、に関する情報を含むアプリケーション ヘルス統計を取得<see cref="F:System.Fabric.Health.HealthState.Ok" />、 <see cref="F:System.Fabric.Health.HealthState.Warning" />、および<see cref="F:System.Fabric.Health.HealthState.Error" />状態です。</span><span class="sxs-lookup"><span data-stu-id="2bae4-109">Gets the application health statistics, which contain information about how many entities of the application are in <see cref="F:System.Fabric.Health.HealthState.Ok" />, <see cref="F:System.Fabric.Health.HealthState.Warning" />, and <see cref="F:System.Fabric.Health.HealthState.Error" /> state.</span></span>
            </summary>
        <value><span data-ttu-id="2bae4-110">アプリケーション状態の統計。</span><span class="sxs-lookup"><span data-stu-id="2bae4-110">The application health statistics.</span></span></value>
        <remarks>
          <para>
            <span data-ttu-id="2bae4-111">アプリケーションの正常性の統計情報がどのくらいサービス、パーティション、レプリカ、展開済みのアプリケーションに関する情報を格納し、展開済みサービス パッケージでは、 <see cref="F:System.Fabric.Health.HealthState.Ok" />、 <see cref="F:System.Fabric.Health.HealthState.Warning" />、および<see cref="F:System.Fabric.Health.HealthState.Error" />状態です。</span><span class="sxs-lookup"><span data-stu-id="2bae4-111">The application health statistics contain information about how many services, partitions, replicas, deployed applications, and deployed service packages are in <see cref="F:System.Fabric.Health.HealthState.Ok" />, <see cref="F:System.Fabric.Health.HealthState.Warning" />, and <see cref="F:System.Fabric.Health.HealthState.Error" /> state.</span></span>
            <span data-ttu-id="2bae4-112">クエリを返す場合 null または空にすることできます、<see cref="T:System.Fabric.Health.ApplicationHealth" />指定<see cref="T:System.Fabric.Health.ApplicationHealthStatisticsFilter" />正常性の統計情報を除外します。</span><span class="sxs-lookup"><span data-stu-id="2bae4-112">It can be null or empty if the query that returns the <see cref="T:System.Fabric.Health.ApplicationHealth" /> specified <see cref="T:System.Fabric.Health.ApplicationHealthStatisticsFilter" /> to exclude health statistics.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceHealthStates">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.ServiceHealthState&gt; ServiceHealthStates { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.ServiceHealthState&gt; ServiceHealthStates" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealth.ServiceHealthStates" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceHealthStates As IList(Of ServiceHealthState)" />
      <MemberSignature Language="F#" Value="member this.ServiceHealthStates : System.Collections.Generic.IList&lt;System.Fabric.Health.ServiceHealthState&gt;" Usage="System.Fabric.Health.ApplicationHealth.ServiceHealthStates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.ServiceHealthState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="2bae4-113">Health store に検出されるように、現在のアプリケーションのサービスのヘルス状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="2bae4-113">Gets the service health states for the current application as found in the health store.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="2bae4-114">Health store に検出されるよう、現在のアプリケーションのサービスです。</span><span class="sxs-lookup"><span data-stu-id="2bae4-114">The services of the current application as found in the health store.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
        <para><span data-ttu-id="2bae4-115">すべてのサービスを評価して、アプリケーションで集計された正常性を決定します。</span><span class="sxs-lookup"><span data-stu-id="2bae4-115">All services are evaluated to determine the application aggregated health.</span></span></para>
        <para><span data-ttu-id="2bae4-116">その点をサービスのみ、 <see cref="P:System.Fabric.Description.ApplicationHealthQueryDescription.ServicesFilter" /> (指定した場合) が返されます。</span><span class="sxs-lookup"><span data-stu-id="2bae4-116">Only services that respect the <see cref="P:System.Fabric.Description.ApplicationHealthQueryDescription.ServicesFilter" /> (if specified) are returned.</span></span> <span data-ttu-id="2bae4-117">入力のフィルターが指定されていない場合は、すべてのサービスが返されます。</span><span class="sxs-lookup"><span data-stu-id="2bae4-117">If the input filter is not specified, all services are returned.</span></span></para>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ApplicationHealth.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="applicationHealth.ToString " />
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
            <span data-ttu-id="2bae4-118">文字列表現を取得、<see cref="T:System.Fabric.Health.ApplicationHealth" />です。</span><span class="sxs-lookup"><span data-stu-id="2bae4-118">Gets a string representation of the <see cref="T:System.Fabric.Health.ApplicationHealth" />.</span></span>
            </summary>
        <returns><span data-ttu-id="2bae4-119"><see cref="T:System.Fabric.Health.ApplicationHealth" /> の文字列形式。</span><span class="sxs-lookup"><span data-stu-id="2bae4-119">A string representation of the <see cref="T:System.Fabric.Health.ApplicationHealth" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>