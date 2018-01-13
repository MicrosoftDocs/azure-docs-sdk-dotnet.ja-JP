<Type Name="ResourceStatistics" FullName="Microsoft.Azure.Batch.ResourceStatistics">
  <TypeSignature Language="C#" Value="public class ResourceStatistics" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceStatistics extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.ResourceStatistics" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceStatistics" />
  <TypeSignature Language="F#" Value="type ResourceStatistics = class&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e8d36-101">プールのリソースの統計データ。</span><span class="sxs-lookup"><span data-stu-id="e8d36-101">The resource statistics data for the pool.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AverageCpuPercentage">
      <MemberSignature Language="C#" Value="public double AverageCpuPercentage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 AverageCpuPercentage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ResourceStatistics.AverageCpuPercentage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AverageCpuPercentage As Double" />
      <MemberSignature Language="F#" Value="member this.AverageCpuPercentage : double" Usage="Microsoft.Azure.Batch.ResourceStatistics.AverageCpuPercentage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e8d36-102">プール (コンピューティング ノードごとの割合) 内のすべてのコンピューティング ノードでは、平均 CPU 使用率を取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d36-102">Gets the average CPU usage across all compute nodes in the pool (percentage per compute node).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AverageDiskGiB">
      <MemberSignature Language="C#" Value="public double AverageDiskGiB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 AverageDiskGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ResourceStatistics.AverageDiskGiB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AverageDiskGiB As Double" />
      <MemberSignature Language="F#" Value="member this.AverageDiskGiB : double" Usage="Microsoft.Azure.Batch.ResourceStatistics.AverageDiskGiB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e8d36-103">プール内のすべてのコンピューティング ノードで gibibytes で平均の使用済みディスク領域を取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d36-103">Gets the average used disk space in gibibytes across all compute nodes in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AverageMemoryGiB">
      <MemberSignature Language="C#" Value="public double AverageMemoryGiB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 AverageMemoryGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ResourceStatistics.AverageMemoryGiB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AverageMemoryGiB As Double" />
      <MemberSignature Language="F#" Value="member this.AverageMemoryGiB : double" Usage="Microsoft.Azure.Batch.ResourceStatistics.AverageMemoryGiB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e8d36-104">プール内のすべてのコンピューティング ノードで gibibytes 内のメモリ平均使用量を取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d36-104">Gets the average memory usage in gibibytes across all compute nodes in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiskReadGiB">
      <MemberSignature Language="C#" Value="public double DiskReadGiB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 DiskReadGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ResourceStatistics.DiskReadGiB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DiskReadGiB As Double" />
      <MemberSignature Language="F#" Value="member this.DiskReadGiB : double" Usage="Microsoft.Azure.Batch.ResourceStatistics.DiskReadGiB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e8d36-105">プール内のすべてのコンピューティング ノードでディスクの読み取り gibibytes 内のデータの合計サイズを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d36-105">Gets the total amount of data in gibibytes of disk reads across all compute nodes in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiskReadIOps">
      <MemberSignature Language="C#" Value="public long DiskReadIOps { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DiskReadIOps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ResourceStatistics.DiskReadIOps" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DiskReadIOps As Long" />
      <MemberSignature Language="F#" Value="member this.DiskReadIOps : int64" Usage="Microsoft.Azure.Batch.ResourceStatistics.DiskReadIOps" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e8d36-106">ディスクのプール内のすべてのコンピューティング ノード間で読み込み操作の合計数を取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d36-106">Gets the total number of disk read operations across all compute nodes in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiskWriteGiB">
      <MemberSignature Language="C#" Value="public double DiskWriteGiB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 DiskWriteGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ResourceStatistics.DiskWriteGiB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DiskWriteGiB As Double" />
      <MemberSignature Language="F#" Value="member this.DiskWriteGiB : double" Usage="Microsoft.Azure.Batch.ResourceStatistics.DiskWriteGiB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e8d36-107">プール内のすべてのコンピューティング ノードでディスクの書き込み gibibytes 内のデータの合計サイズを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d36-107">Gets the total amount of data in gibibytes of disk writes across all compute nodes in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiskWriteIOps">
      <MemberSignature Language="C#" Value="public long DiskWriteIOps { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DiskWriteIOps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ResourceStatistics.DiskWriteIOps" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DiskWriteIOps As Long" />
      <MemberSignature Language="F#" Value="member this.DiskWriteIOps : int64" Usage="Microsoft.Azure.Batch.ResourceStatistics.DiskWriteIOps" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e8d36-108">プール内のすべてのコンピューティング ノードでディスクの書き込み操作の合計数を取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d36-108">Gets the total number of disk write operations across all compute nodes in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastUpdateTime">
      <MemberSignature Language="C#" Value="public DateTime LastUpdateTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastUpdateTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ResourceStatistics.LastUpdateTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastUpdateTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastUpdateTime : DateTime" Usage="Microsoft.Azure.Batch.ResourceStatistics.LastUpdateTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e8d36-109">これで、統計の最終更新時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d36-109">Gets the time at which the statistics were last updated.</span></span> <span data-ttu-id="e8d36-110">すべての統計情報は間の範囲に制限されて<see cref="P:Microsoft.Azure.Batch.ResourceStatistics.StartTime" />とこの値。</span><span class="sxs-lookup"><span data-stu-id="e8d36-110">All statistics are limited to the range between <see cref="P:Microsoft.Azure.Batch.ResourceStatistics.StartTime" /> and this value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkReadGiB">
      <MemberSignature Language="C#" Value="public double NetworkReadGiB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 NetworkReadGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ResourceStatistics.NetworkReadGiB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NetworkReadGiB As Double" />
      <MemberSignature Language="F#" Value="member this.NetworkReadGiB : double" Usage="Microsoft.Azure.Batch.ResourceStatistics.NetworkReadGiB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e8d36-111">プール内のすべてのコンピューティング ノードでネットワークの読み取りの gibibytes 内のデータの合計サイズを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d36-111">Gets the total amount of data in gibibytes of network reads across all compute nodes in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkWriteGiB">
      <MemberSignature Language="C#" Value="public double NetworkWriteGiB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 NetworkWriteGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ResourceStatistics.NetworkWriteGiB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NetworkWriteGiB As Double" />
      <MemberSignature Language="F#" Value="member this.NetworkWriteGiB : double" Usage="Microsoft.Azure.Batch.ResourceStatistics.NetworkWriteGiB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e8d36-112">プール内のすべてのコンピューティング ノード間でネットワークの書き込みの gibibytes 内のデータの合計サイズを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d36-112">Gets the total amount of data in gibibytes of network writes across all compute nodes in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeakDiskGiB">
      <MemberSignature Language="C#" Value="public double PeakDiskGiB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 PeakDiskGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ResourceStatistics.PeakDiskGiB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PeakDiskGiB As Double" />
      <MemberSignature Language="F#" Value="member this.PeakDiskGiB : double" Usage="Microsoft.Azure.Batch.ResourceStatistics.PeakDiskGiB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e8d36-113">プール内のすべてのコンピューティング ノードで gibibytes でピーク時使用ディスク領域を取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d36-113">Gets the peak used disk space in gibibytes across all compute nodes in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeakMemoryGiB">
      <MemberSignature Language="C#" Value="public double PeakMemoryGiB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 PeakMemoryGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ResourceStatistics.PeakMemoryGiB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PeakMemoryGiB As Double" />
      <MemberSignature Language="F#" Value="member this.PeakMemoryGiB : double" Usage="Microsoft.Azure.Batch.ResourceStatistics.PeakMemoryGiB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e8d36-114">プール内のすべてのコンピューティング ノードで gibibytes のピーク時のメモリ使用量を取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d36-114">Gets the peak memory usage in gibibytes across all compute nodes in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public DateTime StartTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ResourceStatistics.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.StartTime : DateTime" Usage="Microsoft.Azure.Batch.ResourceStatistics.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e8d36-115">統計情報の時間範囲の開始時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d36-115">Gets the start time of the time range covered by the statistics.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>