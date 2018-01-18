<Type Name="ClusterLoadInformation" FullName="System.Fabric.Query.ClusterLoadInformation">
  <TypeSignature Language="C#" Value="public class ClusterLoadInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ClusterLoadInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.ClusterLoadInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class ClusterLoadInformation" />
  <TypeSignature Language="F#" Value="type ClusterLoadInformation = class" />
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
      <para><span data-ttu-id="a2d51-101">クラスターの読み込み情報を表します。</span><span class="sxs-lookup"><span data-stu-id="a2d51-101">Represents the cluster load information.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClusterLoadInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ClusterLoadInformation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="a2d51-102"><see cref="T:System.Fabric.Query.ClusterLoadInformation" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a2d51-102">Initializes a new instance of the <see cref="T:System.Fabric.Query.ClusterLoadInformation" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastBalancingEndTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime LastBalancingEndTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastBalancingEndTimeUtc" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ClusterLoadInformation.LastBalancingEndTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastBalancingEndTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastBalancingEndTimeUtc : DateTime" Usage="System.Fabric.Query.ClusterLoadInformation.LastBalancingEndTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="a2d51-103">最後のリソースの実行を負荷分散の (UTC) で終了時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="a2d51-103">Gets the end time (in UTC) of last resource balancing run.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="a2d51-104">最後のリソースの負荷分散の終了時刻を実行します。</span><span class="sxs-lookup"><span data-stu-id="a2d51-104">The end time of last resource balancing run.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastBalancingStartTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime LastBalancingStartTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastBalancingStartTimeUtc" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ClusterLoadInformation.LastBalancingStartTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastBalancingStartTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastBalancingStartTimeUtc : DateTime" Usage="System.Fabric.Query.ClusterLoadInformation.LastBalancingStartTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="a2d51-105">最後のリソースの実行を負荷分散の開始時刻 (UTC) でを取得します。</span><span class="sxs-lookup"><span data-stu-id="a2d51-105">Gets the starting time (in UTC) of last resource balancing run.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="a2d51-106">最後のリソースの負荷分散の開始時刻を実行します。</span><span class="sxs-lookup"><span data-stu-id="a2d51-106">The starting time of last resource balancing run.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadMetricInformationList">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Query.LoadMetricInformation&gt; LoadMetricInformationList { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Query.LoadMetricInformation&gt; LoadMetricInformationList" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ClusterLoadInformation.LoadMetricInformationList" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LoadMetricInformationList As IList(Of LoadMetricInformation)" />
      <MemberSignature Language="F#" Value="member this.LoadMetricInformationList : System.Collections.Generic.IList&lt;System.Fabric.Query.LoadMetricInformation&gt;" Usage="System.Fabric.Query.ClusterLoadInformation.LoadMetricInformationList" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Query.LoadMetricInformation&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="a2d51-107">負荷メトリック情報オブジェクトの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="a2d51-107">Gets a list of load metrics information object.</span></span> <span data-ttu-id="a2d51-108">各エントリは、特定のメトリック用です。</span><span class="sxs-lookup"><span data-stu-id="a2d51-108">Each entry is for a certain metrics.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="a2d51-109">負荷メトリック情報オブジェクトの一覧。</span><span class="sxs-lookup"><span data-stu-id="a2d51-109">A list of load metrics information object.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ClusterLoadInformation.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="clusterLoadInformation.ToString " />
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
          <para>
            <span data-ttu-id="a2d51-110">詳細をかなり印刷<see cref="T:System.Fabric.Query.ClusterLoadInformation" />です。</span><span class="sxs-lookup"><span data-stu-id="a2d51-110">Pretty print out details of <see cref="T:System.Fabric.Query.ClusterLoadInformation" />.</span></span>
            </para>
        </summary>
        <returns><span data-ttu-id="a2d51-111"><see cref="T:System.Fabric.Query.ClusterLoadInformation" /> の文字列形式。</span><span class="sxs-lookup"><span data-stu-id="a2d51-111">A string representation of the <see cref="T:System.Fabric.Query.ClusterLoadInformation" />.</span></span></returns>
        <remarks>To be added.</remarks>
        <example>
            <span data-ttu-id="a2d51-112">LastBalancingStartTimeUtc: 2015 年 11 月 9 日午後 8時 40分: 35 LastBalancingEndTimeUtc: 2015 年 11 月 9 日午後 8時 40分: 35 LoadMetricInformation: LoadMetricName: Metric1 IsBalancedBefore: IsBalancedAfter を True: DeviationBefore True: 2 DeviationAfter: 2 BalancingThreshold: 1 つの操作: NoActionNeeded ActivityThreshold: 3 ClusterCapacity: 100 ClusterLoad: 1 ClusterRemainingCapacity: 0 NodeBufferPercentage: 0 ClusterBufferedCapacity: 0 ClusterRemainingBufferedCapacity: 0 ClusterCapacityViolation: True MinNodeLoadValue: 0 MinNodeLoadNodeId: 1ca9521d70301383417536df0c96f671 MaxNodeLoadValue: 1 MaxNodeLoadNodeId: cf68563e16a44f808e86197a9cf83de5</span><span class="sxs-lookup"><span data-stu-id="a2d51-112">LastBalancingStartTimeUtc : 11/9/2015 8:40:35 PM LastBalancingEndTimeUtc   : 11/9/2015 8:40:35 PM LoadMetricInformation     : LoadMetricName        : Metric1 IsBalancedBefore      : True IsBalancedAfter       : True DeviationBefore       : 2 DeviationAfter        : 2 BalancingThreshold    : 1 Action    : NoActionNeeded ActivityThreshold     : 3 ClusterCapacity       : 100 ClusterLoad           : 1 ClusterRemainingCapacity : 0 NodeBufferPercentage  : 0 ClusterBufferedCapacity : 0 ClusterRemainingBufferedCapacity : 0 ClusterCapacityViolation : True MinNodeLoadValue      : 0 MinNodeLoadNodeId     : 1ca9521d70301383417536df0c96f671 MaxNodeLoadValue      : 1 MaxNodeLoadNodeId     : cf68563e16a44f808e86197a9cf83de5</span></span>
            </example>
      </Docs>
    </Member>
  </Members>
</Type>