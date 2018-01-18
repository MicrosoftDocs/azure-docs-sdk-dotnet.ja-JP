<Type Name="RedisResource" FullName="Microsoft.Azure.Management.Redis.Models.RedisResource">
  <TypeSignature Language="C#" Value="public class RedisResource : Microsoft.Azure.Management.Redis.Models.TrackedResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RedisResource extends Microsoft.Azure.Management.Redis.Models.TrackedResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Redis.Models.RedisResource" />
  <TypeSignature Language="VB.NET" Value="Public Class RedisResource&#xA;Inherits TrackedResource" />
  <TypeSignature Language="F#" Value="type RedisResource = class&#xA;    inherit TrackedResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Redis.Models.Resource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.Redis.Models.TrackedResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="de7e4-101">リストまたは Get 操作で 1 つの Redis アイテムです。</span><span class="sxs-lookup"><span data-stu-id="de7e4-101">A single Redis item in List or Get Operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RedisResource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Models.RedisResource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="de7e4-102">RedisResource クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="de7e4-102">Initializes a new instance of the RedisResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RedisResource (string location, Microsoft.Azure.Management.Redis.Models.Sku sku, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.IDictionary&lt;string,string&gt; redisConfiguration = null, Nullable&lt;bool&gt; enableNonSslPort = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tenantSettings = null, Nullable&lt;int&gt; shardCount = null, string subnetId = null, string staticIP = null, string redisVersion = null, string provisioningState = null, string hostName = null, Nullable&lt;int&gt; port = null, Nullable&lt;int&gt; sslPort = null, Microsoft.Azure.Management.Redis.Models.RedisAccessKeys accessKeys = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Redis.Models.RedisLinkedServer&gt; linkedServers = null, System.Collections.Generic.IList&lt;string&gt; zones = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, class Microsoft.Azure.Management.Redis.Models.Sku sku, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; redisConfiguration, valuetype System.Nullable`1&lt;bool&gt; enableNonSslPort, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tenantSettings, valuetype System.Nullable`1&lt;int32&gt; shardCount, string subnetId, string staticIP, string redisVersion, string provisioningState, string hostName, valuetype System.Nullable`1&lt;int32&gt; port, valuetype System.Nullable`1&lt;int32&gt; sslPort, class Microsoft.Azure.Management.Redis.Models.RedisAccessKeys accessKeys, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Redis.Models.RedisLinkedServer&gt; linkedServers, class System.Collections.Generic.IList`1&lt;string&gt; zones) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Models.RedisResource.#ctor(System.String,Microsoft.Azure.Management.Redis.Models.Sku,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.IDictionary{System.String,System.String},System.Nullable{System.Boolean},System.Collections.Generic.IDictionary{System.String,System.String},System.Nullable{System.Int32},System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},Microsoft.Azure.Management.Redis.Models.RedisAccessKeys,System.Collections.Generic.IList{Microsoft.Azure.Management.Redis.Models.RedisLinkedServer},System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Redis.Models.RedisResource : string * Microsoft.Azure.Management.Redis.Models.Sku * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.IDictionary&lt;string, string&gt; * Nullable&lt;bool&gt; * System.Collections.Generic.IDictionary&lt;string, string&gt; * Nullable&lt;int&gt; * string * string * string * string * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Microsoft.Azure.Management.Redis.Models.RedisAccessKeys * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Redis.Models.RedisLinkedServer&gt; * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.Redis.Models.RedisResource" Usage="new Microsoft.Azure.Management.Redis.Models.RedisResource (location, sku, id, name, type, tags, redisConfiguration, enableNonSslPort, tenantSettings, shardCount, subnetId, staticIP, redisVersion, provisioningState, hostName, port, sslPort, accessKeys, linkedServers, zones)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.Redis.Models.Sku" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="redisConfiguration" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="enableNonSslPort" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="tenantSettings" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="shardCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="subnetId" Type="System.String" />
        <Parameter Name="staticIP" Type="System.String" />
        <Parameter Name="redisVersion" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="hostName" Type="System.String" />
        <Parameter Name="port" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="sslPort" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="accessKeys" Type="Microsoft.Azure.Management.Redis.Models.RedisAccessKeys" />
        <Parameter Name="linkedServers" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Redis.Models.RedisLinkedServer&gt;" />
        <Parameter Name="zones" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="de7e4-103">リソースが存在する地理的な場所</span><span class="sxs-lookup"><span data-stu-id="de7e4-103">The geo-location where the resource lives</span></span></param>
        <param name="sku"><span data-ttu-id="de7e4-104">展開する Redis cache の SKU。</span><span class="sxs-lookup"><span data-stu-id="de7e4-104">The SKU of the Redis cache to deploy.</span></span></param>
        <param name="id"><span data-ttu-id="de7e4-105">リソースの ID</span><span class="sxs-lookup"><span data-stu-id="de7e4-105">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="de7e4-106">リソース名。</span><span class="sxs-lookup"><span data-stu-id="de7e4-106">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="de7e4-107">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="de7e4-107">Resource type.</span></span></param>
        <param name="tags"><span data-ttu-id="de7e4-108">リソース タグ。</span><span class="sxs-lookup"><span data-stu-id="de7e4-108">Resource tags.</span></span></param>
        <param name="redisConfiguration"><span data-ttu-id="de7e4-109">すべては Redis の設定です。</span><span class="sxs-lookup"><span data-stu-id="de7e4-109">All Redis Settings.</span></span> <span data-ttu-id="de7e4-110">Few possible keys: rdb-backup-enabled,rdb-storage-connection-string,rdb-backup-frequency,maxmemory-delta,maxmemory-policy,notify-keyspace-events,maxmemory-samples,slowlog-log-slower-than,slowlog-max-len,list-max-ziplist-entries,list-max-ziplist-value,hash-max-ziplist-entries,hash-max-ziplist-value,set-max-intset-entries,zset-max-ziplist-entries,zset-max-ziplist-value etc.</span><span class="sxs-lookup"><span data-stu-id="de7e4-110">Few possible keys: rdb-backup-enabled,rdb-storage-connection-string,rdb-backup-frequency,maxmemory-delta,maxmemory-policy,notify-keyspace-events,maxmemory-samples,slowlog-log-slower-than,slowlog-max-len,list-max-ziplist-entries,list-max-ziplist-value,hash-max-ziplist-entries,hash-max-ziplist-value,set-max-intset-entries,zset-max-ziplist-entries,zset-max-ziplist-value etc.</span></span></param>
        <param name="enableNonSslPort"><span data-ttu-id="de7e4-111">指定するかどうか、非 ssl Redis サーバーのポート (6379) が有効になっています。</span><span class="sxs-lookup"><span data-stu-id="de7e4-111">Specifies whether the non-ssl Redis server port (6379) is enabled.</span></span></param>
        <param name="tenantSettings"><span data-ttu-id="de7e4-112">テナント設定のディクショナリ</span><span class="sxs-lookup"><span data-stu-id="de7e4-112">A dictionary of tenant settings</span></span></param>
        <param name="shardCount"><span data-ttu-id="de7e4-113">Premium クラスター キャッシュを作成するシャードの数。</span><span class="sxs-lookup"><span data-stu-id="de7e4-113">The number of shards to be created on a Premium Cluster Cache.</span></span></param>
        <param name="subnetId"><span data-ttu-id="de7e4-114">Redis cache を展開する仮想ネットワークのサブネットの完全なリソース ID。</span><span class="sxs-lookup"><span data-stu-id="de7e4-114">The full resource ID of a subnet in a virtual network to deploy the Redis cache in.</span></span> <span data-ttu-id="de7e4-115">たとえばの形式:/subscriptions/{subid} 必要な {resourcegroupname}/Microsoft です。{ネットワーク |ClassicNetwork}/VirtualNetworks、vnet1、サブネット/subnet1</span><span class="sxs-lookup"><span data-stu-id="de7e4-115">Example format: /subscriptions/{subid}/resourceGroups/{resourceGroupName}/Microsoft.{Network|ClassicNetwork}/VirtualNetworks/vnet1/subnets/subnet1</span></span></param>
        <param name="staticIP"><span data-ttu-id="de7e4-116">静的 IP アドレスです。</span><span class="sxs-lookup"><span data-stu-id="de7e4-116">Static IP address.</span></span> <span data-ttu-id="de7e4-117">既存の Azure 仮想ネットワーク内 Redis cache を展開するときに必要です。</span><span class="sxs-lookup"><span data-stu-id="de7e4-117">Required when deploying a Redis cache inside an existing Azure Virtual Network.</span></span></param>
        <param name="redisVersion"><span data-ttu-id="de7e4-118">Redis バージョン。</span><span class="sxs-lookup"><span data-stu-id="de7e4-118">Redis version.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="de7e4-119">インスタンスのプロビジョニングの状態、redis します。</span><span class="sxs-lookup"><span data-stu-id="de7e4-119">Redis instance provisioning status.</span></span></param>
        <param name="hostName"><span data-ttu-id="de7e4-120">ホスト名を redis します。</span><span class="sxs-lookup"><span data-stu-id="de7e4-120">Redis host name.</span></span></param>
        <param name="port"><span data-ttu-id="de7e4-121">非 SSL ポートを redis します。</span><span class="sxs-lookup"><span data-stu-id="de7e4-121">Redis non-SSL port.</span></span></param>
        <param name="sslPort"><span data-ttu-id="de7e4-122">SSL ポートを redis します。</span><span class="sxs-lookup"><span data-stu-id="de7e4-122">Redis SSL port.</span></span></param>
        <param name="accessKeys"><span data-ttu-id="de7e4-123">未設定の場合、このオブジェクトは作成または更新プログラムへの応答ではありません - Redis cache のキーの redis キャッシュ</span><span class="sxs-lookup"><span data-stu-id="de7e4-123">The keys of the Redis cache - not set if this object is not the response to Create or Update redis cache</span></span></param>
        <param name="linkedServers"><span data-ttu-id="de7e4-124">キャッシュに関連付けられているリンク サーバーの一覧</span><span class="sxs-lookup"><span data-stu-id="de7e4-124">List of the linked servers associated with the cache</span></span></param>
        <param name="zones"><span data-ttu-id="de7e4-125">可用性の一覧のゾーンでリソースがから取得する必要があるかを示すです。</span><span class="sxs-lookup"><span data-stu-id="de7e4-125">A list of availability zones denoting where the resource needs to come from.</span></span></param>
        <summary>
            <span data-ttu-id="de7e4-126">RedisResource クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="de7e4-126">Initializes a new instance of the RedisResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessKeys">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Models.RedisAccessKeys AccessKeys { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Redis.Models.RedisAccessKeys AccessKeys" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisResource.AccessKeys" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccessKeys As RedisAccessKeys" />
      <MemberSignature Language="F#" Value="member this.AccessKeys : Microsoft.Azure.Management.Redis.Models.RedisAccessKeys" Usage="Microsoft.Azure.Management.Redis.Models.RedisResource.AccessKeys" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.accessKeys")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Models.RedisAccessKeys</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="de7e4-127">このオブジェクトがない場合、応答の作成や更新 redis キャッシュを設定できません - Redis cache のキーを取得します。</span><span class="sxs-lookup"><span data-stu-id="de7e4-127">Gets the keys of the Redis cache - not set if this object is not the response to Create or Update redis cache</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableNonSslPort">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableNonSslPort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableNonSslPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisResource.EnableNonSslPort" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableNonSslPort As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableNonSslPort : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Redis.Models.RedisResource.EnableNonSslPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.enableNonSslPort")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="de7e4-128">取得または設定を指定するかどうか、非 ssl Redis サーバーのポート (6379) を有効にします。</span><span class="sxs-lookup"><span data-stu-id="de7e4-128">Gets or sets specifies whether the non-ssl Redis server port (6379) is enabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostName">
      <MemberSignature Language="C#" Value="public string HostName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisResource.HostName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HostName As String" />
      <MemberSignature Language="F#" Value="member this.HostName : string" Usage="Microsoft.Azure.Management.Redis.Models.RedisResource.HostName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hostName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="de7e4-129">取得は redis ホスト名です。</span><span class="sxs-lookup"><span data-stu-id="de7e4-129">Gets redis host name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LinkedServers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Redis.Models.RedisLinkedServer&gt; LinkedServers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Redis.Models.RedisLinkedServer&gt; LinkedServers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisResource.LinkedServers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LinkedServers As IList(Of RedisLinkedServer)" />
      <MemberSignature Language="F#" Value="member this.LinkedServers : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Redis.Models.RedisLinkedServer&gt;" Usage="Microsoft.Azure.Management.Redis.Models.RedisResource.LinkedServers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.linkedServers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Redis.Models.RedisLinkedServer&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="de7e4-130">キャッシュに関連付けられているリンク サーバーの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="de7e4-130">Gets list of the linked servers associated with the cache</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Port">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Port { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Port" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisResource.Port" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Port As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Port : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Redis.Models.RedisResource.Port" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.port")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="de7e4-131">取得は redis 非 SSL ポートです。</span><span class="sxs-lookup"><span data-stu-id="de7e4-131">Gets redis non-SSL port.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisResource.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.Redis.Models.RedisResource.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="de7e4-132">取得は redis インスタンスのプロビジョニングの状態です。</span><span class="sxs-lookup"><span data-stu-id="de7e4-132">Gets redis instance provisioning status.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RedisConfiguration">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; RedisConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; RedisConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisResource.RedisConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property RedisConfiguration As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.RedisConfiguration : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.Redis.Models.RedisResource.RedisConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.redisConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="de7e4-133">取得または Redis のすべての設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="de7e4-133">Gets or sets all Redis Settings.</span></span> <span data-ttu-id="de7e4-134">Few possible keys: rdb-backup-enabled,rdb-storage-connection-string,rdb-backup-frequency,maxmemory-delta,maxmemory-policy,notify-keyspace-events,maxmemory-samples,slowlog-log-slower-than,slowlog-max-len,list-max-ziplist-entries,list-max-ziplist-value,hash-max-ziplist-entries,hash-max-ziplist-value,set-max-intset-entries,zset-max-ziplist-entries,zset-max-ziplist-value etc.</span><span class="sxs-lookup"><span data-stu-id="de7e4-134">Few possible keys: rdb-backup-enabled,rdb-storage-connection-string,rdb-backup-frequency,maxmemory-delta,maxmemory-policy,notify-keyspace-events,maxmemory-samples,slowlog-log-slower-than,slowlog-max-len,list-max-ziplist-entries,list-max-ziplist-value,hash-max-ziplist-entries,hash-max-ziplist-value,set-max-intset-entries,zset-max-ziplist-entries,zset-max-ziplist-value etc.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RedisVersion">
      <MemberSignature Language="C#" Value="public string RedisVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RedisVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisResource.RedisVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RedisVersion As String" />
      <MemberSignature Language="F#" Value="member this.RedisVersion : string" Usage="Microsoft.Azure.Management.Redis.Models.RedisResource.RedisVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.redisVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="de7e4-135">取得は redis バージョンです。</span><span class="sxs-lookup"><span data-stu-id="de7e4-135">Gets redis version.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ShardCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ShardCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ShardCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisResource.ShardCount" />
      <MemberSignature Language="VB.NET" Value="Public Property ShardCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ShardCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Redis.Models.RedisResource.ShardCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.shardCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="de7e4-136">取得または Premium クラスター キャッシュを作成するシャードの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="de7e4-136">Gets or sets the number of shards to be created on a Premium Cluster Cache.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Models.Sku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Redis.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisResource.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Redis.Models.Sku with get, set" Usage="Microsoft.Azure.Management.Redis.Models.RedisResource.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Models.Sku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="de7e4-137">取得または設定を展開する Redis cache の SKU。</span><span class="sxs-lookup"><span data-stu-id="de7e4-137">Gets or sets the SKU of the Redis cache to deploy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SslPort">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; SslPort { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; SslPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisResource.SslPort" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SslPort As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.SslPort : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Redis.Models.RedisResource.SslPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sslPort")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="de7e4-138">取得は redis SSL ポートです。</span><span class="sxs-lookup"><span data-stu-id="de7e4-138">Gets redis SSL port.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StaticIP">
      <MemberSignature Language="C#" Value="public string StaticIP { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StaticIP" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisResource.StaticIP" />
      <MemberSignature Language="VB.NET" Value="Public Property StaticIP As String" />
      <MemberSignature Language="F#" Value="member this.StaticIP : string with get, set" Usage="Microsoft.Azure.Management.Redis.Models.RedisResource.StaticIP" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.staticIP")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="de7e4-139">取得または静的 IP アドレスを設定します。</span><span class="sxs-lookup"><span data-stu-id="de7e4-139">Gets or sets static IP address.</span></span> <span data-ttu-id="de7e4-140">既存の Azure 仮想ネットワーク内 Redis cache を展開するときに必要です。</span><span class="sxs-lookup"><span data-stu-id="de7e4-140">Required when deploying a Redis cache inside an existing Azure Virtual Network.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubnetId">
      <MemberSignature Language="C#" Value="public string SubnetId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubnetId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisResource.SubnetId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubnetId As String" />
      <MemberSignature Language="F#" Value="member this.SubnetId : string with get, set" Usage="Microsoft.Azure.Management.Redis.Models.RedisResource.SubnetId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.subnetId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="de7e4-141">取得またはで Redis cache を展開する仮想ネットワーク内のサブネットの完全なリソース ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="de7e4-141">Gets or sets the full resource ID of a subnet in a virtual network to deploy the Redis cache in.</span></span> <span data-ttu-id="de7e4-142">たとえばの形式:/subscriptions/{subid} 必要な {resourcegroupname}/Microsoft です。{ネットワーク |ClassicNetwork}/VirtualNetworks、vnet1、サブネット/subnet1</span><span class="sxs-lookup"><span data-stu-id="de7e4-142">Example format: /subscriptions/{subid}/resourceGroups/{resourceGroupName}/Microsoft.{Network|ClassicNetwork}/VirtualNetworks/vnet1/subnets/subnet1</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TenantSettings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; TenantSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; TenantSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisResource.TenantSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property TenantSettings As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.TenantSettings : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.Redis.Models.RedisResource.TenantSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.tenantSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="de7e4-143">取得または設定をテナントのディクショナリに設定</span><span class="sxs-lookup"><span data-stu-id="de7e4-143">Gets or sets a dictionary of tenant settings</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Models.RedisResource.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="redisResource.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="de7e4-144">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="de7e4-144">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="de7e4-145">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="de7e4-145">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="Zones">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Zones { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Zones" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisResource.Zones" />
      <MemberSignature Language="VB.NET" Value="Public Property Zones As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Zones : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Redis.Models.RedisResource.Zones" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="zones")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="de7e4-146">取得または設定の可用性の一覧のゾーンでリソースがから取得する必要があるかを示すです。</span><span class="sxs-lookup"><span data-stu-id="de7e4-146">Gets or sets a list of availability zones denoting where the resource needs to come from.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>