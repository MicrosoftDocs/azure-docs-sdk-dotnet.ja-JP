<Type Name="ClusterHealthChunk" FullName="System.Fabric.Health.ClusterHealthChunk">
  <TypeSignature Language="C#" Value="public sealed class ClusterHealthChunk" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ClusterHealthChunk extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ClusterHealthChunk" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ClusterHealthChunk" />
  <TypeSignature Language="F#" Value="type ClusterHealthChunk = class" />
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
            <span data-ttu-id="7e8b6-101">クラスターに関するヘルス情報が含まれて、クラスター状態チャンクを表します。</span><span class="sxs-lookup"><span data-stu-id="7e8b6-101">Represents the cluster state chunk, which includes health information about the cluster.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplicationHealthStateChunks">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ApplicationHealthStateChunkList ApplicationHealthStateChunks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ApplicationHealthStateChunkList ApplicationHealthStateChunks" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ClusterHealthChunk.ApplicationHealthStateChunks" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationHealthStateChunks As ApplicationHealthStateChunkList" />
      <MemberSignature Language="F#" Value="member this.ApplicationHealthStateChunks : System.Fabric.Health.ApplicationHealthStateChunkList" Usage="System.Fabric.Health.ClusterHealthChunk.ApplicationHealthStateChunks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ApplicationHealthStateChunkList</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7e8b6-102">アプリケーションの正常性の一覧に、入力フィルターを尊重状態チャンクを取得します。</span><span class="sxs-lookup"><span data-stu-id="7e8b6-102">Gets the list of the application health state chunks that respect the input filters.</span></span>
            </summary>
        <value><span data-ttu-id="7e8b6-103">入力フィルターを適用するアプリケーションのヘルス状態のチャンクの一覧。</span><span class="sxs-lookup"><span data-stu-id="7e8b6-103">The list of the application health state chunks that respect the input filters.</span></span></value>
        <remarks>
          <para><span data-ttu-id="7e8b6-104">既定では、子ない結果に含められます。</span><span class="sxs-lookup"><span data-stu-id="7e8b6-104">By default, no children are included in results.</span></span> <span data-ttu-id="7e8b6-105">ユーザーは、必要な正常性アドインまたはその他の情報に基づく子の一部を含めるように要求できます。</span><span class="sxs-lookup"><span data-stu-id="7e8b6-105">Users can request to include some children based on desired health or other information.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthState">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthState HealthState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthState HealthState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ClusterHealthChunk.HealthState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthState As HealthState" />
      <MemberSignature Language="F#" Value="member this.HealthState : System.Fabric.Health.HealthState" Usage="System.Fabric.Health.ClusterHealthChunk.HealthState" />
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
            <span data-ttu-id="7e8b6-106">集計されたクラスターの正常性状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="7e8b6-106">Gets the cluster aggregated health state.</span></span>
            </summary>
        <value><span data-ttu-id="7e8b6-107">クラスターの正常性状態の集計。</span><span class="sxs-lookup"><span data-stu-id="7e8b6-107">The cluster aggregated health state.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeHealthStateChunks">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.NodeHealthStateChunkList NodeHealthStateChunks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.NodeHealthStateChunkList NodeHealthStateChunks" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ClusterHealthChunk.NodeHealthStateChunks" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeHealthStateChunks As NodeHealthStateChunkList" />
      <MemberSignature Language="F#" Value="member this.NodeHealthStateChunks : System.Fabric.Health.NodeHealthStateChunkList" Usage="System.Fabric.Health.ClusterHealthChunk.NodeHealthStateChunks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.NodeHealthStateChunkList</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7e8b6-108">入力のフィルターを適用するヘルス状態のチャンクのノードの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="7e8b6-108">Gets the list of the node health state chunks that respect the input filters.</span></span>
            </summary>
        <value><span data-ttu-id="7e8b6-109">入力フィルターを適用するノードのヘルス状態のチャンクの一覧。</span><span class="sxs-lookup"><span data-stu-id="7e8b6-109">The list of the node health state chunks that respect the input filters.</span></span></value>
        <remarks>
          <para><span data-ttu-id="7e8b6-110">既定では、子ない結果に含められます。</span><span class="sxs-lookup"><span data-stu-id="7e8b6-110">By default, no children are included in results.</span></span> <span data-ttu-id="7e8b6-111">ユーザーは、必要な正常性アドインまたはその他の情報に基づく子の一部を含めるように要求できます。</span><span class="sxs-lookup"><span data-stu-id="7e8b6-111">Users can request to include some children based on desired health or other information.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ClusterHealthChunk.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="clusterHealthChunk.ToString " />
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
            <span data-ttu-id="7e8b6-112">クラスターのチャンクについて説明する文字列を作成します。</span><span class="sxs-lookup"><span data-stu-id="7e8b6-112">Creates a string description of the cluster chunk.</span></span>
            </summary>
        <returns><span data-ttu-id="7e8b6-113">クラスターのチャンクの説明の文字列を指定します。</span><span class="sxs-lookup"><span data-stu-id="7e8b6-113">String description of the cluster chunk.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>