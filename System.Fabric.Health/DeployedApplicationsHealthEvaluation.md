<Type Name="DeployedApplicationsHealthEvaluation" FullName="System.Fabric.Health.DeployedApplicationsHealthEvaluation">
  <TypeSignature Language="C#" Value="public sealed class DeployedApplicationsHealthEvaluation : System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedApplicationsHealthEvaluation extends System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.DeployedApplicationsHealthEvaluation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedApplicationsHealthEvaluation&#xA;Inherits HealthEvaluation" />
  <TypeSignature Language="F#" Value="type DeployedApplicationsHealthEvaluation = class&#xA;    inherit HealthEvaluation" />
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
      <para><span data-ttu-id="4ed54-101">現在の集計された正常性状態の影響を受ける異常な展開済みアプリケーションごとに正常性評価を含む、展開済みアプリケーションの正常性評価を表します。</span><span class="sxs-lookup"><span data-stu-id="4ed54-101">Represents health evaluation for deployed applications, containing health evaluations for each unhealthy deployed application that impacted current aggregated health state.</span></span> <span data-ttu-id="4ed54-102">いずれかのアプリケーションの正常性と、集計された正常性状態の評価が返されることが<see cref="F:System.Fabric.Health.HealthState.Error" />または<see cref="F:System.Fabric.Health.HealthState.Warning" />です。</span><span class="sxs-lookup"><span data-stu-id="4ed54-102">Can be returned when evaluating application health and the aggregated health state is either <see cref="F:System.Fabric.Health.HealthState.Error" /> or <see cref="F:System.Fabric.Health.HealthState.Warning" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="MaxPercentUnhealthyDeployedApplications">
      <MemberSignature Language="C#" Value="public byte MaxPercentUnhealthyDeployedApplications { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8 MaxPercentUnhealthyDeployedApplications" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedApplicationsHealthEvaluation.MaxPercentUnhealthyDeployedApplications" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxPercentUnhealthyDeployedApplications As Byte" />
      <MemberSignature Language="F#" Value="member this.MaxPercentUnhealthyDeployedApplications : byte" Usage="System.Fabric.Health.DeployedApplicationsHealthEvaluation.MaxPercentUnhealthyDeployedApplications" />
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
          <para><span data-ttu-id="4ed54-103">許容される異常なデプロイ済みのアプリケーションからの割合の最大値を取得、<see cref="T:System.Fabric.Health.ApplicationHealthPolicy" />です。</span><span class="sxs-lookup"><span data-stu-id="4ed54-103">Gets the maximum allowed percentage of unhealthy deployed applications from the <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="4ed54-104">A<see cref="T:System.Byte" />許容される異常な場合の割合の最大値を表すアプリケーションを展開します。</span><span class="sxs-lookup"><span data-stu-id="4ed54-104">A <see cref="T:System.Byte" /> representing the maximum allowed percentage of unhealthy deployed applications.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalCount">
      <MemberSignature Language="C#" Value="public long TotalCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TotalCount" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedApplicationsHealthEvaluation.TotalCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalCount As Long" />
      <MemberSignature Language="F#" Value="member this.TotalCount : int64" Usage="System.Fabric.Health.DeployedApplicationsHealthEvaluation.TotalCount" />
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
          <para><span data-ttu-id="4ed54-105">Health store にアプリケーションの展開済みのアプリケーションの合計数を取得します。</span><span class="sxs-lookup"><span data-stu-id="4ed54-105">Gets the total number of deployed applications of the application in the health store.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="4ed54-106"><see cref="T:System.Int64" />の合計数を表す health store にアプリケーションのアプリケーションを展開します。</span><span class="sxs-lookup"><span data-stu-id="4ed54-106">An <see cref="T:System.Int64" /> representing the total count of deployed applications of the application in the health store.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnhealthyEvaluations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedApplicationsHealthEvaluation.UnhealthyEvaluations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UnhealthyEvaluations As IList(Of HealthEvaluation)" />
      <MemberSignature Language="F#" Value="member this.UnhealthyEvaluations : System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt;" Usage="System.Fabric.Health.DeployedApplicationsHealthEvaluation.UnhealthyEvaluations" />
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
          <para><span data-ttu-id="4ed54-107">集計された正常性状態を原因となった異常な評価の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="4ed54-107">Gets the list of unhealthy evaluations that led to the aggregated health state.</span></span> <span data-ttu-id="4ed54-108">すべての異常が含まれています<see cref="T:System.Fabric.Health.DeployedApplicationHealthEvaluation" />集計された正常性の影響を受けることです。</span><span class="sxs-lookup"><span data-stu-id="4ed54-108">Includes all the unhealthy <see cref="T:System.Fabric.Health.DeployedApplicationHealthEvaluation" /> that impacted the aggregated health.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="4ed54-109">現在の集計された正常性状態を原因となった異常な評価の一覧。</span><span class="sxs-lookup"><span data-stu-id="4ed54-109">A list of unhealthy evaluations that led to current aggregated health state.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>