<Type Name="IRedisCache" FullName="Microsoft.Azure.Management.Redis.Fluent.IRedisCache">
  <TypeSignature Language="C#" Value="public interface IRedisCache : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.Redis.Fluent.IRedisManager,Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Redis.Fluent.IRedisManager&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Redis.Fluent.IRedisCache&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IRedisCache implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource`2&lt;class Microsoft.Azure.Management.Redis.Fluent.IRedisManager, class Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.Redis.Fluent.IRedisManager&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.Redis.Fluent.IRedisCache&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable`1&lt;class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Redis.Fluent.IRedisCache" />
  <TypeSignature Language="VB.NET" Value="Public Interface IRedisCache&#xA;Implements IGroupableResource(Of IRedisManager, RedisResourceInner), IHasInner(Of RedisResourceInner), IHasManager(Of IRedisManager), IRefreshable(Of IRedisCache), IUpdatable(Of IUpdate)" />
  <TypeSignature Language="F#" Value="type IRedisCache = interface&#xA;    interface IGroupableResource&lt;IRedisManager, RedisResourceInner&gt;&#xA;    interface IResource&#xA;    interface IIndexable&#xA;    interface IHasId&#xA;    interface IHasName&#xA;    interface IHasResourceGroup&#xA;    interface IHasManager&lt;IRedisManager&gt;&#xA;    interface IHasInner&lt;RedisResourceInner&gt;&#xA;    interface IRefreshable&lt;IRedisCache&gt;&#xA;    interface IUpdatable&lt;IUpdate&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.Redis.Fluent.IRedisManager,Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Redis.Fluent.IRedisManager&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Redis.Fluent.IRedisCache&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="089e7-101">Azure Redis Cache の変更できないクライアント側表現。</span><span class="sxs-lookup"><span data-stu-id="089e7-101">An immutable client-side representation of an Azure Redis Cache.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AsPremium">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.IRedisCachePremium AsPremium ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Redis.Fluent.IRedisCachePremium AsPremium() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.IRedisCache.AsPremium" />
      <MemberSignature Language="VB.NET" Value="Public Function AsPremium () As IRedisCachePremium" />
      <MemberSignature Language="F#" Value="abstract member AsPremium : unit -&gt; Microsoft.Azure.Management.Redis.Fluent.IRedisCachePremium" Usage="iRedisCache.AsPremium " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.IRedisCachePremium</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="089e7-102">Premium Sku Redis Cache のインスタンスにのみ使用可能な機能を公開します。</span><span class="sxs-lookup"><span data-stu-id="089e7-102">Exposes features available only to Premium Sku Redis Cache instances.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="GetKeys">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.IRedisAccessKeys GetKeys ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Redis.Fluent.IRedisAccessKeys GetKeys() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.IRedisCache.GetKeys" />
      <MemberSignature Language="VB.NET" Value="Public Function GetKeys () As IRedisAccessKeys" />
      <MemberSignature Language="F#" Value="abstract member GetKeys : unit -&gt; Microsoft.Azure.Management.Redis.Fluent.IRedisAccessKeys" Usage="iRedisCache.GetKeys " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.IRedisAccessKeys</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="089e7-103">Redis Cache のアクセス キーを取得します。</span><span class="sxs-lookup"><span data-stu-id="089e7-103">Gets a Redis Cache's access keys.</span></span> <span data-ttu-id="089e7-104">この操作には、キャッシュのリソースに対する書き込み権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="089e7-104">This operation requires write permission to the Cache resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostName">
      <MemberSignature Language="C#" Value="public string HostName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Fluent.IRedisCache.HostName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HostName As String" />
      <MemberSignature Language="F#" Value="member this.HostName : string" Usage="Microsoft.Azure.Management.Redis.Fluent.IRedisCache.HostName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="089e7-105">ホスト名の値を取得します。</span><span class="sxs-lookup"><span data-stu-id="089e7-105">Gets the hostName value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsPremium">
      <MemberSignature Language="C#" Value="public bool IsPremium { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsPremium" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Fluent.IRedisCache.IsPremium" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsPremium As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsPremium : bool" Usage="Microsoft.Azure.Management.Redis.Fluent.IRedisCache.IsPremium" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="089e7-106">Redis Cache の現在のインスタンスに Premium Sku が設定されている場合は、true を返しますを取得します。</span><span class="sxs-lookup"><span data-stu-id="089e7-106">Gets returns true if current Redis Cache instance has Premium Sku.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Keys">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.IRedisAccessKeys Keys { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Redis.Fluent.IRedisAccessKeys Keys" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Fluent.IRedisCache.Keys" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Keys As IRedisAccessKeys" />
      <MemberSignature Language="F#" Value="member this.Keys : Microsoft.Azure.Management.Redis.Fluent.IRedisAccessKeys" Usage="Microsoft.Azure.Management.Redis.Fluent.IRedisCache.Keys" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.IRedisAccessKeys</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NonSslPort">
      <MemberSignature Language="C#" Value="public bool NonSslPort { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool NonSslPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Fluent.IRedisCache.NonSslPort" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NonSslPort As Boolean" />
      <MemberSignature Language="F#" Value="member this.NonSslPort : bool" Usage="Microsoft.Azure.Management.Redis.Fluent.IRedisCache.NonSslPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="089e7-107">非 SSL ポートは有効な場合は false をそれ以外の場合は true を取得します。</span><span class="sxs-lookup"><span data-stu-id="089e7-107">Gets true if non SSL port is enabled, false otherwise.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Port">
      <MemberSignature Language="C#" Value="public int Port { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Port" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Fluent.IRedisCache.Port" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Port As Integer" />
      <MemberSignature Language="F#" Value="member this.Port : int" Usage="Microsoft.Azure.Management.Redis.Fluent.IRedisCache.Port" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="089e7-108">ポートの値を取得します。</span><span class="sxs-lookup"><span data-stu-id="089e7-108">Gets the port value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Fluent.IRedisCache.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.Redis.Fluent.IRedisCache.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="089e7-109">ProvisioningState 値を取得します。</span><span class="sxs-lookup"><span data-stu-id="089e7-109">Gets the provisioningState value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RedisConfiguration">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,string&gt; RedisConfiguration { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, string&gt; RedisConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Fluent.IRedisCache.RedisConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RedisConfiguration As IReadOnlyDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.RedisConfiguration : System.Collections.Generic.IReadOnlyDictionary&lt;string, string&gt;" Usage="Microsoft.Azure.Management.Redis.Fluent.IRedisCache.RedisConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="089e7-110">Redis 構成値を取得します。</span><span class="sxs-lookup"><span data-stu-id="089e7-110">Gets the Redis configuration value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RedisVersion">
      <MemberSignature Language="C#" Value="public string RedisVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RedisVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Fluent.IRedisCache.RedisVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RedisVersion As String" />
      <MemberSignature Language="F#" Value="member this.RedisVersion : string" Usage="Microsoft.Azure.Management.Redis.Fluent.IRedisCache.RedisVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="089e7-111">Redis バージョンの値を取得します。</span><span class="sxs-lookup"><span data-stu-id="089e7-111">Gets the Redis version value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshKeys">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.IRedisAccessKeys RefreshKeys ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Redis.Fluent.IRedisAccessKeys RefreshKeys() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.IRedisCache.RefreshKeys" />
      <MemberSignature Language="VB.NET" Value="Public Function RefreshKeys () As IRedisAccessKeys" />
      <MemberSignature Language="F#" Value="abstract member RefreshKeys : unit -&gt; Microsoft.Azure.Management.Redis.Fluent.IRedisAccessKeys" Usage="iRedisCache.RefreshKeys " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.IRedisAccessKeys</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="089e7-112">Redis キャッシュ用 Azure からの最新の状態のアクセス キーを取得します。</span><span class="sxs-lookup"><span data-stu-id="089e7-112">Fetch the up-to-date access keys from Azure for this Redis Cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="089e7-113">この Redis Cache のアクセス キー。</span><span class="sxs-lookup"><span data-stu-id="089e7-113">The access keys for this Redis Cache.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKey">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.IRedisAccessKeys RegenerateKey (Microsoft.Azure.Management.Redis.Fluent.Models.RedisKeyType keyType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Redis.Fluent.IRedisAccessKeys RegenerateKey(valuetype Microsoft.Azure.Management.Redis.Fluent.Models.RedisKeyType keyType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.IRedisCache.RegenerateKey(Microsoft.Azure.Management.Redis.Fluent.Models.RedisKeyType)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegenerateKey (keyType As RedisKeyType) As IRedisAccessKeys" />
      <MemberSignature Language="F#" Value="abstract member RegenerateKey : Microsoft.Azure.Management.Redis.Fluent.Models.RedisKeyType -&gt; Microsoft.Azure.Management.Redis.Fluent.IRedisAccessKeys" Usage="iRedisCache.RegenerateKey keyType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.IRedisAccessKeys</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyType" Type="Microsoft.Azure.Management.Redis.Fluent.Models.RedisKeyType" />
      </Parameters>
      <Docs>
        <param name="keyType"><span data-ttu-id="089e7-114">キーの型を再生成します。</span><span class="sxs-lookup"><span data-stu-id="089e7-114">Key type to regenerate.</span></span></param>
        <summary>
            <span data-ttu-id="089e7-115">この Redis Cache のアクセス キーを再生成します。</span><span class="sxs-lookup"><span data-stu-id="089e7-115">Regenerates the access keys for this Redis Cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="089e7-116">生成されたアクセスは、この Redis Cache をキーします。</span><span class="sxs-lookup"><span data-stu-id="089e7-116">The generated access keys for this Redis Cache.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="ShardCount">
      <MemberSignature Language="C#" Value="public int ShardCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ShardCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Fluent.IRedisCache.ShardCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ShardCount As Integer" />
      <MemberSignature Language="F#" Value="member this.ShardCount : int" Usage="Microsoft.Azure.Management.Redis.Fluent.IRedisCache.ShardCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="089e7-117">ShardCount 値を取得します。</span><span class="sxs-lookup"><span data-stu-id="089e7-117">Gets the shardCount value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.Models.Sku Sku { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Redis.Fluent.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Fluent.IRedisCache.Sku" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Redis.Fluent.Models.Sku" Usage="Microsoft.Azure.Management.Redis.Fluent.IRedisCache.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.Models.Sku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="089e7-118">Sku 値を取得します。</span><span class="sxs-lookup"><span data-stu-id="089e7-118">Gets the sku value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SslPort">
      <MemberSignature Language="C#" Value="public int SslPort { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 SslPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Fluent.IRedisCache.SslPort" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SslPort As Integer" />
      <MemberSignature Language="F#" Value="member this.SslPort : int" Usage="Microsoft.Azure.Management.Redis.Fluent.IRedisCache.SslPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="089e7-119">SslPort 値を取得します。</span><span class="sxs-lookup"><span data-stu-id="089e7-119">Gets the sslPort value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StaticIP">
      <MemberSignature Language="C#" Value="public string StaticIP { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StaticIP" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Fluent.IRedisCache.StaticIP" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StaticIP As String" />
      <MemberSignature Language="F#" Value="member this.StaticIP : string" Usage="Microsoft.Azure.Management.Redis.Fluent.IRedisCache.StaticIP" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="089e7-120">静的 ip アドレスの値を取得します。</span><span class="sxs-lookup"><span data-stu-id="089e7-120">Gets the staticIP value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubnetId">
      <MemberSignature Language="C#" Value="public string SubnetId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubnetId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Fluent.IRedisCache.SubnetId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SubnetId As String" />
      <MemberSignature Language="F#" Value="member this.SubnetId : string" Usage="Microsoft.Azure.Management.Redis.Fluent.IRedisCache.SubnetId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="089e7-121">&lt; 値を取得します。</span><span class="sxs-lookup"><span data-stu-id="089e7-121">Gets the subnetId value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>