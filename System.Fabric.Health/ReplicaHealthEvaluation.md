<Type Name="ReplicaHealthEvaluation" FullName="System.Fabric.Health.ReplicaHealthEvaluation">
  <TypeSignature Language="C#" Value="public sealed class ReplicaHealthEvaluation : System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ReplicaHealthEvaluation extends System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ReplicaHealthEvaluation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ReplicaHealthEvaluation&#xA;Inherits HealthEvaluation" />
  <TypeSignature Language="F#" Value="type ReplicaHealthEvaluation = class&#xA;    inherit HealthEvaluation" />
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
      <para><span data-ttu-id="60749-101">レプリカの場合、データと正常性を評価する正常性ストアによって使用されるアルゴリズムに関する情報を含む正常性評価を表します。</span><span class="sxs-lookup"><span data-stu-id="60749-101">Represents health evaluation for a replica, containing information about the data and the algorithm used by health store to evaluate health.</span></span> <span data-ttu-id="60749-102">集計された正常性状態は、いずれかの場合にのみ、評価が返される<see cref="F:System.Fabric.Health.HealthState.Error" />または<see cref="F:System.Fabric.Health.HealthState.Warning" />です。</span><span class="sxs-lookup"><span data-stu-id="60749-102">The evaluation is returned only when the aggregated health state is either <see cref="F:System.Fabric.Health.HealthState.Error" /> or <see cref="F:System.Fabric.Health.HealthState.Warning" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public Guid PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid PartitionId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ReplicaHealthEvaluation.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As Guid" />
      <MemberSignature Language="F#" Value="member this.PartitionId : Guid" Usage="System.Fabric.Health.ReplicaHealthEvaluation.PartitionId" />
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
          <para><span data-ttu-id="60749-103">パーティション ID を取得します</span><span class="sxs-lookup"><span data-stu-id="60749-103">Gets the partition ID.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="60749-104">パーティションの id。</span><span class="sxs-lookup"><span data-stu-id="60749-104">The partition ID.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaOrInstanceId">
      <MemberSignature Language="C#" Value="public long ReplicaOrInstanceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ReplicaOrInstanceId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ReplicaHealthEvaluation.ReplicaOrInstanceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicaOrInstanceId As Long" />
      <MemberSignature Language="F#" Value="member this.ReplicaOrInstanceId : int64" Usage="System.Fabric.Health.ReplicaHealthEvaluation.ReplicaOrInstanceId" />
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
          <para><span data-ttu-id="60749-105">ステートフル サービス レプリカ ID またはステートレス サービス インスタンス ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="60749-105">Gets the stateful service replica ID or the stateless service instance ID.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="60749-106">レプリカまたはインスタンスの id。</span><span class="sxs-lookup"><span data-stu-id="60749-106">The replica or instance ID.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnhealthyEvaluations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ReplicaHealthEvaluation.UnhealthyEvaluations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UnhealthyEvaluations As IList(Of HealthEvaluation)" />
      <MemberSignature Language="F#" Value="member this.UnhealthyEvaluations : System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt;" Usage="System.Fabric.Health.ReplicaHealthEvaluation.UnhealthyEvaluations" />
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
          <para><span data-ttu-id="60749-107">レプリカの現在の集計された正常性状態に原因となった異常な評価を取得します。</span><span class="sxs-lookup"><span data-stu-id="60749-107">Gets the unhealthy evaluations that led to the current aggregated health state of the replica.</span></span> <span data-ttu-id="60749-108">異常な評価の種類を指定できます<see cref="T:System.Fabric.Health.EventHealthEvaluation" />です。</span><span class="sxs-lookup"><span data-stu-id="60749-108">The types of the unhealthy evaluations can be <see cref="T:System.Fabric.Health.EventHealthEvaluation" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="60749-109">現在の集計された正常性状態を原因となった異常な評価。</span><span class="sxs-lookup"><span data-stu-id="60749-109">The unhealthy evaluations that led to current aggregated health state.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>