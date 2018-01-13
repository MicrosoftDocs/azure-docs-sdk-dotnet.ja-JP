<Type Name="RedisResourceInner" FullName="Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner">
  <TypeSignature Language="C#" Value="public class RedisResourceInner : Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RedisResourceInner extends Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner" />
  <TypeSignature Language="VB.NET" Value="Public Class RedisResourceInner&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type RedisResourceInner = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="af6fb-101">リストまたは Get 操作で 1 つの Redis アイテムです。</span><span class="sxs-lookup"><span data-stu-id="af6fb-101">A single Redis item in List or Get Operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RedisResourceInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="af6fb-102">RedisResourceInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="af6fb-102">Initializes a new instance of the RedisResourceInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RedisResourceInner (string location = null, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.IDictionary&lt;string,string&gt; redisConfiguration = null, Nullable&lt;bool&gt; enableNonSslPort = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tenantSettings = null, Nullable&lt;int&gt; shardCount = null, string subnetId = null, string staticIP = null, Microsoft.Azure.Management.Redis.Fluent.Models.Sku sku = null, string redisVersion = null, string provisioningState = null, string hostName = null, Nullable&lt;int&gt; port = null, Nullable&lt;int&gt; sslPort = null, Microsoft.Azure.Management.Redis.Fluent.Models.RedisAccessKeysInner accessKeys = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; redisConfiguration, valuetype System.Nullable`1&lt;bool&gt; enableNonSslPort, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tenantSettings, valuetype System.Nullable`1&lt;int32&gt; shardCount, string subnetId, string staticIP, class Microsoft.Azure.Management.Redis.Fluent.Models.Sku sku, string redisVersion, string provisioningState, string hostName, valuetype System.Nullable`1&lt;int32&gt; port, valuetype System.Nullable`1&lt;int32&gt; sslPort, class Microsoft.Azure.Management.Redis.Fluent.Models.RedisAccessKeysInner accessKeys) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.IDictionary{System.String,System.String},System.Nullable{System.Boolean},System.Collections.Generic.IDictionary{System.String,System.String},System.Nullable{System.Int32},System.String,System.String,Microsoft.Azure.Management.Redis.Fluent.Models.Sku,System.String,System.String,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},Microsoft.Azure.Management.Redis.Fluent.Models.RedisAccessKeysInner)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.IDictionary&lt;string, string&gt; * Nullable&lt;bool&gt; * System.Collections.Generic.IDictionary&lt;string, string&gt; * Nullable&lt;int&gt; * string * string * Microsoft.Azure.Management.Redis.Fluent.Models.Sku * string * string * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Microsoft.Azure.Management.Redis.Fluent.Models.RedisAccessKeysInner -&gt; Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner" Usage="new Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner (location, id, name, type, tags, redisConfiguration, enableNonSslPort, tenantSettings, shardCount, subnetId, staticIP, sku, redisVersion, provisioningState, hostName, port, sslPort, accessKeys)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
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
        <Parameter Name="sku" Type="Microsoft.Azure.Management.Redis.Fluent.Models.Sku" />
        <Parameter Name="redisVersion" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="hostName" Type="System.String" />
        <Parameter Name="port" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="sslPort" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="accessKeys" Type="Microsoft.Azure.Management.Redis.Fluent.Models.RedisAccessKeysInner" />
      </Parameters>
      <Docs>
        <param name="location">To be added.</param>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="type">To be added.</param>
        <param name="tags">To be added.</param>
        <param name="redisConfiguration"><span data-ttu-id="af6fb-103">すべては Redis の設定です。</span><span class="sxs-lookup"><span data-stu-id="af6fb-103">All Redis Settings.</span></span> <span data-ttu-id="af6fb-104">Few possible keys: rdb-backup-enabled,rdb-storage-connection-string,rdb-backup-frequency,maxmemory-delta,maxmemory-policy,notify-keyspace-events,maxmemory-samples,slowlog-log-slower-than,slowlog-max-len,list-max-ziplist-entries,list-max-ziplist-value,hash-max-ziplist-entries,hash-max-ziplist-value,set-max-intset-entries,zset-max-ziplist-entries,zset-max-ziplist-value etc.</span><span class="sxs-lookup"><span data-stu-id="af6fb-104">Few possible keys: rdb-backup-enabled,rdb-storage-connection-string,rdb-backup-frequency,maxmemory-delta,maxmemory-policy,notify-keyspace-events,maxmemory-samples,slowlog-log-slower-than,slowlog-max-len,list-max-ziplist-entries,list-max-ziplist-value,hash-max-ziplist-entries,hash-max-ziplist-value,set-max-intset-entries,zset-max-ziplist-entries,zset-max-ziplist-value etc.</span></span></param>
        <param name="enableNonSslPort"><span data-ttu-id="af6fb-105">指定するかどうか、非 ssl Redis サーバーのポート (6379) が有効になっています。</span><span class="sxs-lookup"><span data-stu-id="af6fb-105">Specifies whether the non-ssl Redis server port (6379) is enabled.</span></span></param>
        <param name="tenantSettings"><span data-ttu-id="af6fb-106">tenantSettings</span><span class="sxs-lookup"><span data-stu-id="af6fb-106">tenantSettings</span></span></param>
        <param name="shardCount"><span data-ttu-id="af6fb-107">Premium クラスター キャッシュを作成するシャードの数。</span><span class="sxs-lookup"><span data-stu-id="af6fb-107">The number of shards to be created on a Premium Cluster Cache.</span></span></param>
        <param name="subnetId"><span data-ttu-id="af6fb-108">Redis cache を展開する仮想ネットワークのサブネットの完全なリソース ID。</span><span class="sxs-lookup"><span data-stu-id="af6fb-108">The full resource ID of a subnet in a virtual network to deploy the Redis cache in.</span></span> <span data-ttu-id="af6fb-109">たとえばの形式:/subscriptions/{subid} 必要な {resourcegroupname}/Microsoft です。{ネットワーク |ClassicNetwork}/VirtualNetworks、vnet1、サブネット/subnet1</span><span class="sxs-lookup"><span data-stu-id="af6fb-109">Example format: /subscriptions/{subid}/resourceGroups/{resourceGroupName}/Microsoft.{Network|ClassicNetwork}/VirtualNetworks/vnet1/subnets/subnet1</span></span></param>
        <param name="staticIP"><span data-ttu-id="af6fb-110">静的 IP アドレスです。</span><span class="sxs-lookup"><span data-stu-id="af6fb-110">Static IP address.</span></span> <span data-ttu-id="af6fb-111">既存の Azure 仮想ネットワーク内 Redis cache を展開するときに必要です。</span><span class="sxs-lookup"><span data-stu-id="af6fb-111">Required when deploying a Redis cache inside an existing Azure Virtual Network.</span></span></param>
        <param name="sku"><span data-ttu-id="af6fb-112">展開する Redis cache の SKU。</span><span class="sxs-lookup"><span data-stu-id="af6fb-112">The SKU of the Redis cache to deploy.</span></span></param>
        <param name="redisVersion"><span data-ttu-id="af6fb-113">Redis バージョン。</span><span class="sxs-lookup"><span data-stu-id="af6fb-113">Redis version.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="af6fb-114">インスタンスのプロビジョニングの状態、redis します。</span><span class="sxs-lookup"><span data-stu-id="af6fb-114">Redis instance provisioning status.</span></span></param>
        <param name="hostName"><span data-ttu-id="af6fb-115">ホスト名を redis します。</span><span class="sxs-lookup"><span data-stu-id="af6fb-115">Redis host name.</span></span></param>
        <param name="port"><span data-ttu-id="af6fb-116">非 SSL ポートを redis します。</span><span class="sxs-lookup"><span data-stu-id="af6fb-116">Redis non-SSL port.</span></span></param>
        <param name="sslPort"><span data-ttu-id="af6fb-117">SSL ポートを redis します。</span><span class="sxs-lookup"><span data-stu-id="af6fb-117">Redis SSL port.</span></span></param>
        <param name="accessKeys"><span data-ttu-id="af6fb-118">未設定の場合、このオブジェクトは作成または更新プログラムへの応答ではありません - Redis cache のキーの redis キャッシュ</span><span class="sxs-lookup"><span data-stu-id="af6fb-118">The keys of the Redis cache - not set if this object is not the response to Create or Update redis cache</span></span></param>
        <summary>
            <span data-ttu-id="af6fb-119">RedisResourceInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="af6fb-119">Initializes a new instance of the RedisResourceInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessKeys">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.Models.RedisAccessKeysInner AccessKeys { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Redis.Fluent.Models.RedisAccessKeysInner AccessKeys" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner.AccessKeys" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccessKeys As RedisAccessKeysInner" />
      <MemberSignature Language="F#" Value="member this.AccessKeys : Microsoft.Azure.Management.Redis.Fluent.Models.RedisAccessKeysInner" Usage="Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner.AccessKeys" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.accessKeys")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.Models.RedisAccessKeysInner</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="af6fb-120">このオブジェクトがない場合、応答の作成や更新 redis キャッシュを設定できません - Redis cache のキーを取得します。</span><span class="sxs-lookup"><span data-stu-id="af6fb-120">Gets the keys of the Redis cache - not set if this object is not the response to Create or Update redis cache</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableNonSslPort">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableNonSslPort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableNonSslPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner.EnableNonSslPort" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableNonSslPort As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableNonSslPort : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner.EnableNonSslPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="af6fb-121">取得または設定を指定するかどうか、非 ssl Redis サーバーのポート (6379) を有効にします。</span><span class="sxs-lookup"><span data-stu-id="af6fb-121">Gets or sets specifies whether the non-ssl Redis server port (6379) is enabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostName">
      <MemberSignature Language="C#" Value="public string HostName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner.HostName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HostName As String" />
      <MemberSignature Language="F#" Value="member this.HostName : string" Usage="Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner.HostName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="af6fb-122">取得は redis ホスト名です。</span><span class="sxs-lookup"><span data-stu-id="af6fb-122">Gets redis host name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Port">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Port { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Port" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner.Port" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Port As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Port : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner.Port" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="af6fb-123">取得は redis 非 SSL ポートです。</span><span class="sxs-lookup"><span data-stu-id="af6fb-123">Gets redis non-SSL port.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="af6fb-124">取得は redis インスタンスのプロビジョニングの状態です。</span><span class="sxs-lookup"><span data-stu-id="af6fb-124">Gets redis instance provisioning status.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RedisConfiguration">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; RedisConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; RedisConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner.RedisConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property RedisConfiguration As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.RedisConfiguration : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner.RedisConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="af6fb-125">取得または Redis のすべての設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="af6fb-125">Gets or sets all Redis Settings.</span></span> <span data-ttu-id="af6fb-126">Few possible keys: rdb-backup-enabled,rdb-storage-connection-string,rdb-backup-frequency,maxmemory-delta,maxmemory-policy,notify-keyspace-events,maxmemory-samples,slowlog-log-slower-than,slowlog-max-len,list-max-ziplist-entries,list-max-ziplist-value,hash-max-ziplist-entries,hash-max-ziplist-value,set-max-intset-entries,zset-max-ziplist-entries,zset-max-ziplist-value etc.</span><span class="sxs-lookup"><span data-stu-id="af6fb-126">Few possible keys: rdb-backup-enabled,rdb-storage-connection-string,rdb-backup-frequency,maxmemory-delta,maxmemory-policy,notify-keyspace-events,maxmemory-samples,slowlog-log-slower-than,slowlog-max-len,list-max-ziplist-entries,list-max-ziplist-value,hash-max-ziplist-entries,hash-max-ziplist-value,set-max-intset-entries,zset-max-ziplist-entries,zset-max-ziplist-value etc.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RedisVersion">
      <MemberSignature Language="C#" Value="public string RedisVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RedisVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner.RedisVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RedisVersion As String" />
      <MemberSignature Language="F#" Value="member this.RedisVersion : string" Usage="Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner.RedisVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="af6fb-127">取得は redis バージョンです。</span><span class="sxs-lookup"><span data-stu-id="af6fb-127">Gets redis version.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ShardCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ShardCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ShardCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner.ShardCount" />
      <MemberSignature Language="VB.NET" Value="Public Property ShardCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ShardCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner.ShardCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="af6fb-128">取得または Premium クラスター キャッシュを作成するシャードの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="af6fb-128">Gets or sets the number of shards to be created on a Premium Cluster Cache.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.Models.Sku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Redis.Fluent.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Redis.Fluent.Models.Sku with get, set" Usage="Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.Models.Sku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="af6fb-129">取得または設定を展開する Redis cache の SKU。</span><span class="sxs-lookup"><span data-stu-id="af6fb-129">Gets or sets the SKU of the Redis cache to deploy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SslPort">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; SslPort { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; SslPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner.SslPort" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SslPort As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.SslPort : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner.SslPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="af6fb-130">取得は redis SSL ポートです。</span><span class="sxs-lookup"><span data-stu-id="af6fb-130">Gets redis SSL port.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StaticIP">
      <MemberSignature Language="C#" Value="public string StaticIP { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StaticIP" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner.StaticIP" />
      <MemberSignature Language="VB.NET" Value="Public Property StaticIP As String" />
      <MemberSignature Language="F#" Value="member this.StaticIP : string with get, set" Usage="Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner.StaticIP" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="af6fb-131">取得または静的 IP アドレスを設定します。</span><span class="sxs-lookup"><span data-stu-id="af6fb-131">Gets or sets static IP address.</span></span> <span data-ttu-id="af6fb-132">既存の Azure 仮想ネットワーク内 Redis cache を展開するときに必要です。</span><span class="sxs-lookup"><span data-stu-id="af6fb-132">Required when deploying a Redis cache inside an existing Azure Virtual Network.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubnetId">
      <MemberSignature Language="C#" Value="public string SubnetId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubnetId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner.SubnetId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubnetId As String" />
      <MemberSignature Language="F#" Value="member this.SubnetId : string with get, set" Usage="Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner.SubnetId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="af6fb-133">取得またはで Redis cache を展開する仮想ネットワーク内のサブネットの完全なリソース ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="af6fb-133">Gets or sets the full resource ID of a subnet in a virtual network to deploy the Redis cache in.</span></span> <span data-ttu-id="af6fb-134">たとえばの形式:/subscriptions/{subid} 必要な {resourcegroupname}/Microsoft です。{ネットワーク |ClassicNetwork}/VirtualNetworks、vnet1、サブネット/subnet1</span><span class="sxs-lookup"><span data-stu-id="af6fb-134">Example format: /subscriptions/{subid}/resourceGroups/{resourceGroupName}/Microsoft.{Network|ClassicNetwork}/VirtualNetworks/vnet1/subnets/subnet1</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TenantSettings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; TenantSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; TenantSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner.TenantSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property TenantSettings As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.TenantSettings : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner.TenantSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="af6fb-135">取得または設定 tenantSettings</span><span class="sxs-lookup"><span data-stu-id="af6fb-135">Gets or sets tenantSettings</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="redisResourceInner.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="af6fb-136">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="af6fb-136">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="af6fb-137">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="af6fb-137">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>