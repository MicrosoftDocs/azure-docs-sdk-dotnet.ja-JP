<Type Name="SBNamespace" FullName="Microsoft.Azure.Management.ServiceBus.Models.SBNamespace">
  <TypeSignature Language="C#" Value="public class SBNamespace : Microsoft.Azure.Management.ServiceBus.Models.TrackedResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SBNamespace extends Microsoft.Azure.Management.ServiceBus.Models.TrackedResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Models.SBNamespace" />
  <TypeSignature Language="VB.NET" Value="Public Class SBNamespace&#xA;Inherits TrackedResource" />
  <TypeSignature Language="F#" Value="type SBNamespace = class&#xA;    inherit TrackedResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ServiceBus.Models.TrackedResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="3acea-101">名前空間リソースの説明。</span><span class="sxs-lookup"><span data-stu-id="3acea-101">Description of a namespace resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SBNamespace ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.SBNamespace.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3acea-102">SBNamespace クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3acea-102">Initializes a new instance of the SBNamespace class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SBNamespace (string location, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.ServiceBus.Models.SBSku sku = null, string provisioningState = null, Nullable&lt;DateTime&gt; createdAt = null, Nullable&lt;DateTime&gt; updatedAt = null, string serviceBusEndpoint = null, string metricId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.ServiceBus.Models.SBSku sku, string provisioningState, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; createdAt, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; updatedAt, string serviceBusEndpoint, string metricId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.SBNamespace.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.ServiceBus.Models.SBSku,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (location As String, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional sku As SBSku = null, Optional provisioningState As String = null, Optional createdAt As Nullable(Of DateTime) = null, Optional updatedAt As Nullable(Of DateTime) = null, Optional serviceBusEndpoint As String = null, Optional metricId As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ServiceBus.Models.SBNamespace : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.ServiceBus.Models.SBSku * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * string -&gt; Microsoft.Azure.Management.ServiceBus.Models.SBNamespace" Usage="new Microsoft.Azure.Management.ServiceBus.Models.SBNamespace (location, id, name, type, tags, sku, provisioningState, createdAt, updatedAt, serviceBusEndpoint, metricId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.ServiceBus.Models.SBSku" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="createdAt" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="updatedAt" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="serviceBusEndpoint" Type="System.String" />
        <Parameter Name="metricId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="3acea-103">リソースが存在する地理的な場所</span><span class="sxs-lookup"><span data-stu-id="3acea-103">The Geo-location where the resource lives</span></span></param>
        <param name="id"><span data-ttu-id="3acea-104">リソース Id</span><span class="sxs-lookup"><span data-stu-id="3acea-104">Resource Id</span></span></param>
        <param name="name"><span data-ttu-id="3acea-105">リソース名</span><span class="sxs-lookup"><span data-stu-id="3acea-105">Resource name</span></span></param>
        <param name="type"><span data-ttu-id="3acea-106">リソースの種類</span><span class="sxs-lookup"><span data-stu-id="3acea-106">Resource type</span></span></param>
        <param name="tags"><span data-ttu-id="3acea-107">リソース タグ</span><span class="sxs-lookup"><span data-stu-id="3acea-107">Resource tags</span></span></param>
        <param name="sku"><span data-ttu-id="3acea-108">Sku のプロパティ</span><span class="sxs-lookup"><span data-stu-id="3acea-108">Porperties of Sku</span></span></param>
        <param name="provisioningState"><span data-ttu-id="3acea-109">名前空間のプロビジョニング状態。</span><span class="sxs-lookup"><span data-stu-id="3acea-109">Provisioning state of the namespace.</span></span></param>
        <param name="createdAt"><span data-ttu-id="3acea-110">名前空間が作成された時刻。</span><span class="sxs-lookup"><span data-stu-id="3acea-110">The time the namespace was created.</span></span></param>
        <param name="updatedAt"><span data-ttu-id="3acea-111">名前空間が更新された時刻。</span><span class="sxs-lookup"><span data-stu-id="3acea-111">The time the namespace was updated.</span></span></param>
        <param name="serviceBusEndpoint"><span data-ttu-id="3acea-112">エンドポイントが Service Bus 操作の実行に使用することができます。</span><span class="sxs-lookup"><span data-stu-id="3acea-112">Endpoint you can use to perform Service Bus operations.</span></span></param>
        <param name="metricId"><span data-ttu-id="3acea-113">Azure インサイト メトリックの識別子</span><span class="sxs-lookup"><span data-stu-id="3acea-113">Identifier for Azure Insights metrics</span></span></param>
        <summary>
            <span data-ttu-id="3acea-114">SBNamespace クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3acea-114">Initializes a new instance of the SBNamespace class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedAt">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBNamespace.CreatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreatedAt As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreatedAt : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBNamespace.CreatedAt" />
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
            <span data-ttu-id="3acea-115">名前空間が作成された日時を取得します。</span><span class="sxs-lookup"><span data-stu-id="3acea-115">Gets the time the namespace was created.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MetricId">
      <MemberSignature Language="C#" Value="public string MetricId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MetricId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBNamespace.MetricId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MetricId As String" />
      <MemberSignature Language="F#" Value="member this.MetricId : string" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBNamespace.MetricId" />
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
            <span data-ttu-id="3acea-116">Azure インサイト メトリックの識別子を取得します。</span><span class="sxs-lookup"><span data-stu-id="3acea-116">Gets identifier for Azure Insights metrics</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBNamespace.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBNamespace.ProvisioningState" />
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
            <span data-ttu-id="3acea-117">名前空間の状態のプロビジョニングを取得します。</span><span class="sxs-lookup"><span data-stu-id="3acea-117">Gets provisioning state of the namespace.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceBusEndpoint">
      <MemberSignature Language="C#" Value="public string ServiceBusEndpoint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceBusEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBNamespace.ServiceBusEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceBusEndpoint As String" />
      <MemberSignature Language="F#" Value="member this.ServiceBusEndpoint : string" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBNamespace.ServiceBusEndpoint" />
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
            <span data-ttu-id="3acea-118">Service Bus 操作の実行に使用できるエンドポイントを取得します。</span><span class="sxs-lookup"><span data-stu-id="3acea-118">Gets endpoint you can use to perform Service Bus operations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Models.SBSku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ServiceBus.Models.SBSku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBNamespace.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As SBSku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.ServiceBus.Models.SBSku with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBNamespace.Sku" />
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
            <span data-ttu-id="3acea-119">取得または Sku のプロパティを設定</span><span class="sxs-lookup"><span data-stu-id="3acea-119">Gets or sets porperties of Sku</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatedAt">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; UpdatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; UpdatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBNamespace.UpdatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpdatedAt As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.UpdatedAt : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBNamespace.UpdatedAt" />
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
            <span data-ttu-id="3acea-120">名前空間が更新された時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="3acea-120">Gets the time the namespace was updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.SBNamespace.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="sBNamespace.Validate " />
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
            <span data-ttu-id="3acea-121">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="3acea-121">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="3acea-122">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="3acea-122">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>