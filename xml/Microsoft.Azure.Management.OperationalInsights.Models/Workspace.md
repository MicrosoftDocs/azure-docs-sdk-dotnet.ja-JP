<Type Name="Workspace" FullName="Microsoft.Azure.Management.OperationalInsights.Models.Workspace">
  <TypeSignature Language="C#" Value="public class Workspace : Microsoft.Azure.Management.OperationalInsights.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Workspace extends Microsoft.Azure.Management.OperationalInsights.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.OperationalInsights.Models.Workspace" />
  <TypeSignature Language="VB.NET" Value="Public Class Workspace&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type Workspace = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.OperationalInsights.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="e1562-101">最上位のワークスペースのリソースのコンテナーです。</span><span class="sxs-lookup"><span data-stu-id="e1562-101">The top level Workspace resource container.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Workspace ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.Workspace.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e1562-102">ワークスペースのクラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e1562-102">Initializes a new instance of the Workspace class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Workspace (string location, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string provisioningState = null, string source = null, string customerId = null, string portalUrl = null, Microsoft.Azure.Management.OperationalInsights.Models.Sku sku = null, Nullable&lt;int&gt; retentionInDays = null, string eTag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string provisioningState, string source, string customerId, string portalUrl, class Microsoft.Azure.Management.OperationalInsights.Models.Sku sku, valuetype System.Nullable`1&lt;int32&gt; retentionInDays, string eTag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.Workspace.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.String,System.String,System.String,Microsoft.Azure.Management.OperationalInsights.Models.Sku,System.Nullable{System.Int32},System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.OperationalInsights.Models.Workspace : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * string * string * string * Microsoft.Azure.Management.OperationalInsights.Models.Sku * Nullable&lt;int&gt; * string -&gt; Microsoft.Azure.Management.OperationalInsights.Models.Workspace" Usage="new Microsoft.Azure.Management.OperationalInsights.Models.Workspace (location, id, name, type, tags, provisioningState, source, customerId, portalUrl, sku, retentionInDays, eTag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="source" Type="System.String" />
        <Parameter Name="customerId" Type="System.String" />
        <Parameter Name="portalUrl" Type="System.String" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.OperationalInsights.Models.Sku" />
        <Parameter Name="retentionInDays" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="eTag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="e1562-103">リソースの場所</span><span class="sxs-lookup"><span data-stu-id="e1562-103">Resource location</span></span></param>
        <param name="id"><span data-ttu-id="e1562-104">リソース Id</span><span class="sxs-lookup"><span data-stu-id="e1562-104">Resource Id</span></span></param>
        <param name="name"><span data-ttu-id="e1562-105">リソース名</span><span class="sxs-lookup"><span data-stu-id="e1562-105">Resource name</span></span></param>
        <param name="type"><span data-ttu-id="e1562-106">リソースの種類</span><span class="sxs-lookup"><span data-stu-id="e1562-106">Resource type</span></span></param>
        <param name="tags"><span data-ttu-id="e1562-107">リソース タグ</span><span class="sxs-lookup"><span data-stu-id="e1562-107">Resource tags</span></span></param>
        <param name="provisioningState"><span data-ttu-id="e1562-108">ワークスペースのプロビジョニングの状態。</span><span class="sxs-lookup"><span data-stu-id="e1562-108">The provisioning state of the workspace.</span></span> <span data-ttu-id="e1562-109">使用可能な値が含まれます: '作成中'、'成功'、'失敗'、'キャンセル'、'削除'、'ProvisioningAccount'</span><span class="sxs-lookup"><span data-stu-id="e1562-109">Possible values include: 'Creating', 'Succeeded', 'Failed', 'Canceled', 'Deleting', 'ProvisioningAccount'</span></span></param>
        <param name="source"><span data-ttu-id="e1562-110">ワークスペースのソース。</span><span class="sxs-lookup"><span data-stu-id="e1562-110">The source of the workspace.</span></span>  <span data-ttu-id="e1562-111">ソースは、ワークスペースを作成した場所を定義します。</span><span class="sxs-lookup"><span data-stu-id="e1562-111">Source defines where the workspace was created.</span></span> <span data-ttu-id="e1562-112">'Azure' は、Azure で作成されたことを意味します。</span><span class="sxs-lookup"><span data-stu-id="e1562-112">'Azure' implies it was created in Azure.</span></span>  <span data-ttu-id="e1562-113">「外部」は、Operational Insights ポータルを使用して作成されたことを意味します。</span><span class="sxs-lookup"><span data-stu-id="e1562-113">'External' implies it was created via the Operational Insights Portal.</span></span> <span data-ttu-id="e1562-114">この値は、サービス側とクライアント側では読み取り専用に設定されます。</span><span class="sxs-lookup"><span data-stu-id="e1562-114">This value is set on the service side and read-only on the client side.</span></span></param>
        <param name="customerId"><span data-ttu-id="e1562-115">ワークスペースに関連付けられている ID です。</span><span class="sxs-lookup"><span data-stu-id="e1562-115">The ID associated with the workspace.</span></span> <span data-ttu-id="e1562-116">作成時にこの値を設定すると、既存のワークスペースにリンクするために作成されているワークスペースができます。</span><span class="sxs-lookup"><span data-stu-id="e1562-116">Setting this value at creation time allows the workspace being created to be linked to an existing workspace.</span></span></param>
        <param name="portalUrl"><span data-ttu-id="e1562-117">このワークスペースの Operational Insights ポータルの URL です。</span><span class="sxs-lookup"><span data-stu-id="e1562-117">The URL of the Operational Insights portal for this workspace.</span></span>  <span data-ttu-id="e1562-118">この値は、サービス側とクライアント側では読み取り専用に設定されます。</span><span class="sxs-lookup"><span data-stu-id="e1562-118">This value is set on the service side and read-only on the client side.</span></span></param>
        <param name="sku"><span data-ttu-id="e1562-119">ワークスペースの SKU。</span><span class="sxs-lookup"><span data-stu-id="e1562-119">The SKU of the workspace.</span></span></param>
        <param name="retentionInDays"><span data-ttu-id="e1562-120">日数のワークスペースのデータ保有期間。</span><span class="sxs-lookup"><span data-stu-id="e1562-120">The workspace data retention in days.</span></span>
            <span data-ttu-id="e1562-121">-1 は無制限の Sku の無制限の保有期間を意味します。</span><span class="sxs-lookup"><span data-stu-id="e1562-121">-1 means Unlimited retention for the Unlimited Sku.</span></span> <span data-ttu-id="e1562-122">730 の日数は、その他のすべての Sku で許可される最大です。</span><span class="sxs-lookup"><span data-stu-id="e1562-122">730 days is the maximum allowed for all other Skus.</span></span> </param>
        <param name="eTag"><span data-ttu-id="e1562-123">ワークスペースの ETag です。</span><span class="sxs-lookup"><span data-stu-id="e1562-123">The ETag of the workspace.</span></span></param>
        <summary>
            <span data-ttu-id="e1562-124">ワークスペースのクラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e1562-124">Initializes a new instance of the Workspace class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomerId">
      <MemberSignature Language="C#" Value="public string CustomerId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CustomerId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.Workspace.CustomerId" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomerId As String" />
      <MemberSignature Language="F#" Value="member this.CustomerId : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.Workspace.CustomerId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.customerId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e1562-125">取得またはワークスペースに関連付けられている ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="e1562-125">Gets or sets the ID associated with the workspace.</span></span>  <span data-ttu-id="e1562-126">作成時にこの値を設定すると、既存のワークスペースにリンクするために作成されているワークスペースができます。</span><span class="sxs-lookup"><span data-stu-id="e1562-126">Setting this value at creation time allows the workspace being created to be linked to an existing workspace.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.Workspace.ETag" />
      <MemberSignature Language="VB.NET" Value="Public Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.Workspace.ETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="eTag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e1562-127">取得またはワークスペースの ETag を設定します。</span><span class="sxs-lookup"><span data-stu-id="e1562-127">Gets or sets the ETag of the workspace.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PortalUrl">
      <MemberSignature Language="C#" Value="public string PortalUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PortalUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.Workspace.PortalUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property PortalUrl As String" />
      <MemberSignature Language="F#" Value="member this.PortalUrl : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.Workspace.PortalUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.portalUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e1562-128">取得またはこのワークスペースの Operational Insights ポータルの URL を設定します。</span><span class="sxs-lookup"><span data-stu-id="e1562-128">Gets or sets the URL of the Operational Insights portal for this workspace.</span></span>  <span data-ttu-id="e1562-129">この値は、サービス側とクライアント側では読み取り専用に設定されます。</span><span class="sxs-lookup"><span data-stu-id="e1562-129">This value is set on the service side and read-only on the client side.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.Workspace.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.Workspace.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e1562-130">取得またはワークスペースのプロビジョニングの状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="e1562-130">Gets or sets the provisioning state of the workspace.</span></span> <span data-ttu-id="e1562-131">使用可能な値が含まれます: '作成中'、'成功'、'失敗'、'キャンセル'、'削除'、'ProvisioningAccount'</span><span class="sxs-lookup"><span data-stu-id="e1562-131">Possible values include: 'Creating', 'Succeeded', 'Failed', 'Canceled', 'Deleting', 'ProvisioningAccount'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionInDays">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; RetentionInDays { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; RetentionInDays" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.Workspace.RetentionInDays" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionInDays As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.RetentionInDays : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.Workspace.RetentionInDays" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.retentionInDays")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e1562-132">取得またはワークスペースのデータ保有期間を日に設定します。</span><span class="sxs-lookup"><span data-stu-id="e1562-132">Gets or sets the workspace data retention in days.</span></span> <span data-ttu-id="e1562-133">-1 は無制限の Sku の無制限の保有期間を意味します。</span><span class="sxs-lookup"><span data-stu-id="e1562-133">-1 means Unlimited retention for the Unlimited Sku.</span></span> <span data-ttu-id="e1562-134">730 の日数は、その他のすべての Sku で許可される最大です。</span><span class="sxs-lookup"><span data-stu-id="e1562-134">730 days is the maximum allowed for all other Skus.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.OperationalInsights.Models.Sku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.OperationalInsights.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.Workspace.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.OperationalInsights.Models.Sku with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.Workspace.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.Sku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e1562-135">取得またはワークスペースの SKU を設定します。</span><span class="sxs-lookup"><span data-stu-id="e1562-135">Gets or sets the SKU of the workspace.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Source">
      <MemberSignature Language="C#" Value="public string Source { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Source" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.Workspace.Source" />
      <MemberSignature Language="VB.NET" Value="Public Property Source As String" />
      <MemberSignature Language="F#" Value="member this.Source : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.Workspace.Source" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.source")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e1562-136">取得またはワークスペースのソースを設定します。</span><span class="sxs-lookup"><span data-stu-id="e1562-136">Gets or sets the source of the workspace.</span></span>  <span data-ttu-id="e1562-137">ソースは、ワークスペースを作成した場所を定義します。</span><span class="sxs-lookup"><span data-stu-id="e1562-137">Source defines where the workspace was created.</span></span> <span data-ttu-id="e1562-138">'Azure' は、Azure で作成されたことを意味します。</span><span class="sxs-lookup"><span data-stu-id="e1562-138">'Azure' implies it was created in Azure.</span></span> <span data-ttu-id="e1562-139">「外部」は、Operational Insights ポータルを使用して作成されたことを意味します。</span><span class="sxs-lookup"><span data-stu-id="e1562-139">'External' implies it was created via the Operational Insights Portal.</span></span> <span data-ttu-id="e1562-140">この値は、サービス側とクライアント側では読み取り専用に設定されます。</span><span class="sxs-lookup"><span data-stu-id="e1562-140">This value is set on the service side and read-only on the client side.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.Workspace.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="workspace.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e1562-141">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="e1562-141">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e1562-142">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e1562-142">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>