<Type Name="IWithPremiumSkuCreate" FullName="Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithPremiumSkuCreate">
  <TypeSignature Language="C#" Value="public interface IWithPremiumSkuCreate : Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate, Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags&lt;Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Redis.Fluent.IRedisCache&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPremiumSkuCreate implements class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags`1&lt;class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Redis.Fluent.IRedisCache&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithPremiumSkuCreate" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPremiumSkuCreate&#xA;Implements ICreatable(Of IRedisCache), IDefinitionWithTags(Of IWithCreate), IWithCreate" />
  <TypeSignature Language="F#" Value="type IWithPremiumSkuCreate = interface&#xA;    interface IWithCreate&#xA;    interface ICreatable&lt;IRedisCache&gt;&#xA;    interface IIndexable&#xA;    interface IDefinitionWithTags&lt;IWithCreate&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags&lt;Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Redis.Fluent.IRedisCache&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="29f09-101">Premium Sku 固有の機能を持つ Redis Cache 定義します。</span><span class="sxs-lookup"><span data-stu-id="29f09-101">A Redis Cache definition with Premium Sku specific functionality.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithPatchSchedule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithPremiumSkuCreate WithPatchSchedule (Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntry scheduleEntry);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithPremiumSkuCreate WithPatchSchedule(class Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntry scheduleEntry) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithPremiumSkuCreate.WithPatchSchedule(Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntry)" />
      <MemberSignature Language="F#" Value="abstract member WithPatchSchedule : Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntry -&gt; Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithPremiumSkuCreate" Usage="iWithPremiumSkuCreate.WithPatchSchedule scheduleEntry" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithPremiumSkuCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scheduleEntry" Type="Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntry" />
      </Parameters>
      <Docs>
        <param name="scheduleEntry"><span data-ttu-id="29f09-102">Redis Cache の Premium のパッチ スケジュール エントリです。</span><span class="sxs-lookup"><span data-stu-id="29f09-102">Patch schedule entry for Premium Redis Cache.</span></span></param>
        <summary>
            <span data-ttu-id="29f09-103">Premium クラスター キャッシュでスケジュールの更新プログラム。</span><span class="sxs-lookup"><span data-stu-id="29f09-103">Patch schedule on a Premium Cluster Cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="29f09-104">Redis Cache の次のステージを Premium SKU 定義を使用します。</span><span class="sxs-lookup"><span data-stu-id="29f09-104">The next stage of Redis Cache with Premium SKU definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithPatchSchedule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithPremiumSkuCreate WithPatchSchedule (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntry&gt; scheduleEntry);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithPremiumSkuCreate WithPatchSchedule(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntry&gt; scheduleEntry) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithPremiumSkuCreate.WithPatchSchedule(System.Collections.Generic.IList{Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntry})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPatchSchedule (scheduleEntry As IList(Of ScheduleEntry)) As IWithPremiumSkuCreate" />
      <MemberSignature Language="F#" Value="abstract member WithPatchSchedule : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntry&gt; -&gt; Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithPremiumSkuCreate" Usage="iWithPremiumSkuCreate.WithPatchSchedule scheduleEntry" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithPremiumSkuCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scheduleEntry" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntry&gt;" />
      </Parameters>
      <Docs>
        <param name="scheduleEntry"><span data-ttu-id="29f09-105">Redis Cache の Premium のパッチ スケジュール エントリの一覧です。</span><span class="sxs-lookup"><span data-stu-id="29f09-105">List of patch schedule entries for Premium Redis Cache.</span></span></param>
        <summary>
            <span data-ttu-id="29f09-106">Premium クラスター キャッシュでスケジュールの更新プログラム。</span><span class="sxs-lookup"><span data-stu-id="29f09-106">Patch schedule on a Premium Cluster Cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="29f09-107">Redis Cache の次のステージを Premium SKU 定義を使用します。</span><span class="sxs-lookup"><span data-stu-id="29f09-107">The next stage of Redis Cache with Premium SKU definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithPatchSchedule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithPremiumSkuCreate WithPatchSchedule (Microsoft.Azure.Management.Redis.Fluent.Models.DayOfWeek dayOfWeek, int startHourUtc);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithPremiumSkuCreate WithPatchSchedule(valuetype Microsoft.Azure.Management.Redis.Fluent.Models.DayOfWeek dayOfWeek, int32 startHourUtc) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithPremiumSkuCreate.WithPatchSchedule(Microsoft.Azure.Management.Redis.Fluent.Models.DayOfWeek,System.Int32)" />
      <MemberSignature Language="F#" Value="abstract member WithPatchSchedule : Microsoft.Azure.Management.Redis.Fluent.Models.DayOfWeek * int -&gt; Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithPremiumSkuCreate" Usage="iWithPremiumSkuCreate.WithPatchSchedule (dayOfWeek, startHourUtc)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithPremiumSkuCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="dayOfWeek" Type="Microsoft.Azure.Management.Redis.Fluent.Models.DayOfWeek" />
        <Parameter Name="startHourUtc" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="dayOfWeek"><span data-ttu-id="29f09-108">キャッシュにパッチできると曜日です。</span><span class="sxs-lookup"><span data-stu-id="29f09-108">Day of week when cache can be patched.</span></span></param>
        <param name="startHourUtc"><span data-ttu-id="29f09-109">開始時刻がどのキャッシュ後に修正プログラムの適用開始できます。</span><span class="sxs-lookup"><span data-stu-id="29f09-109">Start hour after which cache patching can start.</span></span></param>
        <summary>
            <span data-ttu-id="29f09-110">Premium クラスター キャッシュでスケジュールの更新プログラム。</span><span class="sxs-lookup"><span data-stu-id="29f09-110">Patch schedule on a Premium Cluster Cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="29f09-111">Redis Cache の次のステージを Premium SKU 定義を使用します。</span><span class="sxs-lookup"><span data-stu-id="29f09-111">The next stage of Redis Cache with Premium SKU definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithPatchSchedule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithPremiumSkuCreate WithPatchSchedule (Microsoft.Azure.Management.Redis.Fluent.Models.DayOfWeek dayOfWeek, int startHourUtc, TimeSpan maintenanceWindow);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithPremiumSkuCreate WithPatchSchedule(valuetype Microsoft.Azure.Management.Redis.Fluent.Models.DayOfWeek dayOfWeek, int32 startHourUtc, valuetype System.TimeSpan maintenanceWindow) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithPremiumSkuCreate.WithPatchSchedule(Microsoft.Azure.Management.Redis.Fluent.Models.DayOfWeek,System.Int32,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="abstract member WithPatchSchedule : Microsoft.Azure.Management.Redis.Fluent.Models.DayOfWeek * int * TimeSpan -&gt; Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithPremiumSkuCreate" Usage="iWithPremiumSkuCreate.WithPatchSchedule (dayOfWeek, startHourUtc, maintenanceWindow)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithPremiumSkuCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="dayOfWeek" Type="Microsoft.Azure.Management.Redis.Fluent.Models.DayOfWeek" />
        <Parameter Name="startHourUtc" Type="System.Int32" />
        <Parameter Name="maintenanceWindow" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="dayOfWeek"><span data-ttu-id="29f09-112">キャッシュにパッチできると曜日です。</span><span class="sxs-lookup"><span data-stu-id="29f09-112">Day of week when cache can be patched.</span></span></param>
        <param name="startHourUtc"><span data-ttu-id="29f09-113">開始時刻がどのキャッシュ後に修正プログラムの適用開始できます。</span><span class="sxs-lookup"><span data-stu-id="29f09-113">Start hour after which cache patching can start.</span></span></param>
        <param name="maintenanceWindow"><span data-ttu-id="29f09-114">ISO8601 timespan をどの程度時間キャッシュ修正プログラムの適用を指定することがかかることができます。</span><span class="sxs-lookup"><span data-stu-id="29f09-114">ISO8601 timespan specifying how much time cache patching can take.</span></span></param>
        <summary>
            <span data-ttu-id="29f09-115">Premium クラスター キャッシュでスケジュールの更新プログラム。</span><span class="sxs-lookup"><span data-stu-id="29f09-115">Patch schedule on a Premium Cluster Cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="29f09-116">Redis Cache の次のステージを Premium SKU 定義を使用します。</span><span class="sxs-lookup"><span data-stu-id="29f09-116">The next stage of Redis Cache with Premium SKU definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithShardCount">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithPremiumSkuCreate WithShardCount (int shardCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithPremiumSkuCreate WithShardCount(int32 shardCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithPremiumSkuCreate.WithShardCount(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithShardCount (shardCount As Integer) As IWithPremiumSkuCreate" />
      <MemberSignature Language="F#" Value="abstract member WithShardCount : int -&gt; Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithPremiumSkuCreate" Usage="iWithPremiumSkuCreate.WithShardCount shardCount" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithPremiumSkuCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="shardCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="shardCount"><span data-ttu-id="29f09-117">設定するシャード数の値。</span><span class="sxs-lookup"><span data-stu-id="29f09-117">The shard count value to set.</span></span></param>
        <summary>
            <span data-ttu-id="29f09-118">Premium クラスター キャッシュを作成するシャードの数。</span><span class="sxs-lookup"><span data-stu-id="29f09-118">The number of shards to be created on a Premium Cluster Cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="29f09-119">Redis Cache の次のステージを Premium SKU 定義を使用します。</span><span class="sxs-lookup"><span data-stu-id="29f09-119">The next stage of Redis Cache with Premium SKU definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>