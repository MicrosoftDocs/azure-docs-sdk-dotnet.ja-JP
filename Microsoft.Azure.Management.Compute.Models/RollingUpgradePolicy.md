<Type Name="RollingUpgradePolicy" FullName="Microsoft.Azure.Management.Compute.Models.RollingUpgradePolicy">
  <TypeSignature Language="C#" Value="public class RollingUpgradePolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RollingUpgradePolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.RollingUpgradePolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class RollingUpgradePolicy" />
  <TypeSignature Language="F#" Value="type RollingUpgradePolicy = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f53a5-101">ローリング アップグレードの実行中に使用される構成パラメーター。</span><span class="sxs-lookup"><span data-stu-id="f53a5-101">The configuration parameters used while performing a rolling upgrade.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RollingUpgradePolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.RollingUpgradePolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f53a5-102">RollingUpgradePolicy クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f53a5-102">Initializes a new instance of the RollingUpgradePolicy class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RollingUpgradePolicy (Nullable&lt;int&gt; maxBatchInstancePercent = null, Nullable&lt;int&gt; maxUnhealthyInstancePercent = null, Nullable&lt;int&gt; maxUnhealthyUpgradedInstancePercent = null, string pauseTimeBetweenBatches = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; maxBatchInstancePercent, valuetype System.Nullable`1&lt;int32&gt; maxUnhealthyInstancePercent, valuetype System.Nullable`1&lt;int32&gt; maxUnhealthyUpgradedInstancePercent, string pauseTimeBetweenBatches) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.RollingUpgradePolicy.#ctor(System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional maxBatchInstancePercent As Nullable(Of Integer) = null, Optional maxUnhealthyInstancePercent As Nullable(Of Integer) = null, Optional maxUnhealthyUpgradedInstancePercent As Nullable(Of Integer) = null, Optional pauseTimeBetweenBatches As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.RollingUpgradePolicy : Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * string -&gt; Microsoft.Azure.Management.Compute.Models.RollingUpgradePolicy" Usage="new Microsoft.Azure.Management.Compute.Models.RollingUpgradePolicy (maxBatchInstancePercent, maxUnhealthyInstancePercent, maxUnhealthyUpgradedInstancePercent, pauseTimeBetweenBatches)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="maxBatchInstancePercent" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="maxUnhealthyInstancePercent" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="maxUnhealthyUpgradedInstancePercent" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="pauseTimeBetweenBatches" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="maxBatchInstancePercent"><span data-ttu-id="f53a5-103">1 つのバッチでローリング アップグレードを同時にアップグレードする場合は合計の仮想マシン インスタンスの最大比率。</span><span class="sxs-lookup"><span data-stu-id="f53a5-103">The maximum percent of total virtual machine instances that will be upgraded simultaneously by the rolling upgrade in one batch.</span></span> <span data-ttu-id="f53a5-104">これは、最大、以前または将来のバッチで異常なインスタンスはインスタンスの割合を高い信頼性を確保に低下するためのバッチに可能性があります。</span><span class="sxs-lookup"><span data-stu-id="f53a5-104">As this is a maximum, unhealthy instances in previous or future batches can cause the percentage of instances in a batch to decrease to ensure higher reliability.</span></span> <span data-ttu-id="f53a5-105">このパラメーターの既定値は、20% です。</span><span class="sxs-lookup"><span data-stu-id="f53a5-105">The default value for this parameter is 20%.</span></span></param>
        <param name="maxUnhealthyInstancePercent"><span data-ttu-id="f53a5-106">同時に異常な状態、アップグレード中の結果として、またはが異常な状態で仮想マシンの正常性チェックでローリング アップグレードが中止される前に、できるスケール セット内の合計の仮想マシン インスタンスの最大パーセンテージです。</span><span class="sxs-lookup"><span data-stu-id="f53a5-106">The maximum percentage of the total virtual machine instances in the scale set that can be simultaneously unhealthy, either as a result of being upgraded, or by being found in an unhealthy state by the virtual machine health checks before the rolling upgrade aborts.</span></span> <span data-ttu-id="f53a5-107">すべてのバッチを開始する前にこの制約がチェックされます。</span><span class="sxs-lookup"><span data-stu-id="f53a5-107">This constraint will be checked prior to starting any batch.</span></span> <span data-ttu-id="f53a5-108">このパラメーターの既定値は、20% です。</span><span class="sxs-lookup"><span data-stu-id="f53a5-108">The default value for this parameter is 20%.</span></span></param>
        <param name="maxUnhealthyUpgradedInstancePercent"><span data-ttu-id="f53a5-109">異常な状態にするのにはありますアップグレードした仮想マシン インスタンスの最大のパーセンテージです。</span><span class="sxs-lookup"><span data-stu-id="f53a5-109">The maximum percentage of upgraded virtual machine instances that can be found to be in an unhealthy state.</span></span> <span data-ttu-id="f53a5-110">このチェックは、各バッチがアップグレードされた後に発生します。</span><span class="sxs-lookup"><span data-stu-id="f53a5-110">This check will happen after each batch is upgraded.</span></span> <span data-ttu-id="f53a5-111">この割合は、これまで超えた場合、ローリング アップデートを中止します。</span><span class="sxs-lookup"><span data-stu-id="f53a5-111">If this percentage is ever exceeded, the rolling update aborts.</span></span> <span data-ttu-id="f53a5-112">このパラメーターの既定値は、20% です。</span><span class="sxs-lookup"><span data-stu-id="f53a5-112">The default value for this parameter is 20%.</span></span></param>
        <param name="pauseTimeBetweenBatches"><span data-ttu-id="f53a5-113">次のバッチを開始する 1 つのバッチ内のすべての仮想マシン用の更新プログラムを完了するまでの待機時間。</span><span class="sxs-lookup"><span data-stu-id="f53a5-113">The wait time between completing the update for all virtual machines in one batch and starting the next batch.</span></span> <span data-ttu-id="f53a5-114">継続時間は、ISO 8601 形式で指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f53a5-114">The time duration should be specified in ISO 8601 format.</span></span> <span data-ttu-id="f53a5-115">既定値は、0 秒 (pt0s ですです)。</span><span class="sxs-lookup"><span data-stu-id="f53a5-115">The default value is 0 seconds (PT0S).</span></span></param>
        <summary>
            <span data-ttu-id="f53a5-116">RollingUpgradePolicy クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f53a5-116">Initializes a new instance of the RollingUpgradePolicy class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBatchInstancePercent">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxBatchInstancePercent { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxBatchInstancePercent" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.RollingUpgradePolicy.MaxBatchInstancePercent" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBatchInstancePercent As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxBatchInstancePercent : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.RollingUpgradePolicy.MaxBatchInstancePercent" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxBatchInstancePercent")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f53a5-117">取得または 1 つのバッチでローリング アップグレード時に、同時にアップグレードされる合計の仮想マシン インスタンスの最大割合を設定します。</span><span class="sxs-lookup"><span data-stu-id="f53a5-117">Gets or sets the maximum percent of total virtual machine instances that will be upgraded simultaneously by the rolling upgrade in one batch.</span></span> <span data-ttu-id="f53a5-118">これは、最大、以前または将来のバッチで異常なインスタンスはインスタンスの割合を高い信頼性を確保に低下するためのバッチに可能性があります。</span><span class="sxs-lookup"><span data-stu-id="f53a5-118">As this is a maximum, unhealthy instances in previous or future batches can cause the percentage of instances in a batch to decrease to ensure higher reliability.</span></span> <span data-ttu-id="f53a5-119">このパラメーターの既定値は、20% です。</span><span class="sxs-lookup"><span data-stu-id="f53a5-119">The default value for this parameter is 20%.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxUnhealthyInstancePercent">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxUnhealthyInstancePercent { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxUnhealthyInstancePercent" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.RollingUpgradePolicy.MaxUnhealthyInstancePercent" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxUnhealthyInstancePercent As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxUnhealthyInstancePercent : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.RollingUpgradePolicy.MaxUnhealthyInstancePercent" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxUnhealthyInstancePercent")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f53a5-120">取得または同時に異常な状態、アップグレード中の結果として、または異常な状態で、公開する前に、仮想マシンの正常性チェックで見つかったしてできるスケール セット内の合計仮想マシン インスタンスの最大パーセンテージを設定アップグレードを中止します。</span><span class="sxs-lookup"><span data-stu-id="f53a5-120">Gets or sets the maximum percentage of the total virtual machine instances in the scale set that can be simultaneously unhealthy, either as a result of being upgraded, or by being found in an unhealthy state by the virtual machine health checks before the rolling upgrade aborts.</span></span> <span data-ttu-id="f53a5-121">すべてのバッチを開始する前にこの制約がチェックされます。</span><span class="sxs-lookup"><span data-stu-id="f53a5-121">This constraint will be checked prior to starting any batch.</span></span> <span data-ttu-id="f53a5-122">このパラメーターの既定値は、20% です。</span><span class="sxs-lookup"><span data-stu-id="f53a5-122">The default value for this parameter is 20%.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxUnhealthyUpgradedInstancePercent">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxUnhealthyUpgradedInstancePercent { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxUnhealthyUpgradedInstancePercent" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.RollingUpgradePolicy.MaxUnhealthyUpgradedInstancePercent" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxUnhealthyUpgradedInstancePercent As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxUnhealthyUpgradedInstancePercent : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.RollingUpgradePolicy.MaxUnhealthyUpgradedInstancePercent" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxUnhealthyUpgradedInstancePercent")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f53a5-123">取得または異常な状態にするのにはありますアップグレードした仮想マシン インスタンスの最大パーセンテージを設定します。</span><span class="sxs-lookup"><span data-stu-id="f53a5-123">Gets or sets the maximum percentage of upgraded virtual machine instances that can be found to be in an unhealthy state.</span></span> <span data-ttu-id="f53a5-124">このチェックは、各バッチがアップグレードされた後に発生します。</span><span class="sxs-lookup"><span data-stu-id="f53a5-124">This check will happen after each batch is upgraded.</span></span> <span data-ttu-id="f53a5-125">この割合は、これまで超えた場合、ローリング アップデートを中止します。</span><span class="sxs-lookup"><span data-stu-id="f53a5-125">If this percentage is ever exceeded, the rolling update aborts.</span></span> <span data-ttu-id="f53a5-126">このパラメーターの既定値は、20% です。</span><span class="sxs-lookup"><span data-stu-id="f53a5-126">The default value for this parameter is 20%.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PauseTimeBetweenBatches">
      <MemberSignature Language="C#" Value="public string PauseTimeBetweenBatches { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PauseTimeBetweenBatches" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.RollingUpgradePolicy.PauseTimeBetweenBatches" />
      <MemberSignature Language="VB.NET" Value="Public Property PauseTimeBetweenBatches As String" />
      <MemberSignature Language="F#" Value="member this.PauseTimeBetweenBatches : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.RollingUpgradePolicy.PauseTimeBetweenBatches" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pauseTimeBetweenBatches")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f53a5-127">取得または次のバッチを開始する 1 つのバッチ内のすべての仮想マシン用の更新プログラムを完了するまでの待機時間を設定します。</span><span class="sxs-lookup"><span data-stu-id="f53a5-127">Gets or sets the wait time between completing the update for all virtual machines in one batch and starting the next batch.</span></span> <span data-ttu-id="f53a5-128">継続時間は、ISO 8601 形式で指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f53a5-128">The time duration should be specified in ISO 8601 format.</span></span> <span data-ttu-id="f53a5-129">既定値は、0 秒 (pt0s ですです)。</span><span class="sxs-lookup"><span data-stu-id="f53a5-129">The default value is 0 seconds (PT0S).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.RollingUpgradePolicy.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="rollingUpgradePolicy.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f53a5-130">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="f53a5-130">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f53a5-131">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f53a5-131">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>