<Type Name="ClusterHealthStatisticsFilter" FullName="System.Fabric.Health.ClusterHealthStatisticsFilter">
  <TypeSignature Language="C#" Value="public sealed class ClusterHealthStatisticsFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ClusterHealthStatisticsFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ClusterHealthStatisticsFilter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ClusterHealthStatisticsFilter" />
  <TypeSignature Language="F#" Value="type ClusterHealthStatisticsFilter = class" />
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
      <para><span data-ttu-id="f556a-101">フィルターを表す<see cref="T:System.Fabric.Health.HealthStatistics" />です。</span><span class="sxs-lookup"><span data-stu-id="f556a-101">Represents the filter for <see cref="T:System.Fabric.Health.HealthStatistics" />.</span></span></para>
    </summary>
    <remarks><span data-ttu-id="f556a-102">使用できるフィルター<see cref="T:System.Fabric.Description.ClusterHealthQueryDescription" />正常性の統計情報の一部として返されるかどうかを指定する<see cref="T:System.Fabric.Health.ClusterHealth" />です。</span><span class="sxs-lookup"><span data-stu-id="f556a-102">The filter can be used in <see cref="T:System.Fabric.Description.ClusterHealthQueryDescription" /> to specify whether the health statistics should be returned as part of <see cref="T:System.Fabric.Health.ClusterHealth" />.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClusterHealthStatisticsFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ClusterHealthStatisticsFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="f556a-103"><see cref="T:System.Fabric.Health.ClusterHealthStatisticsFilter" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f556a-103">Initializes a new instance of the <see cref="T:System.Fabric.Health.ClusterHealthStatisticsFilter" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExcludeHealthStatistics">
      <MemberSignature Language="C#" Value="public bool ExcludeHealthStatistics { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ExcludeHealthStatistics" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ClusterHealthStatisticsFilter.ExcludeHealthStatistics" />
      <MemberSignature Language="VB.NET" Value="Public Property ExcludeHealthStatistics As Boolean" />
      <MemberSignature Language="F#" Value="member this.ExcludeHealthStatistics : bool with get, set" Usage="System.Fabric.Health.ClusterHealthStatisticsFilter.ExcludeHealthStatistics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f556a-104">取得または状態の統計をクエリの結果に含める必要があるかどうかを示すフラグを設定します。</span><span class="sxs-lookup"><span data-stu-id="f556a-104">Gets or sets a flag that indicates whether the health statistics should be included in query result.</span></span>
            </summary>
        <value><span data-ttu-id="f556a-105">状態の統計をクエリの結果に含める必要があるかどうかを示すフラグです。</span><span class="sxs-lookup"><span data-stu-id="f556a-105">A flag that indicates whether the health statistics should be included in query result.</span></span></value>
        <remarks>
          <para>
            <span data-ttu-id="f556a-106">ExcludeHealthStatistics に設定されている場合<languageKeyword>true</languageKeyword>状態の統計はクエリ結果の一部として返されません。</span><span class="sxs-lookup"><span data-stu-id="f556a-106">If ExcludeHealthStatistics is set to <languageKeyword>true</languageKeyword>, the health statistics are not returned as part of the query result.</span></span>
            <span data-ttu-id="f556a-107">それ以外の場合、クエリの結果には、クラスターの状態の統計が含まれています。</span><span class="sxs-lookup"><span data-stu-id="f556a-107">Otherwise, the query result includes the cluster health statistics.</span></span>
            <span data-ttu-id="f556a-108">統計の数を含む、エンティティの種類ごとのクラスター内のエンティティの数を示しています<see cref="F:System.Fabric.Health.HealthState.Ok" />、 <see cref="F:System.Fabric.Health.HealthState.Warning" />、および<see cref="F:System.Fabric.Health.HealthState.Error" />状態です。</span><span class="sxs-lookup"><span data-stu-id="f556a-108">The statistics shows the number of entities in the cluster per entity type, with count for <see cref="F:System.Fabric.Health.HealthState.Ok" />, <see cref="F:System.Fabric.Health.HealthState.Warning" />, and <see cref="F:System.Fabric.Health.HealthState.Error" /> state.</span></span>
            <span data-ttu-id="f556a-109">既定値は<languageKeyword>false</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="f556a-109">Defaults to <languageKeyword>false</languageKeyword>.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="IncludeSystemApplicationHealthStatistics">
      <MemberSignature Language="C#" Value="public bool IncludeSystemApplicationHealthStatistics { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IncludeSystemApplicationHealthStatistics" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ClusterHealthStatisticsFilter.IncludeSystemApplicationHealthStatistics" />
      <MemberSignature Language="VB.NET" Value="Public Property IncludeSystemApplicationHealthStatistics As Boolean" />
      <MemberSignature Language="F#" Value="member this.IncludeSystemApplicationHealthStatistics : bool with get, set" Usage="System.Fabric.Health.ClusterHealthStatisticsFilter.IncludeSystemApplicationHealthStatistics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f556a-110">取得または状態の統計がファブリックの情報を含めるかどうかを示すフラグを設定します。/システム アプリケーションです。</span><span class="sxs-lookup"><span data-stu-id="f556a-110">Gets or sets a flag that indicates whether the health statistics should include information for the fabric:/System application.</span></span>
            </summary>
        <value><span data-ttu-id="f556a-111">状態の統計がファブリックの情報を含めるかどうかを示すフラグ。/システム アプリケーションです。</span><span class="sxs-lookup"><span data-stu-id="f556a-111">A flag that indicates whether the health statistics should include information for the fabric:/System application.</span></span></value>
        <remarks>
          <para>
            <span data-ttu-id="f556a-112">IncludeSystemApplicationHealthStatistics に設定されている場合<languageKeyword>true</languageKeyword>、正常性の統計情報には、ファブリックに属しているエンティティが含まれます。/システム アプリケーションです。</span><span class="sxs-lookup"><span data-stu-id="f556a-112">If IncludeSystemApplicationHealthStatistics is set to <languageKeyword>true</languageKeyword>, the health statistics include the entities that belong to the fabric:/System application.</span></span>
            <span data-ttu-id="f556a-113">そうでない場合、クエリの結果には、ユーザー アプリケーションのみの正常性の統計情報が含まれます。</span><span class="sxs-lookup"><span data-stu-id="f556a-113">Otherwise, the query result includes health statistics only for user applications.</span></span>
            <span data-ttu-id="f556a-114">既定値は<languageKeyword>false</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="f556a-114">Defaults to <languageKeyword>false</languageKeyword>.</span></span>
            </para>
          <para><span data-ttu-id="f556a-115">設定する必要があります ExcludeHealthStatistics IncludeSystemApplicationHealthStatistics を適用するために<languageKeyword>false</languageKeyword> (既定値)。</span><span class="sxs-lookup"><span data-stu-id="f556a-115">In order to apply IncludeSystemApplicationHealthStatistics, ExcludeHealthStatistics must be set to <languageKeyword>false</languageKeyword> (default value).</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ClusterHealthStatisticsFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="clusterHealthStatisticsFilter.ToString " />
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
            <span data-ttu-id="f556a-116">フィルターの文字列表現を返します。</span><span class="sxs-lookup"><span data-stu-id="f556a-116">Returns a string representation of the filter.</span></span>
            </summary>
        <returns><span data-ttu-id="f556a-117">フィルターの文字列形式。</span><span class="sxs-lookup"><span data-stu-id="f556a-117">A string representation of the filter.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>