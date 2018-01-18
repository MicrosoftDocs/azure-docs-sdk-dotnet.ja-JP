<Type Name="EntityHealth" FullName="System.Fabric.Health.EntityHealth">
  <TypeSignature Language="C#" Value="public abstract class EntityHealth" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit EntityHealth extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.EntityHealth" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class EntityHealth" />
  <TypeSignature Language="F#" Value="type EntityHealth = class" />
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
      <para><span data-ttu-id="897de-101">関連するクラスをすべてのエンティティのヘルスの基本クラスを表します。</span><span class="sxs-lookup"><span data-stu-id="897de-101">Represents the base class for all entity health related classes.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected EntityHealth ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.EntityHealth.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="897de-102"><see cref="T:System.Fabric.Health.EntityHealth" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="897de-102">Initializes a new instance of the <see cref="T:System.Fabric.Health.EntityHealth" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AggregatedHealthState">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthState AggregatedHealthState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthState AggregatedHealthState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.EntityHealth.AggregatedHealthState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AggregatedHealthState As HealthState" />
      <MemberSignature Language="F#" Value="member this.AggregatedHealthState : System.Fabric.Health.HealthState" Usage="System.Fabric.Health.EntityHealth.AggregatedHealthState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="897de-103">エンティティで集計された正常性状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="897de-103">Gets the entity aggregated health state.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="897de-104"><see cref="T:System.Fabric.Health.HealthState" />に基づいて Health Manager によって計算された集計された正常性状態を表す (存在する場合)、エンティティとその子でイベントを報告し、正常性ポリシーを必要に応じて。</span><span class="sxs-lookup"><span data-stu-id="897de-104">The <see cref="T:System.Fabric.Health.HealthState" /> representing the aggregated health state computed by Health Manager based on reported events on entity and its children (if any) and desired health policy.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthEvents">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvent&gt; HealthEvents { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.HealthEvent&gt; HealthEvents" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.EntityHealth.HealthEvents" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthEvents As IList(Of HealthEvent)" />
      <MemberSignature Language="F#" Value="member this.HealthEvents : System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvent&gt;" Usage="System.Fabric.Health.EntityHealth.HealthEvents" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvent&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="897de-105">エンティティで報告される正常性イベントを取得します。</span><span class="sxs-lookup"><span data-stu-id="897de-105">Gets the health events reported on the entity.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="897de-106">エンティティの正常性イベントが報告されました。</span><span class="sxs-lookup"><span data-stu-id="897de-106">The health events reported on the entity.</span></span></para>
        </value>
        <remarks><span data-ttu-id="897de-107">正常性イベントは、正常性ストアに送信される正常性レポートに基づいて作成されます。</span><span class="sxs-lookup"><span data-stu-id="897de-107">The health events are created based on health reports sent to health store.</span></span> <span data-ttu-id="897de-108">正常性ストアによって追加された追加のメタデータが含まれます。</span><span class="sxs-lookup"><span data-stu-id="897de-108">They contain additional metadata added by health store.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="UnhealthyEvaluations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.EntityHealth.UnhealthyEvaluations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UnhealthyEvaluations As IList(Of HealthEvaluation)" />
      <MemberSignature Language="F#" Value="member this.UnhealthyEvaluations : System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt;" Usage="System.Fabric.Health.EntityHealth.UnhealthyEvaluations" />
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
          <para><span data-ttu-id="897de-109">現在の集計された正常性状態が正常性マネージャーによってに返された理由を示す異常な評価を取得します。</span><span class="sxs-lookup"><span data-stu-id="897de-109">Gets the unhealthy evaluations that show why the current aggregated health state was returned by Health Manager.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="897de-110">現在の集計された正常性状態が正常性マネージャーによってに返された理由を説明する異常な評価。</span><span class="sxs-lookup"><span data-stu-id="897de-110">The unhealthy evaluations that describe why the current aggregated health state was returned by Health Manager.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>