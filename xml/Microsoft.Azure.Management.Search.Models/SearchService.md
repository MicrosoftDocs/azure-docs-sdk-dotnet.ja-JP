<Type Name="SearchService" FullName="Microsoft.Azure.Management.Search.Models.SearchService">
  <TypeSignature Language="C#" Value="public class SearchService : Microsoft.Azure.Management.Search.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SearchService extends Microsoft.Azure.Management.Search.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Search.Models.SearchService" />
  <TypeSignature Language="VB.NET" Value="Public Class SearchService&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type SearchService = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Search.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="7e7ce-101">Azure Search サービスとその現在の状態について説明します。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-101">Describes an Azure Search service and its current state.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SearchService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.Models.SearchService.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7e7ce-102">SearchService クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-102">Initializes a new instance of the SearchService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SearchService (string location, Microsoft.Azure.Management.Search.Models.Sku sku, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Nullable&lt;int&gt; replicaCount = null, Nullable&lt;int&gt; partitionCount = null, Nullable&lt;Microsoft.Azure.Management.Search.Models.HostingMode&gt; hostingMode = null, Nullable&lt;Microsoft.Azure.Management.Search.Models.SearchServiceStatus&gt; status = null, string statusDetails = null, Nullable&lt;Microsoft.Azure.Management.Search.Models.ProvisioningState&gt; provisioningState = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, class Microsoft.Azure.Management.Search.Models.Sku sku, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Nullable`1&lt;int32&gt; replicaCount, valuetype System.Nullable`1&lt;int32&gt; partitionCount, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Search.Models.HostingMode&gt; hostingMode, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Search.Models.SearchServiceStatus&gt; status, string statusDetails, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Search.Models.ProvisioningState&gt; provisioningState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.Models.SearchService.#ctor(System.String,Microsoft.Azure.Management.Search.Models.Sku,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{Microsoft.Azure.Management.Search.Models.HostingMode},System.Nullable{Microsoft.Azure.Management.Search.Models.SearchServiceStatus},System.String,System.Nullable{Microsoft.Azure.Management.Search.Models.ProvisioningState})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Search.Models.SearchService : string * Microsoft.Azure.Management.Search.Models.Sku * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;Microsoft.Azure.Management.Search.Models.HostingMode&gt; * Nullable&lt;Microsoft.Azure.Management.Search.Models.SearchServiceStatus&gt; * string * Nullable&lt;Microsoft.Azure.Management.Search.Models.ProvisioningState&gt; -&gt; Microsoft.Azure.Management.Search.Models.SearchService" Usage="new Microsoft.Azure.Management.Search.Models.SearchService (location, sku, id, name, type, tags, replicaCount, partitionCount, hostingMode, status, statusDetails, provisioningState)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.Search.Models.Sku" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="replicaCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="partitionCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="hostingMode" Type="System.Nullable&lt;Microsoft.Azure.Management.Search.Models.HostingMode&gt;" />
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.Search.Models.SearchServiceStatus&gt;" />
        <Parameter Name="statusDetails" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.Nullable&lt;Microsoft.Azure.Management.Search.Models.ProvisioningState&gt;" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="7e7ce-103">リソースの地理的な場所です。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-103">The geographic location of the resource.</span></span>
            <span data-ttu-id="7e7ce-104">サポートされており、登録済みの Azure の Geo リージョンは (たとえば、米国西部、米国東部、東南アジアなど) の 1 つがあります。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-104">This must be one of the supported and registered Azure Geo Regions (for example, West US, East US, Southeast Asia, and so forth).</span></span></param>
        <param name="sku"><span data-ttu-id="7e7ce-105">SKU を決定する検索サービスの価格レベルと容量の制限。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-105">The SKU of the Search Service, which determines price tier and capacity limits.</span></span></param>
        <param name="id"><span data-ttu-id="7e7ce-106">リソースの ID。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-106">The ID of the resource.</span></span> <span data-ttu-id="7e7ce-107">これは、使用できます、Azure リソース マネージャーにリソースを相互にリンクします。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-107">This can be used with the Azure Resource Manager to link resources together.</span></span></param>
        <param name="name"><span data-ttu-id="7e7ce-108">リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-108">The name of the resource.</span></span></param>
        <param name="type"><span data-ttu-id="7e7ce-109">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-109">The resource type.</span></span></param>
        <param name="tags"><span data-ttu-id="7e7ce-110">Azure ポータルでリソースを分類するためにタグを付けます。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-110">Tags to help categorize the resource in the Azure portal.</span></span></param>
        <param name="replicaCount"><span data-ttu-id="7e7ce-111">Search サービス内のレプリカの数。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-111">The number of replicas in the Search service.</span></span> <span data-ttu-id="7e7ce-112">指定した場合は、1 から 12 standard Sku の間、または 1 ~ 3 の基本的な SKU の包括的で値を指定してする必要があります。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-112">If specified, it must be a value between 1 and 12 inclusive for standard SKUs or between 1 and 3 inclusive for basic SKU.</span></span></param>
        <param name="partitionCount"><span data-ttu-id="7e7ce-113">検索サービスのパーティションの数指定した場合は、1、2、3、4、6、または 12 にできます。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-113">The number of partitions in the Search service; if specified, it can be 1, 2, 3, 4, 6, or 12.</span></span>
            <span data-ttu-id="7e7ce-114">1 より大きい値では、標準 Sku 有効のみです。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-114">Values greater than 1 are only valid for standard SKUs.</span></span> <span data-ttu-id="7e7ce-115">HostingMode 'highDensity' éý 'standard3' サービスの有効な値は 1 ~ 3 の範囲です。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-115">For 'standard3' services with hostingMode set to 'highDensity', the allowed values are between 1 and 3.</span></span></param>
        <param name="hostingMode"><span data-ttu-id="7e7ce-116">Standard3 SKU にのみ適用できます。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-116">Applicable only for the standard3 SKU.</span></span>
            <span data-ttu-id="7e7ce-117">他の任意の SKU で許可される最大のインデックスよりも多くは最大で 1,000 個のインデックスを許可する最大 3 つの高密度パーティションを有効にするには、このプロパティを設定することができます。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-117">You can set this property to enable up to 3 high density partitions that allow up to 1000 indexes, which is much higher than the maximum indexes allowed for any other SKU.</span></span> <span data-ttu-id="7e7ce-118">Standard3 SKU 値は 'default' または 'highDensity' のいずれかです。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-118">For the standard3 SKU, the value is either 'default' or 'highDensity'.</span></span>
            <span data-ttu-id="7e7ce-119">その他のすべての Sku では、この値は 'default' をする必要があります。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-119">For all other SKUs, this value must be 'default'.</span></span> <span data-ttu-id="7e7ce-120">使用可能な値が含まれます: 'default'、'highDensity'</span><span class="sxs-lookup"><span data-stu-id="7e7ce-120">Possible values include: 'default', 'highDensity'</span></span></param>
        <param name="status"><span data-ttu-id="7e7ce-121">検索サービスの状態。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-121">The status of the Search service.</span></span> <span data-ttu-id="7e7ce-122">使用可能な値が含まれます: '実行中: Search サービスが実行されていると、プロビジョニング操作がない進行中です。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-122">Possible values include: 'running': The Search service is running and no provisioning operations are underway.</span></span> <span data-ttu-id="7e7ce-123">'プロビジョニング': Search サービスが中プロビジョニングまたは拡大または縮小します。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-123">'provisioning': The Search service is being provisioned or scaled up or down.</span></span> <span data-ttu-id="7e7ce-124">'削除': Search サービスが削除されています。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-124">'deleting': The Search service is being deleted.</span></span> <span data-ttu-id="7e7ce-125">'低下': Search サービスが低下します。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-125">'degraded': The Search service is degraded.</span></span> <span data-ttu-id="7e7ce-126">これは、基になる検索単位が異常な場合に発生します。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-126">This can occur when the underlying search units are not healthy.</span></span> <span data-ttu-id="7e7ce-127">Search サービスは、運用上のほとんどの場合ですがパフォーマンスが低下する可能性があり、いくつかの要求が削除される可能性があります。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-127">The Search service is most likely operational, but performance might be slow and some requests might be dropped.</span></span> <span data-ttu-id="7e7ce-128">'disabled': Search サービスを無効にします。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-128">'disabled': The Search service is disabled.</span></span> <span data-ttu-id="7e7ce-129">この状態では、サービスはすべての API 要求を拒否します。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-129">In this state, the service will reject all API requests.</span></span> <span data-ttu-id="7e7ce-130">'error': Search サービスが、エラー状態にします。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-130">'error': The Search service is in an error state.</span></span> <span data-ttu-id="7e7ce-131">サービスを低下、無効な場合、またはエラーを示している場合は、Azure Search チームが、基になる問題を積極的に調査を意味します。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-131">If your service is in the degraded, disabled, or error states, it means the Azure Search team is actively investigating the underlying issue.</span></span>
            <span data-ttu-id="7e7ce-132">この状態の専用サービスは、プロビジョニングされた検索単位数に基づいて、引き続き課金対象になります。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-132">Dedicated services in these states are still chargeable based on the number of search units provisioned.</span></span> <span data-ttu-id="7e7ce-133">使用可能な値が含まれます: 'を実行している'、'プロビジョニング、' 'を削除する'、'低下'、'disabled'、'error'</span><span class="sxs-lookup"><span data-stu-id="7e7ce-133">Possible values include: 'running', 'provisioning', 'deleting', 'degraded', 'disabled', 'error'</span></span></param>
        <param name="statusDetails"><span data-ttu-id="7e7ce-134">検索サービスの状態の詳細。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-134">The details of the Search service status.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="7e7ce-135">最後のプロビジョニング操作の状態は、Search サービスで実行します。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-135">The state of the last provisioning operation performed on the Search service.</span></span> <span data-ttu-id="7e7ce-136">プロビジョニングは、サービスの容量が確立されるときに発生する中間的な状態です。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-136">Provisioning is an intermediate state that occurs while service capacity is being established.</span></span> <span data-ttu-id="7e7ce-137">容量がセットアップされたら、provisioningState は、'成功' または '失敗' に変更します。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-137">After capacity is set up, provisioningState changes to either 'succeeded' or 'failed'.</span></span> <span data-ttu-id="7e7ce-138">クライアント アプリケーションを使用して、検索サービスの取得操作を操作が完了したタイミングを参照してください (推奨されるポーリング間隔は 30 秒から 1 分間) のプロビジョニング ステータスをポーリングできます。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-138">Client applications can poll provisioning status (the recommended polling interval is from 30 seconds to one minute) by using the Get Search Service operation to see when an operation is completed.</span></span> <span data-ttu-id="7e7ce-139">無料のサービスを使用している場合、この値を検索の作成サービスへの呼び出しで直接には、'成功' として返される傾向があります。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-139">If you are using the free service, this value tends to come back as 'succeeded' directly in the call to Create Search service.</span></span> <span data-ttu-id="7e7ce-140">これは、無料のサービスは既にセットアップされている容量を使用するためです。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-140">This is because the free service uses capacity that is already set up.</span></span> <span data-ttu-id="7e7ce-141">使用可能な値が含まれます: は ' succeeded'、'プロビジョニング'、'失敗'</span><span class="sxs-lookup"><span data-stu-id="7e7ce-141">Possible values include: 'succeeded', 'provisioning', 'failed'</span></span></param>
        <summary>
            <span data-ttu-id="7e7ce-142">SearchService クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-142">Initializes a new instance of the SearchService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostingMode">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Search.Models.HostingMode&gt; HostingMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Search.Models.HostingMode&gt; HostingMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Search.Models.SearchService.HostingMode" />
      <MemberSignature Language="VB.NET" Value="Public Property HostingMode As Nullable(Of HostingMode)" />
      <MemberSignature Language="F#" Value="member this.HostingMode : Nullable&lt;Microsoft.Azure.Management.Search.Models.HostingMode&gt; with get, set" Usage="Microsoft.Azure.Management.Search.Models.SearchService.HostingMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hostingMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Search.Models.HostingMode&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7e7ce-143">取得または standard3 SKU に対してのみ該当する設定。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-143">Gets or sets applicable only for the standard3 SKU.</span></span> <span data-ttu-id="7e7ce-144">他の任意の SKU で許可される最大のインデックスよりも多くは最大で 1,000 個のインデックスを許可する最大 3 つの高密度パーティションを有効にするには、このプロパティを設定することができます。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-144">You can set this property to enable up to 3 high density partitions that allow up to 1000 indexes, which is much higher than the maximum indexes allowed for any other SKU.</span></span> <span data-ttu-id="7e7ce-145">Standard3 SKU 値は 'default' または 'highDensity' のいずれかです。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-145">For the standard3 SKU, the value is either 'default' or 'highDensity'.</span></span> <span data-ttu-id="7e7ce-146">その他のすべての Sku では、この値は 'default' をする必要があります。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-146">For all other SKUs, this value must be 'default'.</span></span> <span data-ttu-id="7e7ce-147">使用可能な値が含まれます: 'default'、'highDensity'</span><span class="sxs-lookup"><span data-stu-id="7e7ce-147">Possible values include: 'default', 'highDensity'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; PartitionCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; PartitionCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Search.Models.SearchService.PartitionCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.PartitionCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Search.Models.SearchService.PartitionCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.partitionCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7e7ce-148">取得または検索サービスのパーティションの数を設定指定した場合は、1、2、3、4、6、または 12 にできます。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-148">Gets or sets the number of partitions in the Search service; if specified, it can be 1, 2, 3, 4, 6, or 12.</span></span> <span data-ttu-id="7e7ce-149">1 より大きい値では、標準 Sku 有効のみです。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-149">Values greater than 1 are only valid for standard SKUs.</span></span> <span data-ttu-id="7e7ce-150">HostingMode 'highDensity' éý 'standard3' サービスの有効な値は 1 ~ 3 の範囲です。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-150">For 'standard3' services with hostingMode set to 'highDensity', the allowed values are between 1 and 3.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Search.Models.ProvisioningState&gt; ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Search.Models.ProvisioningState&gt; ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Search.Models.SearchService.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As Nullable(Of ProvisioningState)" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Nullable&lt;Microsoft.Azure.Management.Search.Models.ProvisioningState&gt;" Usage="Microsoft.Azure.Management.Search.Models.SearchService.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Search.Models.ProvisioningState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7e7ce-151">Search サービスで実行される操作のプロビジョニング、最後の状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-151">Gets the state of the last provisioning operation performed on the Search service.</span></span> <span data-ttu-id="7e7ce-152">プロビジョニングは、サービスの容量が確立されるときに発生する中間的な状態です。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-152">Provisioning is an intermediate state that occurs while service capacity is being established.</span></span> <span data-ttu-id="7e7ce-153">容量がセットアップされたら、provisioningState は、'成功' または '失敗' に変更します。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-153">After capacity is set up, provisioningState changes to either 'succeeded' or 'failed'.</span></span> <span data-ttu-id="7e7ce-154">クライアント アプリケーションを使用して、検索サービスの取得操作を操作が完了したタイミングを参照してください (推奨されるポーリング間隔は 30 秒から 1 分間) のプロビジョニング ステータスをポーリングできます。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-154">Client applications can poll provisioning status (the recommended polling interval is from 30 seconds to one minute) by using the Get Search Service operation to see when an operation is completed.</span></span> <span data-ttu-id="7e7ce-155">無料のサービスを使用している場合、この値を検索の作成サービスへの呼び出しで直接には、'成功' として返される傾向があります。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-155">If you are using the free service, this value tends to come back as 'succeeded' directly in the call to Create Search service.</span></span> <span data-ttu-id="7e7ce-156">これは、無料のサービスは既にセットアップされている容量を使用するためです。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-156">This is because the free service uses capacity that is already set up.</span></span> <span data-ttu-id="7e7ce-157">使用可能な値が含まれます: は ' succeeded'、'プロビジョニング'、'失敗'</span><span class="sxs-lookup"><span data-stu-id="7e7ce-157">Possible values include: 'succeeded', 'provisioning', 'failed'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ReplicaCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ReplicaCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Search.Models.SearchService.ReplicaCount" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplicaCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ReplicaCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Search.Models.SearchService.ReplicaCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.replicaCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7e7ce-158">取得または Search サービスのレプリカの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-158">Gets or sets the number of replicas in the Search service.</span></span> <span data-ttu-id="7e7ce-159">指定した場合は、1 から 12 standard Sku の間、または 1 ~ 3 の基本的な SKU の包括的で値を指定してする必要があります。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-159">If specified, it must be a value between 1 and 12 inclusive for standard SKUs or between 1 and 3 inclusive for basic SKU.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Search.Models.Sku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Search.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Search.Models.SearchService.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Search.Models.Sku with get, set" Usage="Microsoft.Azure.Management.Search.Models.SearchService.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Search.Models.Sku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7e7ce-160">取得または設定を決定する検索サービスの SKU の価格レベルと容量の制限。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-160">Gets or sets the SKU of the Search Service, which determines price tier and capacity limits.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Search.Models.SearchServiceStatus&gt; Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Search.Models.SearchServiceStatus&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Search.Models.SearchService.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As Nullable(Of SearchServiceStatus)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;Microsoft.Azure.Management.Search.Models.SearchServiceStatus&gt;" Usage="Microsoft.Azure.Management.Search.Models.SearchService.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Search.Models.SearchServiceStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7e7ce-161">検索サービスの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-161">Gets the status of the Search service.</span></span> <span data-ttu-id="7e7ce-162">使用可能な値が含まれます: '実行中: Search サービスが実行されていると、プロビジョニング操作がない進行中です。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-162">Possible values include: 'running': The Search service is running and no provisioning operations are underway.</span></span> <span data-ttu-id="7e7ce-163">'プロビジョニング': Search サービスが中プロビジョニングまたは拡大または縮小します。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-163">'provisioning': The Search service is being provisioned or scaled up or down.</span></span> <span data-ttu-id="7e7ce-164">'削除': Search サービスが削除されています。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-164">'deleting': The Search service is being deleted.</span></span> <span data-ttu-id="7e7ce-165">'低下': Search サービスが低下します。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-165">'degraded': The Search service is degraded.</span></span> <span data-ttu-id="7e7ce-166">これは、基になる検索単位が異常な場合に発生します。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-166">This can occur when the underlying search units are not healthy.</span></span> <span data-ttu-id="7e7ce-167">Search サービスは、運用上のほとんどの場合ですがパフォーマンスが低下する可能性があり、いくつかの要求が削除される可能性があります。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-167">The Search service is most likely operational, but performance might be slow and some requests might be dropped.</span></span>
            <span data-ttu-id="7e7ce-168">'disabled': Search サービスを無効にします。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-168">'disabled': The Search service is disabled.</span></span> <span data-ttu-id="7e7ce-169">この状態では、サービスはすべての API 要求を拒否します。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-169">In this state, the service will reject all API requests.</span></span> <span data-ttu-id="7e7ce-170">'error': Search サービスが、エラー状態にします。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-170">'error': The Search service is in an error state.</span></span> <span data-ttu-id="7e7ce-171">サービスを低下、無効な場合、またはエラーを示している場合は、Azure Search チームが、基になる問題を積極的に調査を意味します。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-171">If your service is in the degraded, disabled, or error states, it means the Azure Search team is actively investigating the underlying issue.</span></span> <span data-ttu-id="7e7ce-172">この状態の専用サービスは、プロビジョニングされた検索単位数に基づいて、引き続き課金対象になります。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-172">Dedicated services in these states are still chargeable based on the number of search units provisioned.</span></span> <span data-ttu-id="7e7ce-173">使用可能な値が含まれます: 'を実行している'、'プロビジョニング、' 'を削除する'、'低下'、'disabled'、'error'</span><span class="sxs-lookup"><span data-stu-id="7e7ce-173">Possible values include: 'running', 'provisioning', 'deleting', 'degraded', 'disabled', 'error'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusDetails">
      <MemberSignature Language="C#" Value="public string StatusDetails { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StatusDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Search.Models.SearchService.StatusDetails" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StatusDetails As String" />
      <MemberSignature Language="F#" Value="member this.StatusDetails : string" Usage="Microsoft.Azure.Management.Search.Models.SearchService.StatusDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.statusDetails")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7e7ce-174">検索サービスの状態の詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-174">Gets the details of the Search service status.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.Models.SearchService.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="searchService.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7e7ce-175">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-175">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7e7ce-176">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7e7ce-176">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>