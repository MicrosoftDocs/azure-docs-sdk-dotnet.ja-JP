<Type Name="PoolUsageMetrics" FullName="Microsoft.Azure.Batch.PoolUsageMetrics">
  <TypeSignature Language="C#" Value="public class PoolUsageMetrics" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PoolUsageMetrics extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.PoolUsageMetrics" />
  <TypeSignature Language="VB.NET" Value="Public Class PoolUsageMetrics" />
  <TypeSignature Language="F#" Value="type PoolUsageMetrics = class&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            <span data-ttu-id="79506-101">特定の時間の範囲内の 1 つのプールの使用状況メトリック。</span><span class="sxs-lookup"><span data-stu-id="79506-101">The usage metrics for a single pool in a certain time range.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DataEgressGiB">
      <MemberSignature Language="C#" Value="public double DataEgressGiB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 DataEgressGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolUsageMetrics.DataEgressGiB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DataEgressGiB As Double" />
      <MemberSignature Language="F#" Value="member this.DataEgressGiB : double" Usage="Microsoft.Azure.Batch.PoolUsageMetrics.DataEgressGiB" />
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
            <span data-ttu-id="79506-102">Gibibytes で、この間隔中に、プールからの間のデータ センター ネットワーク送信を取得します。</span><span class="sxs-lookup"><span data-stu-id="79506-102">Gets the cross data center network egress from the pool during this interval, in gibibytes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataIngressGiB">
      <MemberSignature Language="C#" Value="public double DataIngressGiB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 DataIngressGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolUsageMetrics.DataIngressGiB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DataIngressGiB As Double" />
      <MemberSignature Language="F#" Value="member this.DataIngressGiB : double" Usage="Microsoft.Azure.Batch.PoolUsageMetrics.DataIngressGiB" />
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
            <span data-ttu-id="79506-103">Gibibytes で、この間隔中には、プールには、クロス データ センター ネットワーク受信を取得します。</span><span class="sxs-lookup"><span data-stu-id="79506-103">Gets the cross data center network ingress to the pool during this interval, in gibibytes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public DateTime EndTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolUsageMetrics.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EndTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.EndTime : DateTime" Usage="Microsoft.Azure.Batch.PoolUsageMetrics.EndTime" />
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
            <span data-ttu-id="79506-104">このエントリの集計間隔の終了時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="79506-104">Gets the end time of the aggregation interval for this entry.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PoolId">
      <MemberSignature Language="C#" Value="public string PoolId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PoolId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolUsageMetrics.PoolId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PoolId As String" />
      <MemberSignature Language="F#" Value="member this.PoolId : string" Usage="Microsoft.Azure.Batch.PoolUsageMetrics.PoolId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="79506-105">このエントリであるメトリックが集計されて、プールの id を取得します。</span><span class="sxs-lookup"><span data-stu-id="79506-105">Gets the id of the pool whose metrics are aggregated in this entry.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public DateTime StartTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolUsageMetrics.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.StartTime : DateTime" Usage="Microsoft.Azure.Batch.PoolUsageMetrics.StartTime" />
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
            <span data-ttu-id="79506-106">このエントリに含まれる集計範囲の開始時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="79506-106">Gets the start time of the aggregation interval covered by this entry.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalCoreHours">
      <MemberSignature Language="C#" Value="public double TotalCoreHours { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 TotalCoreHours" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolUsageMetrics.TotalCoreHours" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalCoreHours As Double" />
      <MemberSignature Language="F#" Value="member this.TotalCoreHours : double" Usage="Microsoft.Azure.Batch.PoolUsageMetrics.TotalCoreHours" />
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
            <span data-ttu-id="79506-107">この集計間隔の間に、プールで使用される合計コア時間を取得します。</span><span class="sxs-lookup"><span data-stu-id="79506-107">Gets the total core hours used in the pool during this aggregation interval.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineSize">
      <MemberSignature Language="C#" Value="public string VirtualMachineSize { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VirtualMachineSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolUsageMetrics.VirtualMachineSize" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualMachineSize As String" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineSize : string" Usage="Microsoft.Azure.Batch.PoolUsageMetrics.VirtualMachineSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="79506-108">プール内の仮想マシンのサイズを取得します。</span><span class="sxs-lookup"><span data-stu-id="79506-108">Gets the size of the virtual machines in the pool.</span></span>  <span data-ttu-id="79506-109">プール内の仮想マシンのサイズはすべて同じです。</span><span class="sxs-lookup"><span data-stu-id="79506-109">All virtual machines in a pool are the same size.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para><span data-ttu-id="79506-110">クラウド サービス プールの仮想マシンの利用可能なサイズについて (で作成されたプール、 <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" />)、https://azure.microsoft.com/documentation/articles/cloud-services-sizes-specs/ を参照してください。</span><span class="sxs-lookup"><span data-stu-id="79506-110">For information about available sizes of virtual machines for Cloud Services pools (pools created with a <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" />), see https://azure.microsoft.com/documentation/articles/cloud-services-sizes-specs/.</span></span> <span data-ttu-id="79506-111">バッチには、ExtraSmall を除くすべてのクラウド サービス VM サイズがサポートしています。</span><span class="sxs-lookup"><span data-stu-id="79506-111">Batch supports all Cloud Services VM sizes except ExtraSmall.</span></span></para>
          <para><span data-ttu-id="79506-112">仮想マシンのマーケットプ レースからイメージを使用するプールの利用可能な VM サイズについては (で作成されたプール、 <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" />) https://azure.microsoft.com/documentation/articles/virtual-machines-linux-sizes/ または https:// を参照してくださいazure.microsoft.com/documentation/articles/virtual-machines-windows-sizes/ です。</span><span class="sxs-lookup"><span data-stu-id="79506-112">For information about available VM sizes for pools using images from the Virtual Machines Marketplace (pools created with a <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" />) see https://azure.microsoft.com/documentation/articles/virtual-machines-linux-sizes/ or https://azure.microsoft.com/documentation/articles/virtual-machines-windows-sizes/.</span></span> <span data-ttu-id="79506-113">バッチには、STANDARD_A0 と premium storage (たとえば STANDARD_GS、STANDARD_DS、および STANDARD_DSV2 シリーズ) でそれらを除くすべての Azure VM サイズがサポートしています。</span><span class="sxs-lookup"><span data-stu-id="79506-113">Batch supports all Azure VM sizes except STANDARD_A0 and those with premium storage (for example STANDARD_GS, STANDARD_DS, and STANDARD_DSV2 series).</span></span></para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>