<Type Name="UpgradeDomainDeployedApplicationsHealthEvaluation" FullName="System.Fabric.Health.UpgradeDomainDeployedApplicationsHealthEvaluation">
  <TypeSignature Language="C#" Value="public sealed class UpgradeDomainDeployedApplicationsHealthEvaluation : System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit UpgradeDomainDeployedApplicationsHealthEvaluation extends System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.UpgradeDomainDeployedApplicationsHealthEvaluation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class UpgradeDomainDeployedApplicationsHealthEvaluation&#xA;Inherits HealthEvaluation" />
  <TypeSignature Language="F#" Value="type UpgradeDomainDeployedApplicationsHealthEvaluation = class&#xA;    inherit HealthEvaluation" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Health.HealthEvaluation</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="a4aa6-101">現在の集計された正常性状態の影響を受ける異常な展開済みアプリケーションごとに正常性評価を含む、アップグレード ドメイン内のアプリケーションの展開済みアプリケーションの正常性評価を表します。</span><span class="sxs-lookup"><span data-stu-id="a4aa6-101">Represents health evaluation for deployed applications of an application in an upgrade domain, containing health evaluations for each unhealthy deployed application that impacted current aggregated health state.</span></span>
            </para>
    </summary>
    <remarks><span data-ttu-id="a4aa6-102">いずれかがクラスターやアプリケーションのアップグレードと、集計された正常性状態の中にアプリケーションの正常性を評価するときに返される<see cref="F:System.Fabric.Health.HealthState.Error" />または<see cref="F:System.Fabric.Health.HealthState.Warning" />です。</span><span class="sxs-lookup"><span data-stu-id="a4aa6-102">Can be returned when evaluating application health during cluster or application upgrade and the aggregated health state is either <see cref="F:System.Fabric.Health.HealthState.Error" /> or <see cref="F:System.Fabric.Health.HealthState.Warning" />.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName="MaxPercentUnhealthyDeployedApplications">
      <MemberSignature Language="C#" Value="public byte MaxPercentUnhealthyDeployedApplications { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8 MaxPercentUnhealthyDeployedApplications" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.UpgradeDomainDeployedApplicationsHealthEvaluation.MaxPercentUnhealthyDeployedApplications" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxPercentUnhealthyDeployedApplications As Byte" />
      <MemberSignature Language="F#" Value="member this.MaxPercentUnhealthyDeployedApplications : byte" Usage="System.Fabric.Health.UpgradeDomainDeployedApplicationsHealthEvaluation.MaxPercentUnhealthyDeployedApplications" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="a4aa6-103">許容される異常なデプロイ済みのアプリケーションからの割合の最大値を取得、<see cref="T:System.Fabric.Health.ApplicationHealthPolicy" />です。</span><span class="sxs-lookup"><span data-stu-id="a4aa6-103">Gets the maximum allowed percentage of unhealthy deployed applications from the <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="a4aa6-104">許容される異常な展開済みアプリケーションの割合の最大値。</span><span class="sxs-lookup"><span data-stu-id="a4aa6-104">The maximum allowed percentage of unhealthy deployed applications.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalCount">
      <MemberSignature Language="C#" Value="public long TotalCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TotalCount" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.UpgradeDomainDeployedApplicationsHealthEvaluation.TotalCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalCount As Long" />
      <MemberSignature Language="F#" Value="member this.TotalCount : int64" Usage="System.Fabric.Health.UpgradeDomainDeployedApplicationsHealthEvaluation.TotalCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="a4aa6-105">現在のアップグレード ドメイン内の現在のアプリケーションの展開済みのアプリケーションの合計数を取得します。</span><span class="sxs-lookup"><span data-stu-id="a4aa6-105">Gets the total number of deployed applications of the current application in the current upgrade domain.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="a4aa6-106">現在のアップグレード ドメイン内の現在のアプリケーションの展開済みのアプリケーションの合計数。</span><span class="sxs-lookup"><span data-stu-id="a4aa6-106">The total number of deployed applications of the current application in the current upgrade domain.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnhealthyEvaluations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.UpgradeDomainDeployedApplicationsHealthEvaluation.UnhealthyEvaluations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UnhealthyEvaluations As IList(Of HealthEvaluation)" />
      <MemberSignature Language="F#" Value="member this.UnhealthyEvaluations : System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt;" Usage="System.Fabric.Health.UpgradeDomainDeployedApplicationsHealthEvaluation.UnhealthyEvaluations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="a4aa6-107">集計された正常性状態を原因となった異常な評価の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="a4aa6-107">Gets the list of unhealthy evaluations that led to the aggregated health state.</span></span> <span data-ttu-id="a4aa6-108">すべての異常が含まれています<see cref="T:System.Fabric.Health.DeployedApplicationHealthEvaluation" />集計された正常性の影響を受けることです。</span><span class="sxs-lookup"><span data-stu-id="a4aa6-108">Includes all the unhealthy <see cref="T:System.Fabric.Health.DeployedApplicationHealthEvaluation" /> that impacted the aggregated health.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="a4aa6-109">現在の集計された正常性状態を原因となった異常な評価。</span><span class="sxs-lookup"><span data-stu-id="a4aa6-109">The unhealthy evaluations that led to current aggregated health state.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeDomainName">
      <MemberSignature Language="C#" Value="public string UpgradeDomainName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UpgradeDomainName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.UpgradeDomainDeployedApplicationsHealthEvaluation.UpgradeDomainName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradeDomainName As String" />
      <MemberSignature Language="F#" Value="member this.UpgradeDomainName : string" Usage="System.Fabric.Health.UpgradeDomainDeployedApplicationsHealthEvaluation.UpgradeDomainName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="a4aa6-110">アプリケーションの正常性が評価される現在のアップグレード ドメインの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="a4aa6-110">Gets the name of the upgrade domain where the application health is currently evaluated.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="a4aa6-111">アップグレード ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="a4aa6-111">The upgrade domain name.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>