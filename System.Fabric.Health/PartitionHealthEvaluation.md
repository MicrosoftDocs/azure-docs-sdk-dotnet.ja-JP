<Type Name="PartitionHealthEvaluation" FullName="System.Fabric.Health.PartitionHealthEvaluation">
  <TypeSignature Language="C#" Value="public sealed class PartitionHealthEvaluation : System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PartitionHealthEvaluation extends System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.PartitionHealthEvaluation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PartitionHealthEvaluation&#xA;Inherits HealthEvaluation" />
  <TypeSignature Language="F#" Value="type PartitionHealthEvaluation = class&#xA;    inherit HealthEvaluation" />
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
      <para><span data-ttu-id="962d6-101">データと正常性を評価する正常性ストアによって使用されるアルゴリズムに関する情報を含むパーティションの正常性評価を表します。</span><span class="sxs-lookup"><span data-stu-id="962d6-101">Represents health evaluation for a partition, containing information about the data and the algorithm used by health store to evaluate health.</span></span> <span data-ttu-id="962d6-102">集計された正常性状態は、いずれかの場合にのみ、評価が返される<see cref="F:System.Fabric.Health.HealthState.Error" />または<see cref="F:System.Fabric.Health.HealthState.Warning" />です。</span><span class="sxs-lookup"><span data-stu-id="962d6-102">The evaluation is returned only when the aggregated health state is either <see cref="F:System.Fabric.Health.HealthState.Error" /> or <see cref="F:System.Fabric.Health.HealthState.Warning" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public Guid PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid PartitionId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.PartitionHealthEvaluation.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As Guid" />
      <MemberSignature Language="F#" Value="member this.PartitionId : Guid" Usage="System.Fabric.Health.PartitionHealthEvaluation.PartitionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="962d6-103">パーティション ID を取得します</span><span class="sxs-lookup"><span data-stu-id="962d6-103">Gets the partition ID.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="962d6-104">パーティションの id。</span><span class="sxs-lookup"><span data-stu-id="962d6-104">The partition ID.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnhealthyEvaluations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.PartitionHealthEvaluation.UnhealthyEvaluations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UnhealthyEvaluations As IList(Of HealthEvaluation)" />
      <MemberSignature Language="F#" Value="member this.UnhealthyEvaluations : System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt;" Usage="System.Fabric.Health.PartitionHealthEvaluation.UnhealthyEvaluations" />
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
          <para><span data-ttu-id="962d6-105">パーティションの現在の集計された正常性状態に原因となった異常な評価を取得します。</span><span class="sxs-lookup"><span data-stu-id="962d6-105">Gets the unhealthy evaluations that led to the current aggregated health state of the partition.</span></span> <span data-ttu-id="962d6-106">異常な評価の種類を指定できます<see cref="T:System.Fabric.Health.ReplicasHealthEvaluation" />または<see cref="T:System.Fabric.Health.EventHealthEvaluation" />です。</span><span class="sxs-lookup"><span data-stu-id="962d6-106">The types of the unhealthy evaluations can be <see cref="T:System.Fabric.Health.ReplicasHealthEvaluation" /> or <see cref="T:System.Fabric.Health.EventHealthEvaluation" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="962d6-107">現在の集計された正常性状態を原因となった異常な評価。</span><span class="sxs-lookup"><span data-stu-id="962d6-107">The unhealthy evaluations that led to current aggregated health state.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>