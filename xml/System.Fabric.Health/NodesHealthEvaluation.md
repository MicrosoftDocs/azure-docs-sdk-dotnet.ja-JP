<Type Name="NodesHealthEvaluation" FullName="System.Fabric.Health.NodesHealthEvaluation">
  <TypeSignature Language="C#" Value="public sealed class NodesHealthEvaluation : System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NodesHealthEvaluation extends System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.NodesHealthEvaluation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NodesHealthEvaluation&#xA;Inherits HealthEvaluation" />
  <TypeSignature Language="F#" Value="type NodesHealthEvaluation = class&#xA;    inherit HealthEvaluation" />
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
      <para><span data-ttu-id="4a8e6-101">現在の集計された正常性状態の影響を受ける各の異常なノードの正常性評価を含むノードの正常性評価を表します。</span><span class="sxs-lookup"><span data-stu-id="4a8e6-101">Represents health evaluation for nodes, containing health evaluations for each unhealthy node that impacted current aggregated health state.</span></span> <span data-ttu-id="4a8e6-102">いずれかのクラスターの正常性と、集計された正常性状態の評価が返されることが<see cref="F:System.Fabric.Health.HealthState.Error" />または<see cref="F:System.Fabric.Health.HealthState.Warning" />です。</span><span class="sxs-lookup"><span data-stu-id="4a8e6-102">Can be returned when evaluating cluster health and the aggregated health state is either <see cref="F:System.Fabric.Health.HealthState.Error" /> or <see cref="F:System.Fabric.Health.HealthState.Warning" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="MaxPercentUnhealthyNodes">
      <MemberSignature Language="C#" Value="public byte MaxPercentUnhealthyNodes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8 MaxPercentUnhealthyNodes" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.NodesHealthEvaluation.MaxPercentUnhealthyNodes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxPercentUnhealthyNodes As Byte" />
      <MemberSignature Language="F#" Value="member this.MaxPercentUnhealthyNodes : byte" Usage="System.Fabric.Health.NodesHealthEvaluation.MaxPercentUnhealthyNodes" />
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
          <para><span data-ttu-id="4a8e6-103">許容される異常なノードからの割合の最大値を取得、<see cref="T:System.Fabric.Health.ClusterHealthPolicy" />です。</span><span class="sxs-lookup"><span data-stu-id="4a8e6-103">Gets the maximum allowed percentage of unhealthy nodes from the <see cref="T:System.Fabric.Health.ClusterHealthPolicy" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="4a8e6-104">許容される異常なノードの割合の最大値。</span><span class="sxs-lookup"><span data-stu-id="4a8e6-104">The maximum allowed percentage of unhealthy nodes.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalCount">
      <MemberSignature Language="C#" Value="public long TotalCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TotalCount" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.NodesHealthEvaluation.TotalCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalCount As Long" />
      <MemberSignature Language="F#" Value="member this.TotalCount : int64" Usage="System.Fabric.Health.NodesHealthEvaluation.TotalCount" />
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
          <para><span data-ttu-id="4a8e6-105">正常性ストア内のノードの合計数を取得します。</span><span class="sxs-lookup"><span data-stu-id="4a8e6-105">Gets the total number of nodes in the health store.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="4a8e6-106">正常性ストア内のノードの合計数。</span><span class="sxs-lookup"><span data-stu-id="4a8e6-106">The total number of nodes in the health store.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnhealthyEvaluations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.NodesHealthEvaluation.UnhealthyEvaluations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UnhealthyEvaluations As IList(Of HealthEvaluation)" />
      <MemberSignature Language="F#" Value="member this.UnhealthyEvaluations : System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt;" Usage="System.Fabric.Health.NodesHealthEvaluation.UnhealthyEvaluations" />
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
          <para><span data-ttu-id="4a8e6-107">集計された正常性状態を原因となった異常な評価の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="4a8e6-107">Gets the list of unhealthy evaluations that led to the aggregated health state.</span></span> <span data-ttu-id="4a8e6-108">すべての異常が含まれています<see cref="T:System.Fabric.Health.NodeHealthEvaluation" />集計された正常性の影響を受けることです。</span><span class="sxs-lookup"><span data-stu-id="4a8e6-108">Includes all the unhealthy <see cref="T:System.Fabric.Health.NodeHealthEvaluation" /> that impacted the aggregated health.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="4a8e6-109">現在の集計された正常性状態を原因となった異常な評価。</span><span class="sxs-lookup"><span data-stu-id="4a8e6-109">The unhealthy evaluations that led to current aggregated health state.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>