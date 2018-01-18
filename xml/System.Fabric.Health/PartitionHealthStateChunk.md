<Type Name="PartitionHealthStateChunk" FullName="System.Fabric.Health.PartitionHealthStateChunk">
  <TypeSignature Language="C#" Value="public sealed class PartitionHealthStateChunk" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PartitionHealthStateChunk extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.PartitionHealthStateChunk" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PartitionHealthStateChunk" />
  <TypeSignature Language="F#" Value="type PartitionHealthStateChunk = class" />
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
            <span data-ttu-id="3ed21-101">パーティションに関する基本的な正常性の情報が含まれているパーティションの正常性の状態チャンクを表します。</span><span class="sxs-lookup"><span data-stu-id="3ed21-101">Represents a partition health state chunk, which contains basic health information about the partition.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="HealthState">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthState HealthState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthState HealthState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.PartitionHealthStateChunk.HealthState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthState As HealthState" />
      <MemberSignature Language="F#" Value="member this.HealthState : System.Fabric.Health.HealthState" Usage="System.Fabric.Health.PartitionHealthStateChunk.HealthState" />
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
            <span data-ttu-id="3ed21-102">パーティションの集計計算のヘルス状態の取得は、報告された状態のすべてのイベント、レプリカの子およびアプリケーションの正常性ポリシーに基づいています。</span><span class="sxs-lookup"><span data-stu-id="3ed21-102">Gets the partition aggregated health state, computed based on all reported health events, the replica children and the application health policy.</span></span>
            </summary>
        <value><span data-ttu-id="3ed21-103">パーティションの集計された正常性状態</span><span class="sxs-lookup"><span data-stu-id="3ed21-103">The aggregated health state of the partition.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public Guid PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid PartitionId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.PartitionHealthStateChunk.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As Guid" />
      <MemberSignature Language="F#" Value="member this.PartitionId : Guid" Usage="System.Fabric.Health.PartitionHealthStateChunk.PartitionId" />
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
            <span data-ttu-id="3ed21-104">パーティション id を取得します。</span><span class="sxs-lookup"><span data-stu-id="3ed21-104">Gets the partition id.</span></span>
            </summary>
        <value><span data-ttu-id="3ed21-105">パーティション id。</span><span class="sxs-lookup"><span data-stu-id="3ed21-105">The partition id.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaHealthStateChunks">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ReplicaHealthStateChunkList ReplicaHealthStateChunks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ReplicaHealthStateChunkList ReplicaHealthStateChunks" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.PartitionHealthStateChunk.ReplicaHealthStateChunks" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicaHealthStateChunks As ReplicaHealthStateChunkList" />
      <MemberSignature Language="F#" Value="member this.ReplicaHealthStateChunks : System.Fabric.Health.ReplicaHealthStateChunkList" Usage="System.Fabric.Health.PartitionHealthStateChunk.ReplicaHealthStateChunks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ReplicaHealthStateChunkList</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3ed21-106">レプリカのヘルス状態チャンク入力フィルターを適用するパーティションの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="3ed21-106">Gets the list of the partition replica health state chunks that respect the input filters.</span></span>
            </summary>
        <value><span data-ttu-id="3ed21-107">入力フィルターを適用するパーティション レプリカ ヘルス状態チャンクの一覧。</span><span class="sxs-lookup"><span data-stu-id="3ed21-107">The list of the partition replica health state chunks that respect the input filters.</span></span></value>
        <remarks>
          <para><span data-ttu-id="3ed21-108">既定では、子ない結果に含められます。</span><span class="sxs-lookup"><span data-stu-id="3ed21-108">By default, no children are included in results.</span></span> <span data-ttu-id="3ed21-109">ユーザーは、必要な正常性アドインまたはその他の情報に基づく子の一部を含めるように要求できます。</span><span class="sxs-lookup"><span data-stu-id="3ed21-109">Users can request to include some children based on desired health or other information.</span></span> <span data-ttu-id="3ed21-110">たとえば、ユーザーは、ヘルス状態のエラーのあるすべてのレプリカを含めるに要求できます。</span><span class="sxs-lookup"><span data-stu-id="3ed21-110">For example, users can request to include all replicas that have health state error.</span></span>
            <span data-ttu-id="3ed21-111">フィルター値に関係なく、すべての子は、パーティションの集計された正常性が計算に使用されます。</span><span class="sxs-lookup"><span data-stu-id="3ed21-111">Regardless of filter value, all children are used to compute partition aggregated health.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.PartitionHealthStateChunk.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="partitionHealthStateChunk.ToString " />
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
            <span data-ttu-id="3ed21-112">パーティションのヘルス状態のチャンクについて説明する文字列を作成します。</span><span class="sxs-lookup"><span data-stu-id="3ed21-112">Creates a string description of the partition health state chunk.</span></span>
            </summary>
        <returns><span data-ttu-id="3ed21-113">ヘルス状態のチャンクの説明の文字列を指定します。</span><span class="sxs-lookup"><span data-stu-id="3ed21-113">String description of the health state chunk.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>