<Type Name="RedisCreateParameters" FullName="Microsoft.Azure.Management.Redis.Models.RedisCreateParameters">
  <TypeSignature Language="C#" Value="public class RedisCreateParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RedisCreateParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Redis.Models.RedisCreateParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class RedisCreateParameters" />
  <TypeSignature Language="F#" Value="type RedisCreateParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Redis.Models.Resource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            パラメーターは、Redis 作成操作に指定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RedisCreateParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Models.RedisCreateParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            RedisCreateParameters クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RedisCreateParameters (Microsoft.Azure.Management.Redis.Models.Sku sku, string location, System.Collections.Generic.IDictionary&lt;string,string&gt; redisConfiguration = null, Nullable&lt;bool&gt; enableNonSslPort = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tenantSettings = null, Nullable&lt;int&gt; shardCount = null, string subnetId = null, string staticIP = null, System.Collections.Generic.IList&lt;string&gt; zones = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Redis.Models.Sku sku, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; redisConfiguration, valuetype System.Nullable`1&lt;bool&gt; enableNonSslPort, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tenantSettings, valuetype System.Nullable`1&lt;int32&gt; shardCount, string subnetId, string staticIP, class System.Collections.Generic.IList`1&lt;string&gt; zones, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Models.RedisCreateParameters.#ctor(Microsoft.Azure.Management.Redis.Models.Sku,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Nullable{System.Boolean},System.Collections.Generic.IDictionary{System.String,System.String},System.Nullable{System.Int32},System.String,System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Redis.Models.RedisCreateParameters : Microsoft.Azure.Management.Redis.Models.Sku * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Nullable&lt;bool&gt; * System.Collections.Generic.IDictionary&lt;string, string&gt; * Nullable&lt;int&gt; * string * string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.Redis.Models.RedisCreateParameters" Usage="new Microsoft.Azure.Management.Redis.Models.RedisCreateParameters (sku, location, redisConfiguration, enableNonSslPort, tenantSettings, shardCount, subnetId, staticIP, zones, tags)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sku" Type="Microsoft.Azure.Management.Redis.Models.Sku" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="redisConfiguration" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="enableNonSslPort" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="tenantSettings" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="shardCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="subnetId" Type="System.String" />
        <Parameter Name="staticIP" Type="System.String" />
        <Parameter Name="zones" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="sku">展開する Redis cache の SKU。</param>
        <param name="location">リソースが存在する地理的な場所</param>
        <param name="redisConfiguration">すべては Redis の設定です。 Few possible keys: rdb-backup-enabled,rdb-storage-connection-string,rdb-backup-frequency,maxmemory-delta,maxmemory-policy,notify-keyspace-events,maxmemory-samples,slowlog-log-slower-than,slowlog-max-len,list-max-ziplist-entries,list-max-ziplist-value,hash-max-ziplist-entries,hash-max-ziplist-value,set-max-intset-entries,zset-max-ziplist-entries,zset-max-ziplist-value etc.</param>
        <param name="enableNonSslPort">指定するかどうか、非 ssl Redis サーバーのポート (6379) が有効になっています。</param>
        <param name="tenantSettings">テナント設定のディクショナリ</param>
        <param name="shardCount">Premium クラスター キャッシュを作成するシャードの数。</param>
        <param name="subnetId">Redis cache を展開する仮想ネットワークのサブネットの完全なリソース ID。 たとえばの形式:/subscriptions/{subid} 必要な {resourcegroupname}/Microsoft です。{ネットワーク |ClassicNetwork}/VirtualNetworks、vnet1、サブネット/subnet1</param>
        <param name="staticIP">静的 IP アドレスです。 既存の Azure 仮想ネットワーク内 Redis cache を展開するときに必要です。</param>
        <param name="zones">可用性の一覧のゾーンでリソースがから取得する必要があるかを示すです。</param>
        <param name="tags">リソース タグ。</param>
        <summary>
            RedisCreateParameters クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableNonSslPort">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableNonSslPort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableNonSslPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisCreateParameters.EnableNonSslPort" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableNonSslPort As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableNonSslPort : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Redis.Models.RedisCreateParameters.EnableNonSslPort" />
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
            取得または設定を指定するかどうか、非 ssl Redis サーバーのポート (6379) を有効にします。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisCreateParameters.Location" />
      <MemberSignature Language="VB.NET" Value="Public Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string with get, set" Usage="Microsoft.Azure.Management.Redis.Models.RedisCreateParameters.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="location")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはリソースが存在する場所を地理的な場所に設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RedisConfiguration">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; RedisConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; RedisConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisCreateParameters.RedisConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property RedisConfiguration As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.RedisConfiguration : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.Redis.Models.RedisCreateParameters.RedisConfiguration" />
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
            取得または Redis のすべての設定を設定します。 Few possible keys: rdb-backup-enabled,rdb-storage-connection-string,rdb-backup-frequency,maxmemory-delta,maxmemory-policy,notify-keyspace-events,maxmemory-samples,slowlog-log-slower-than,slowlog-max-len,list-max-ziplist-entries,list-max-ziplist-value,hash-max-ziplist-entries,hash-max-ziplist-value,set-max-intset-entries,zset-max-ziplist-entries,zset-max-ziplist-value etc.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ShardCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ShardCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ShardCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisCreateParameters.ShardCount" />
      <MemberSignature Language="VB.NET" Value="Public Property ShardCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ShardCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Redis.Models.RedisCreateParameters.ShardCount" />
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
            取得または Premium クラスター キャッシュを作成するシャードの数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Models.Sku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Redis.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisCreateParameters.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Redis.Models.Sku with get, set" Usage="Microsoft.Azure.Management.Redis.Models.RedisCreateParameters.Sku" />
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
            取得または設定を展開する Redis cache の SKU。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StaticIP">
      <MemberSignature Language="C#" Value="public string StaticIP { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StaticIP" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisCreateParameters.StaticIP" />
      <MemberSignature Language="VB.NET" Value="Public Property StaticIP As String" />
      <MemberSignature Language="F#" Value="member this.StaticIP : string with get, set" Usage="Microsoft.Azure.Management.Redis.Models.RedisCreateParameters.StaticIP" />
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
            取得または静的 IP アドレスを設定します。 既存の Azure 仮想ネットワーク内 Redis cache を展開するときに必要です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubnetId">
      <MemberSignature Language="C#" Value="public string SubnetId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubnetId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisCreateParameters.SubnetId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubnetId As String" />
      <MemberSignature Language="F#" Value="member this.SubnetId : string with get, set" Usage="Microsoft.Azure.Management.Redis.Models.RedisCreateParameters.SubnetId" />
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
            取得またはで Redis cache を展開する仮想ネットワーク内のサブネットの完全なリソース ID を設定します。 たとえばの形式:/subscriptions/{subid} 必要な {resourcegroupname}/Microsoft です。{ネットワーク |ClassicNetwork}/VirtualNetworks、vnet1、サブネット/subnet1
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisCreateParameters.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.Redis.Models.RedisCreateParameters.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tags")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはリソース タグを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TenantSettings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; TenantSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; TenantSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisCreateParameters.TenantSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property TenantSettings As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.TenantSettings : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.Redis.Models.RedisCreateParameters.TenantSettings" />
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
            取得または設定をテナントのディクショナリに設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Models.RedisCreateParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="redisCreateParameters.Validate " />
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
            オブジェクトを検証します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            検証が失敗した場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="Zones">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Zones { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Zones" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisCreateParameters.Zones" />
      <MemberSignature Language="VB.NET" Value="Public Property Zones As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Zones : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Redis.Models.RedisCreateParameters.Zones" />
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
            取得または設定の可用性の一覧のゾーンでリソースがから取得する必要があるかを示すです。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>