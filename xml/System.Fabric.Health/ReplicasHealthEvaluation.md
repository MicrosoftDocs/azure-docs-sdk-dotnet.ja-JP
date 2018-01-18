<Type Name="ReplicasHealthEvaluation" FullName="System.Fabric.Health.ReplicasHealthEvaluation">
  <TypeSignature Language="C#" Value="public sealed class ReplicasHealthEvaluation : System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ReplicasHealthEvaluation extends System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ReplicasHealthEvaluation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ReplicasHealthEvaluation&#xA;Inherits HealthEvaluation" />
  <TypeSignature Language="F#" Value="type ReplicasHealthEvaluation = class&#xA;    inherit HealthEvaluation" />
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
      <para><span data-ttu-id="13661-101">現在の集計されたヘルス状態、影響を受ける異常な各レプリカの正常性評価を含む、レプリカの正常性評価を表します。</span><span class="sxs-lookup"><span data-stu-id="13661-101">Represents health evaluation for replicas, containing health evaluations for each unhealthy replica that impacted current aggregated health state.</span></span>
            <span data-ttu-id="13661-102">いずれかのパーティションの正常性と、集計された正常性状態の評価が返されることが<see cref="F:System.Fabric.Health.HealthState.Error" />または<see cref="F:System.Fabric.Health.HealthState.Warning" />です。</span><span class="sxs-lookup"><span data-stu-id="13661-102">Can be returned when evaluating partition health and the aggregated health state is either <see cref="F:System.Fabric.Health.HealthState.Error" /> or <see cref="F:System.Fabric.Health.HealthState.Warning" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="MaxPercentUnhealthyReplicasPerPartition">
      <MemberSignature Language="C#" Value="public byte MaxPercentUnhealthyReplicasPerPartition { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8 MaxPercentUnhealthyReplicasPerPartition" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ReplicasHealthEvaluation.MaxPercentUnhealthyReplicasPerPartition" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxPercentUnhealthyReplicasPerPartition As Byte" />
      <MemberSignature Language="F#" Value="member this.MaxPercentUnhealthyReplicasPerPartition : byte" Usage="System.Fabric.Health.ReplicasHealthEvaluation.MaxPercentUnhealthyReplicasPerPartition" />
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
          <para><span data-ttu-id="13661-103">許容される異常なレプリカからパーティションあたりの割合の最大値を取得、<see cref="T:System.Fabric.Health.ApplicationHealthPolicy" />です。</span><span class="sxs-lookup"><span data-stu-id="13661-103">Gets the maximum allowed percentage of unhealthy replicas per partition from the <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="13661-104">最大パーティションあたりの異常なレプリカの割合です。</span><span class="sxs-lookup"><span data-stu-id="13661-104">The maximum allowed percentage of unhealthy replicas per partition.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalCount">
      <MemberSignature Language="C#" Value="public long TotalCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TotalCount" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ReplicasHealthEvaluation.TotalCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalCount As Long" />
      <MemberSignature Language="F#" Value="member this.TotalCount : int64" Usage="System.Fabric.Health.ReplicasHealthEvaluation.TotalCount" />
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
          <para><span data-ttu-id="13661-105">Health store からパーティションのレプリカの合計数を取得します。</span><span class="sxs-lookup"><span data-stu-id="13661-105">Gets the total number of replicas in the partition from the health store.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="13661-106">パーティション内のレプリカの合計数。</span><span class="sxs-lookup"><span data-stu-id="13661-106">The total number of replicas in the partition.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnhealthyEvaluations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ReplicasHealthEvaluation.UnhealthyEvaluations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UnhealthyEvaluations As IList(Of HealthEvaluation)" />
      <MemberSignature Language="F#" Value="member this.UnhealthyEvaluations : System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt;" Usage="System.Fabric.Health.ReplicasHealthEvaluation.UnhealthyEvaluations" />
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
          <para><span data-ttu-id="13661-107">集計された正常性状態を原因となった異常な評価の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="13661-107">Gets the list of unhealthy evaluations that led to the aggregated health state.</span></span>
            <span data-ttu-id="13661-108">すべての異常が含まれています<see cref="T:System.Fabric.Health.ReplicaHealthEvaluation" />集計された正常性の影響を受けることです。</span><span class="sxs-lookup"><span data-stu-id="13661-108">Includes all the unhealthy <see cref="T:System.Fabric.Health.ReplicaHealthEvaluation" /> that impacted the aggregated health.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="13661-109">現在の集計された正常性状態を原因となった異常な評価。</span><span class="sxs-lookup"><span data-stu-id="13661-109">The unhealthy evaluations that led to current aggregated health state.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>