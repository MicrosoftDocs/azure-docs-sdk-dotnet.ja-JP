<Type Name="PoolUsageMetrics" FullName="Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics">
  <TypeSignature Language="C#" Value="public class PoolUsageMetrics" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PoolUsageMetrics extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics" />
  <TypeSignature Language="VB.NET" Value="Public Class PoolUsageMetrics" />
  <TypeSignature Language="F#" Value="type PoolUsageMetrics = class" />
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
            <span data-ttu-id="13ebc-101">集計間隔の間でプールの使用状況メトリック。</span><span class="sxs-lookup"><span data-stu-id="13ebc-101">Usage metrics for a pool across an aggregation interval.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolUsageMetrics ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="13ebc-102">PoolUsageMetrics クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="13ebc-102">Initializes a new instance of the PoolUsageMetrics class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolUsageMetrics (string poolId, DateTime startTime, DateTime endTime, string vmSize, double totalCoreHours, double dataIngressGiB, double dataEgressGiB);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string poolId, valuetype System.DateTime startTime, valuetype System.DateTime endTime, string vmSize, float64 totalCoreHours, float64 dataIngressGiB, float64 dataEgressGiB) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics.#ctor(System.String,System.DateTime,System.DateTime,System.String,System.Double,System.Double,System.Double)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (poolId As String, startTime As DateTime, endTime As DateTime, vmSize As String, totalCoreHours As Double, dataIngressGiB As Double, dataEgressGiB As Double)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics : string * DateTime * DateTime * string * double * double * double -&gt; Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics" Usage="new Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics (poolId, startTime, endTime, vmSize, totalCoreHours, dataIngressGiB, dataEgressGiB)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="startTime" Type="System.DateTime" />
        <Parameter Name="endTime" Type="System.DateTime" />
        <Parameter Name="vmSize" Type="System.String" />
        <Parameter Name="totalCoreHours" Type="System.Double" />
        <Parameter Name="dataIngressGiB" Type="System.Double" />
        <Parameter Name="dataEgressGiB" Type="System.Double" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="13ebc-103">このエントリであるメトリックが集計されて、プールの ID。</span><span class="sxs-lookup"><span data-stu-id="13ebc-103">The ID of the pool whose metrics are aggregated in this entry.</span></span></param>
        <param name="startTime"><span data-ttu-id="13ebc-104">このエントリに含まれる集計範囲の開始時刻です。</span><span class="sxs-lookup"><span data-stu-id="13ebc-104">The start time of the aggregation interval covered by this entry.</span></span></param>
        <param name="endTime"><span data-ttu-id="13ebc-105">このエントリに含まれる集計範囲の終了時刻。</span><span class="sxs-lookup"><span data-stu-id="13ebc-105">The end time of the aggregation interval covered by this entry.</span></span></param>
        <param name="vmSize"><span data-ttu-id="13ebc-106">プール内の仮想マシンのサイズ。</span><span class="sxs-lookup"><span data-stu-id="13ebc-106">The size of virtual machines in the pool.</span></span> <span data-ttu-id="13ebc-107">プール内のすべての Vm は、同じサイズです。</span><span class="sxs-lookup"><span data-stu-id="13ebc-107">All VMs in a pool are the same size.</span></span></param>
        <param name="totalCoreHours"><span data-ttu-id="13ebc-108">この集計間隔の間に、プールで使用される合計コア時間。</span><span class="sxs-lookup"><span data-stu-id="13ebc-108">The total core hours used in the pool during this aggregation interval.</span></span></param>
        <param name="dataIngressGiB"><span data-ttu-id="13ebc-109">GiB で、この間隔中に、プールにクロス データ センター ネットワーク受信します。</span><span class="sxs-lookup"><span data-stu-id="13ebc-109">The cross data center network ingress to the pool during this interval, in GiB.</span></span></param>
        <param name="dataEgressGiB"><span data-ttu-id="13ebc-110">間のデータ センター ネットワーク送信 GiB で、この間隔の間にプールからです。</span><span class="sxs-lookup"><span data-stu-id="13ebc-110">The cross data center network egress from the pool during this interval, in GiB.</span></span></param>
        <summary>
            <span data-ttu-id="13ebc-111">PoolUsageMetrics クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="13ebc-111">Initializes a new instance of the PoolUsageMetrics class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataEgressGiB">
      <MemberSignature Language="C#" Value="public double DataEgressGiB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 DataEgressGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics.DataEgressGiB" />
      <MemberSignature Language="VB.NET" Value="Public Property DataEgressGiB As Double" />
      <MemberSignature Language="F#" Value="member this.DataEgressGiB : double with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics.DataEgressGiB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dataEgressGiB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="13ebc-112">取得または設定間のデータ センター ネットワーク出口プール GiB で、この間隔中にします。</span><span class="sxs-lookup"><span data-stu-id="13ebc-112">Gets or sets the cross data center network egress from the pool during this interval, in GiB.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataIngressGiB">
      <MemberSignature Language="C#" Value="public double DataIngressGiB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 DataIngressGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics.DataIngressGiB" />
      <MemberSignature Language="VB.NET" Value="Public Property DataIngressGiB As Double" />
      <MemberSignature Language="F#" Value="member this.DataIngressGiB : double with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics.DataIngressGiB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dataIngressGiB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="13ebc-113">取得または設定間のデータ センター ネットワーク受信プール GiB で、この間隔中にします。</span><span class="sxs-lookup"><span data-stu-id="13ebc-113">Gets or sets the cross data center network ingress to the pool during this interval, in GiB.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public DateTime EndTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public Property EndTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.EndTime : DateTime with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics.EndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="endTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="13ebc-114">取得または、このエントリに含まれる集計範囲の終了時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="13ebc-114">Gets or sets the end time of the aggregation interval covered by this entry.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PoolId">
      <MemberSignature Language="C#" Value="public string PoolId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PoolId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics.PoolId" />
      <MemberSignature Language="VB.NET" Value="Public Property PoolId As String" />
      <MemberSignature Language="F#" Value="member this.PoolId : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics.PoolId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="poolId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="13ebc-115">取得またはメトリックが集計されて、プールの ID をこのエントリに設定します。</span><span class="sxs-lookup"><span data-stu-id="13ebc-115">Gets or sets the ID of the pool whose metrics are aggregated in this entry.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public DateTime StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.StartTime : DateTime with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="13ebc-116">取得または、このエントリに含まれる集計範囲の開始時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="13ebc-116">Gets or sets the start time of the aggregation interval covered by this entry.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalCoreHours">
      <MemberSignature Language="C#" Value="public double TotalCoreHours { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 TotalCoreHours" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics.TotalCoreHours" />
      <MemberSignature Language="VB.NET" Value="Public Property TotalCoreHours As Double" />
      <MemberSignature Language="F#" Value="member this.TotalCoreHours : double with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics.TotalCoreHours" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="totalCoreHours")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="13ebc-117">取得またはこの集計間隔の間に、プールで使用される合計コア時間を設定します。</span><span class="sxs-lookup"><span data-stu-id="13ebc-117">Gets or sets the total core hours used in the pool during this aggregation interval.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="poolUsageMetrics.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="13ebc-118">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="13ebc-118">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="13ebc-119">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="13ebc-119">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VmSize">
      <MemberSignature Language="C#" Value="public string VmSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VmSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics.VmSize" />
      <MemberSignature Language="VB.NET" Value="Public Property VmSize As String" />
      <MemberSignature Language="F#" Value="member this.VmSize : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics.VmSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="vmSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="13ebc-120">取得またはプール内の仮想マシンのサイズを設定します。</span><span class="sxs-lookup"><span data-stu-id="13ebc-120">Gets or sets the size of virtual machines in the pool.</span></span> <span data-ttu-id="13ebc-121">プール内のすべての Vm は、同じサイズです。</span><span class="sxs-lookup"><span data-stu-id="13ebc-121">All VMs in a pool are the same size.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="13ebc-122">クラウド サービス プール (プール cloudServiceConfiguration で作成された) の仮想マシンの利用可能なサイズについては、クラウド サービス (http://azure.microsoft.com/documentation/articles/cloud-services-sizes-specs/) のサイズを参照してください。</span><span class="sxs-lookup"><span data-stu-id="13ebc-122">For information about available sizes of virtual machines for Cloud Services pools (pools created with cloudServiceConfiguration), see Sizes for Cloud Services (http://azure.microsoft.com/documentation/articles/cloud-services-sizes-specs/).</span></span>
            <span data-ttu-id="13ebc-123">バッチには、ExtraSmall、STANDARD_A1_V2 STANDARD_A2_V2 を除くすべてのクラウド サービス VM サイズがサポートしています。</span><span class="sxs-lookup"><span data-stu-id="13ebc-123">Batch supports all Cloud Services VM sizes except ExtraSmall, STANDARD_A1_V2 and STANDARD_A2_V2.</span></span> <span data-ttu-id="13ebc-124">(プール virtualMachineConfiguration で作成した) 仮想マシンのマーケットプ レースからイメージを使用するプールの利用可能な VM サイズについては (Linux) (https://azure.microsoft.com/documentation/articles/ の仮想マシンのサイズを参照してください。仮想マシンの linux-サイズ/) または仮想マシン (Windows) (https://azure.microsoft.com/documentation/articles/virtual-machines-windows-sizes/) のサイズ。</span><span class="sxs-lookup"><span data-stu-id="13ebc-124">For information about available VM sizes for pools using images from the Virtual Machines Marketplace (pools created with virtualMachineConfiguration) see Sizes for Virtual Machines (Linux) (https://azure.microsoft.com/documentation/articles/virtual-machines-linux-sizes/) or Sizes for Virtual Machines (Windows) (https://azure.microsoft.com/documentation/articles/virtual-machines-windows-sizes/).</span></span>
            <span data-ttu-id="13ebc-125">バッチには、STANDARD_A0 と premium storage (STANDARD_GS、STANDARD_DS、および STANDARD_DSV2 シリーズ) でそれらを除くすべての Azure VM サイズがサポートしています。</span><span class="sxs-lookup"><span data-stu-id="13ebc-125">Batch supports all Azure VM sizes except STANDARD_A0 and those with premium storage (STANDARD_GS, STANDARD_DS, and STANDARD_DSV2 series).</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>