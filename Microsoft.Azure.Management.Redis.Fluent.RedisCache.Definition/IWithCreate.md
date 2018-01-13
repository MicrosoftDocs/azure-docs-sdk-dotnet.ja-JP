<Type Name="IWithCreate" FullName="Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate">
  <TypeSignature Language="C#" Value="public interface IWithCreate : Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags&lt;Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Redis.Fluent.IRedisCache&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithCreate implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags`1&lt;class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Redis.Fluent.IRedisCache&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithCreate&#xA;Implements ICreatable(Of IRedisCache), IDefinitionWithTags(Of IWithCreate)" />
  <TypeSignature Language="F#" Value="type IWithCreate = interface&#xA;    interface ICreatable&lt;IRedisCache&gt;&#xA;    interface IIndexable&#xA;    interface IDefinitionWithTags&lt;IWithCreate&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags&lt;Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Redis.Fluent.IRedisCache&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="f715b-101">クラウドを指定する省略可能な追加の入力を公開する新しい Redis Cache を作成するための十分な入力で Redis Cache 定義します。</span><span class="sxs-lookup"><span data-stu-id="f715b-101">A Redis Cache definition with sufficient inputs to create a new Redis Cache in the cloud, but exposing additional optional inputs to specify.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithNonSslPort">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate WithNonSslPort ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate WithNonSslPort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate.WithNonSslPort" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNonSslPort () As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNonSslPort : unit -&gt; Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate" Usage="iWithCreate.WithNonSslPort " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f715b-102">ポート (6379 を) の Redis サーバーの非 ssl を有効にします。</span><span class="sxs-lookup"><span data-stu-id="f715b-102">Enables non-ssl Redis server port (6379).</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="f715b-103">Redis Cache の定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="f715b-103">The next stage of Redis Cache definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithRedisConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate WithRedisConfiguration (System.Collections.Generic.IDictionary&lt;string,string&gt; redisConfiguration);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate WithRedisConfiguration(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; redisConfiguration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate.WithRedisConfiguration(System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRedisConfiguration (redisConfiguration As IDictionary(Of String, String)) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithRedisConfiguration : System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate" Usage="iWithCreate.WithRedisConfiguration redisConfiguration" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="redisConfiguration" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="redisConfiguration"><span data-ttu-id="f715b-104">構成名でインデックス付けされたマップとして Redis Cache の構成。</span><span class="sxs-lookup"><span data-stu-id="f715b-104">Configuration of Redis Cache as a map indexed by configuration name.</span></span></param>
        <summary>
            <span data-ttu-id="f715b-105">すべては Redis の設定です。</span><span class="sxs-lookup"><span data-stu-id="f715b-105">All Redis Settings.</span></span> <span data-ttu-id="f715b-106">いくつかの可能なキー: rdb バックアップ-有効になっている、rdb ストレージ接続文字列、rdb のバックアップの頻度、maxmemory デルタ、maxmemory ポリシー、通知 keyspace イベント、maxmemory サンプル slowlog-ログ-低速の設定よりも、slowlog max-len リスト max-ziplist エントリ、リスト max-ziplist 値、ハッシュの最大-ziplist-エントリ、ハッシュ max-ziplist 値、- 最大値-intset-エントリ、zset 最大 ziplist エントリ、zset 最大 ziplist-値などです。</span><span class="sxs-lookup"><span data-stu-id="f715b-106">Few possible keys: rdb-backup-enabled, rdb-storage-connection-string, rdb-backup-frequency, maxmemory-delta, maxmemory-policy, notify-keyspace-events, maxmemory-samples, slowlog-log-slower-than, slowlog-max-len, list-max-ziplist-entries, list-max-ziplist-value, hash-max-ziplist-entries, hash-max-ziplist-value, set -max-intset-entries, zset-max-ziplist-entries, zset-max-ziplist-value etc.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="f715b-107">Redis Cache の定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="f715b-107">The next stage of Redis Cache definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithRedisConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate WithRedisConfiguration (string key, string value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate WithRedisConfiguration(string key, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate.WithRedisConfiguration(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRedisConfiguration (key As String, value As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithRedisConfiguration : string * string -&gt; Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate" Usage="iWithCreate.WithRedisConfiguration (key, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="f715b-108">構成名を redis します。</span><span class="sxs-lookup"><span data-stu-id="f715b-108">Redis configuration name.</span></span></param>
        <param name="value"><span data-ttu-id="f715b-109">構成値を redis します。</span><span class="sxs-lookup"><span data-stu-id="f715b-109">Redis configuration value.</span></span></param>
        <summary>
            <span data-ttu-id="f715b-110">Redis の設定を指定します。</span><span class="sxs-lookup"><span data-stu-id="f715b-110">Specifies Redis Setting.</span></span>
            <span data-ttu-id="f715b-111">rdb バックアップ-有効になっている、rdb ストレージ接続文字列、rdb のバックアップの頻度、maxmemory デルタ、maxmemory ポリシー、通知 keyspace イベント、maxmemory サンプル slowlog-ログ-低速の設定よりも、slowlog max-len リスト max-ziplist エントリ、リスト max-ziplist 値、ハッシュの最大-ziplist-エントリ、ハッシュ max-ziplist 値、- 最大値-intset-エントリ、zset 最大 ziplist エントリ、zset 最大 ziplist-値などです。</span><span class="sxs-lookup"><span data-stu-id="f715b-111">rdb-backup-enabled, rdb-storage-connection-string, rdb-backup-frequency, maxmemory-delta, maxmemory-policy, notify-keyspace-events, maxmemory-samples, slowlog-log-slower-than, slowlog-max-len, list-max-ziplist-entries, list-max-ziplist-value, hash-max-ziplist-entries, hash-max-ziplist-value, set -max-intset-entries, zset-max-ziplist-entries, zset-max-ziplist-value etc.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="f715b-112">Redis Cache の定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="f715b-112">The next stage of Redis Cache definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithStaticIP">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate WithStaticIP (string staticIP);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate WithStaticIP(string staticIP) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate.WithStaticIP(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithStaticIP (staticIP As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithStaticIP : string -&gt; Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate" Usage="iWithCreate.WithStaticIP staticIP" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="staticIP" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="staticIP"><span data-ttu-id="f715b-113">静的 IP 設定する値。</span><span class="sxs-lookup"><span data-stu-id="f715b-113">The static IP value to set.</span></span></param>
        <summary>
            <span data-ttu-id="f715b-114">Redis Cache の静的 IP を設定します。</span><span class="sxs-lookup"><span data-stu-id="f715b-114">Sets Redis Cache static IP.</span></span> <span data-ttu-id="f715b-115">既存の Azure 仮想ネットワーク内 Redis Cache を展開するときに必要です。</span><span class="sxs-lookup"><span data-stu-id="f715b-115">Required when deploying a Redis Cache inside an existing Azure Virtual Network.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="f715b-116">Redis Cache の定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="f715b-116">The next stage of Redis Cache definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithSubnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate WithSubnet (Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId network, string subnetName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate WithSubnet(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId network, string subnetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate.WithSubnet(Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSubnet (network As IHasId, subnetName As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithSubnet : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId * string -&gt; Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate" Usage="iWithCreate.WithSubnet (network, subnetName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="network" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId" />
        <Parameter Name="subnetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="network"><span data-ttu-id="f715b-117">ネットワークのオブジェクトのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="f715b-117">Instance of Network object.</span></span></param>
        <param name="subnetName"><span data-ttu-id="f715b-118">サブネットの名前。</span><span class="sxs-lookup"><span data-stu-id="f715b-118">The name of the subnet.</span></span></param>
        <summary>
            <span data-ttu-id="f715b-119">Redis Cache のこのインスタンスに指定されたサブネットを割り当てます。</span><span class="sxs-lookup"><span data-stu-id="f715b-119">Assigns the specified subnet to this instance of Redis Cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="f715b-120">Redis Cache の定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="f715b-120">The next stage of Redis Cache definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>