<Type Name="SBNamespaceUpdateParameters" FullName="Microsoft.Azure.Management.ServiceBus.Models.SBNamespaceUpdateParameters">
  <TypeSignature Language="C#" Value="public class SBNamespaceUpdateParameters : Microsoft.Azure.Management.ServiceBus.Models.ResourceNamespacePatch" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SBNamespaceUpdateParameters extends Microsoft.Azure.Management.ServiceBus.Models.ResourceNamespacePatch" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Models.SBNamespaceUpdateParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class SBNamespaceUpdateParameters&#xA;Inherits ResourceNamespacePatch" />
  <TypeSignature Language="F#" Value="type SBNamespaceUpdateParameters = class&#xA;    inherit ResourceNamespacePatch" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ServiceBus.Models.ResourceNamespacePatch</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="4974d-101">名前空間リソースの説明。</span><span class="sxs-lookup"><span data-stu-id="4974d-101">Description of a namespace resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SBNamespaceUpdateParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.SBNamespaceUpdateParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4974d-102">SBNamespaceUpdateParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="4974d-102">Initializes a new instance of the SBNamespaceUpdateParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SBNamespaceUpdateParameters (string id = null, string name = null, string type = null, string location = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.ServiceBus.Models.SBSku sku = null, string provisioningState = null, Nullable&lt;DateTime&gt; createdAt = null, Nullable&lt;DateTime&gt; updatedAt = null, string serviceBusEndpoint = null, string metricId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.ServiceBus.Models.SBSku sku, string provisioningState, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; createdAt, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; updatedAt, string serviceBusEndpoint, string metricId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.SBNamespaceUpdateParameters.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.ServiceBus.Models.SBSku,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional location As String = null, Optional tags As IDictionary(Of String, String) = null, Optional sku As SBSku = null, Optional provisioningState As String = null, Optional createdAt As Nullable(Of DateTime) = null, Optional updatedAt As Nullable(Of DateTime) = null, Optional serviceBusEndpoint As String = null, Optional metricId As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ServiceBus.Models.SBNamespaceUpdateParameters : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.ServiceBus.Models.SBSku * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * string -&gt; Microsoft.Azure.Management.ServiceBus.Models.SBNamespaceUpdateParameters" Usage="new Microsoft.Azure.Management.ServiceBus.Models.SBNamespaceUpdateParameters (id, name, type, location, tags, sku, provisioningState, createdAt, updatedAt, serviceBusEndpoint, metricId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.ServiceBus.Models.SBSku" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="createdAt" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="updatedAt" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="serviceBusEndpoint" Type="System.String" />
        <Parameter Name="metricId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="4974d-103">リソース Id</span><span class="sxs-lookup"><span data-stu-id="4974d-103">Resource Id</span></span></param>
        <param name="name"><span data-ttu-id="4974d-104">リソース名</span><span class="sxs-lookup"><span data-stu-id="4974d-104">Resource name</span></span></param>
        <param name="type"><span data-ttu-id="4974d-105">リソースの種類</span><span class="sxs-lookup"><span data-stu-id="4974d-105">Resource type</span></span></param>
        <param name="location"><span data-ttu-id="4974d-106">リソースの場所</span><span class="sxs-lookup"><span data-stu-id="4974d-106">Resource location</span></span></param>
        <param name="tags"><span data-ttu-id="4974d-107">リソース タグ</span><span class="sxs-lookup"><span data-stu-id="4974d-107">Resource tags</span></span></param>
        <param name="sku"><span data-ttu-id="4974d-108">Sku のプロパティ</span><span class="sxs-lookup"><span data-stu-id="4974d-108">Porperties of Sku</span></span></param>
        <param name="provisioningState"><span data-ttu-id="4974d-109">名前空間のプロビジョニング状態。</span><span class="sxs-lookup"><span data-stu-id="4974d-109">Provisioning state of the namespace.</span></span></param>
        <param name="createdAt"><span data-ttu-id="4974d-110">名前空間が作成された時刻。</span><span class="sxs-lookup"><span data-stu-id="4974d-110">The time the namespace was created.</span></span></param>
        <param name="updatedAt"><span data-ttu-id="4974d-111">名前空間が更新された時刻。</span><span class="sxs-lookup"><span data-stu-id="4974d-111">The time the namespace was updated.</span></span></param>
        <param name="serviceBusEndpoint"><span data-ttu-id="4974d-112">エンドポイントが Service Bus 操作の実行に使用することができます。</span><span class="sxs-lookup"><span data-stu-id="4974d-112">Endpoint you can use to perform Service Bus operations.</span></span></param>
        <param name="metricId"><span data-ttu-id="4974d-113">Azure インサイト メトリックの識別子</span><span class="sxs-lookup"><span data-stu-id="4974d-113">Identifier for Azure Insights metrics</span></span></param>
        <summary>
            <span data-ttu-id="4974d-114">SBNamespaceUpdateParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="4974d-114">Initializes a new instance of the SBNamespaceUpdateParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedAt">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBNamespaceUpdateParameters.CreatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreatedAt As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreatedAt : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBNamespaceUpdateParameters.CreatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.createdAt")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4974d-115">名前空間が作成された日時を取得します。</span><span class="sxs-lookup"><span data-stu-id="4974d-115">Gets the time the namespace was created.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MetricId">
      <MemberSignature Language="C#" Value="public string MetricId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MetricId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBNamespaceUpdateParameters.MetricId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MetricId As String" />
      <MemberSignature Language="F#" Value="member this.MetricId : string" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBNamespaceUpdateParameters.MetricId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.metricId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4974d-116">Azure インサイト メトリックの識別子を取得します。</span><span class="sxs-lookup"><span data-stu-id="4974d-116">Gets identifier for Azure Insights metrics</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBNamespaceUpdateParameters.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBNamespaceUpdateParameters.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="4974d-117">名前空間の状態のプロビジョニングを取得します。</span><span class="sxs-lookup"><span data-stu-id="4974d-117">Gets provisioning state of the namespace.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceBusEndpoint">
      <MemberSignature Language="C#" Value="public string ServiceBusEndpoint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceBusEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBNamespaceUpdateParameters.ServiceBusEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceBusEndpoint As String" />
      <MemberSignature Language="F#" Value="member this.ServiceBusEndpoint : string" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBNamespaceUpdateParameters.ServiceBusEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serviceBusEndpoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4974d-118">Service Bus 操作の実行に使用できるエンドポイントを取得します。</span><span class="sxs-lookup"><span data-stu-id="4974d-118">Gets endpoint you can use to perform Service Bus operations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Models.SBSku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ServiceBus.Models.SBSku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBNamespaceUpdateParameters.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As SBSku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.ServiceBus.Models.SBSku with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBNamespaceUpdateParameters.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Models.SBSku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4974d-119">取得または Sku のプロパティを設定</span><span class="sxs-lookup"><span data-stu-id="4974d-119">Gets or sets porperties of Sku</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatedAt">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; UpdatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; UpdatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBNamespaceUpdateParameters.UpdatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpdatedAt As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.UpdatedAt : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBNamespaceUpdateParameters.UpdatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.updatedAt")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4974d-120">名前空間が更新された時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="4974d-120">Gets the time the namespace was updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.SBNamespaceUpdateParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="sBNamespaceUpdateParameters.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4974d-121">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="4974d-121">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4974d-122">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4974d-122">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>