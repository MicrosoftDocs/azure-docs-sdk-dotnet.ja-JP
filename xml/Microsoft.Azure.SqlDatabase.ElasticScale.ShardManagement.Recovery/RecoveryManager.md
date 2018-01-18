<Type Name="RecoveryManager" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager">
  <TypeSignature Language="C#" Value="public sealed class RecoveryManager" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit RecoveryManager extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class RecoveryManager" />
  <TypeSignature Language="F#" Value="type RecoveryManager = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
    <AssemblyVersion>1.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f4a1a-101">さまざまな回復を管理するシャードのマップ manager に関連するタスク。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-101">Manages various recovery related tasks for a shard map manager.</span></span> <span data-ttu-id="f4a1a-102">シャード マップの情報およびグローバル シャードのマップ manager データベース、シャードにローカルに格納されている間のデータ破損の問題を解決するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-102">It helps resolving data corruption issues between shard map information stored locally on the shards and in the global shard map manager database.</span></span> <span data-ttu-id="f4a1a-103">また、特定の '不測' データベースのバックアップまたはデータベース コピー数のシャード マップの再構築が必要な回復シナリオ。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-103">It also helps with certain 'oops' recovery scenarios where reconstruction of shard maps from database backups or database copies is necessary.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="f4a1a-104">いる一部の回復方法が不可能なデータ失われること正しく使用されていないときに注意してください。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-104">Note that some of the recovery methods can cause unrecoverable data loss when not used properly.</span></span> <span data-ttu-id="f4a1a-105">バックアップまたは回復操作に参加するすべてのデータベースのコピーをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-105">It is recommend to take backups or copies of all databases that participate in recovery operations.</span></span> 
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="AttachShard">
      <MemberSignature Language="C#" Value="public void AttachShard (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void AttachShard(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.AttachShard(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation)" />
      <MemberSignature Language="VB.NET" Value="Public Sub AttachShard (location As ShardLocation)" />
      <MemberSignature Language="F#" Value="member this.AttachShard : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation -&gt; unit" Usage="recoveryManager.AttachShard location" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="location" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="f4a1a-106">アタッチされている、シャードの場所です。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-106">Location of the shard being attached.</span></span></param>
        <summary>
            <span data-ttu-id="f4a1a-107">シャードをシャードのマップ マネージャーにアタッチします。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-107">Attaches a shard to the shard map manager.</span></span> <span data-ttu-id="f4a1a-108">アタッチするシャード上でより新しいバージョンが見つかった場合、同じシャード マップのマッピングの以前のバージョンが自動的に更新されます。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-108">Earlier versions of mappings for the same shard map will automatically be updated if more recent versions are found on the shard to be attached.</span></span>
            <span data-ttu-id="f4a1a-109">シャードをアタッチした後<see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />手動を保証する不整合競合解決のチェックに呼び出す必要があります。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-109">After attaching a shard, <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" /> should be called to check for any inconsistencies that warrant manual conflict resolution.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="f4a1a-110">このメソッドが不可能なデータ損失を招くことに注意してください。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-110">Note that this method can cause unrecoverable data loss.</span></span> <span data-ttu-id="f4a1a-111">バックアップまたはデータベースのコピーを取得した、慎重に進みます. のみを確認してください。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-111">Make sure you have taken backups or copies of your databases and only then proceed with great care.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AttachShard">
      <MemberSignature Language="C#" Value="public void AttachShard (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location, string shardMapName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void AttachShard(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location, string shardMapName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.AttachShard(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub AttachShard (location As ShardLocation, shardMapName As String)" />
      <MemberSignature Language="F#" Value="member this.AttachShard : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation * string -&gt; unit" Usage="recoveryManager.AttachShard (location, shardMapName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Maintainability", "CA1502:AvoidExcessiveComplexity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="location" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" />
        <Parameter Name="shardMapName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="f4a1a-112">アタッチされている、シャードの場所です。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-112">Location of the shard being attached.</span></span></param>
        <param name="shardMapName"><span data-ttu-id="f4a1a-113">シャード マップ名でフィルター処理する省略可能です。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-113">Optional string to filter on the shard map name.</span></span></param>
        <summary>
            <span data-ttu-id="f4a1a-114">シャードをシャードのマップ マネージャーにアタッチします。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-114">Attaches a shard to the shard map manager.</span></span> <span data-ttu-id="f4a1a-115">アタッチするシャード上でより新しいバージョンが見つかった場合、同じシャード マップのマッピングの以前のバージョンが自動的に更新されます。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-115">Earlier versions of mappings for the same shard map will automatically be updated if more recent versions are found on the shard to be attached.</span></span>
            <span data-ttu-id="f4a1a-116">シャードの場所は、この操作の一部としてローカル ストアの最新バージョンにアップグレードされます。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-116">Shard location will be upgraded to latest version of local store as part of this operation.</span></span>
            <span data-ttu-id="f4a1a-117">シャードをアタッチした後<see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />手動を保証する不整合競合解決のチェックに呼び出す必要があります。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-117">After attaching a shard, <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" /> should be called to check for any inconsistencies that warrant manual conflict resolution.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="f4a1a-118">このメソッドが不可能なデータ損失を招くことに注意してください。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-118">Note that this method can cause unrecoverable data loss.</span></span> <span data-ttu-id="f4a1a-119">バックアップまたはデータベースのコピーを取得した、慎重に進みます. のみを確認してください。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-119">Make sure you have taken backups or copies of your databases and only then proceed with great care.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DetachShard">
      <MemberSignature Language="C#" Value="public void DetachShard (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DetachShard(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetachShard(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DetachShard (location As ShardLocation)" />
      <MemberSignature Language="F#" Value="member this.DetachShard : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation -&gt; unit" Usage="recoveryManager.DetachShard location" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="location" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="f4a1a-120">デタッチするシャードの場所です。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-120">Location of the shard being detached.</span></span></param>
        <summary>
            <span data-ttu-id="f4a1a-121">シャードのマップ マネージャーから特定のシャードをデタッチします。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-121">Detaches the given shard from the shard map manager.</span></span> <span data-ttu-id="f4a1a-122">マッピングを削除するシャードを指すは、このメソッドによって自動的に削除されます。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-122">Mappings pointing to the shard to be deleted will automatically be removed by this method.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="f4a1a-123">このメソッドが不可能なデータ損失を招くことに注意してください。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-123">Note that this method can cause unrecoverable data loss.</span></span> <span data-ttu-id="f4a1a-124">バックアップまたはデータベースのコピーを取得した、慎重に進みます. のみを確認してください。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-124">Make sure you have taken backups or copies of your databases and only then proceed with great care.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DetachShard">
      <MemberSignature Language="C#" Value="public void DetachShard (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location, string shardMapName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DetachShard(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location, string shardMapName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetachShard(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DetachShard (location As ShardLocation, shardMapName As String)" />
      <MemberSignature Language="F#" Value="member this.DetachShard : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation * string -&gt; unit" Usage="recoveryManager.DetachShard (location, shardMapName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="location" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" />
        <Parameter Name="shardMapName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="f4a1a-125">デタッチするシャードの場所です。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-125">Location of the shard being detached.</span></span></param>
        <param name="shardMapName"><span data-ttu-id="f4a1a-126">シャード マップ名でフィルター処理する省略可能です。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-126">Optional string to filter on shard map name.</span></span></param>
        <summary>
            <span data-ttu-id="f4a1a-127">シャードのマップ マネージャーから特定のシャードをデタッチします。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-127">Detaches the given shard from the shard map manager.</span></span> <span data-ttu-id="f4a1a-128">マッピングを削除するシャードを指すは、このメソッドによって自動的に削除されます。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-128">Mappings pointing to the shard to be deleted will automatically be removed by this method.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="f4a1a-129">このメソッドが不可能なデータ損失を招くことに注意してください。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-129">Note that this method can cause unrecoverable data loss.</span></span> <span data-ttu-id="f4a1a-130">バックアップまたはデータベースのコピーを取得した、慎重に進みます. のみを確認してください。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-130">Make sure you have taken backups or copies of your databases and only then proceed with great care.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DetectMappingDifferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken&gt; DetectMappingDifferences (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken&gt; DetectMappingDifferences(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation)" />
      <MemberSignature Language="VB.NET" Value="Public Function DetectMappingDifferences (location As ShardLocation) As IEnumerable(Of RecoveryToken)" />
      <MemberSignature Language="F#" Value="member this.DetectMappingDifferences : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation -&gt; seq&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken&gt;" Usage="recoveryManager.DetectMappingDifferences location" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="location" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="f4a1a-131">不整合が検出する対象のシャードの場所です。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-131">Location of shard for which to detect inconsistencies.</span></span></param>
        <summary>
            <span data-ttu-id="f4a1a-132">シャードを指定した場所にグローバル シャードのマップ manager データベースとシャードのローカルのデータベースのマッピングでの違いを列挙します。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-132">Enumerates differences in the mappings between the global shard map manager database and the local shard database in the specified shard location.</span></span>
            </summary>
        <returns><span data-ttu-id="f4a1a-133">さらに解決タスクに使用されるトークンのコレクション (を参照してください<see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.ResolveMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution)" />)。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-133">Collection of tokens to be used for further resolution tasks (see <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.ResolveMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution)" />).</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DetectMappingDifferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken&gt; DetectMappingDifferences (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location, string shardMapName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken&gt; DetectMappingDifferences(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location, string shardMapName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DetectMappingDifferences (location As ShardLocation, shardMapName As String) As IEnumerable(Of RecoveryToken)" />
      <MemberSignature Language="F#" Value="member this.DetectMappingDifferences : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation * string -&gt; seq&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken&gt;" Usage="recoveryManager.DetectMappingDifferences (location, shardMapName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Maintainability", "CA1506:AvoidExcessiveClassCoupling")</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Maintainability", "CA1502:AvoidExcessiveComplexity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="location" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" />
        <Parameter Name="shardMapName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="f4a1a-134">不整合が検出する対象のシャードの場所です。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-134">Location of shard for which to detect inconsistencies.</span></span></param>
        <param name="shardMapName"><span data-ttu-id="f4a1a-135">特定のシャード マップを指定する省略可能なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-135">Optional parameter to specify a particular shard map.</span></span></param>
        <summary>
            <span data-ttu-id="f4a1a-136">シャードを指定した場所にグローバル シャードのマップ manager データベースとシャードのローカルのデータベースのマッピングでの違いを列挙します。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-136">Enumerates differences in the mappings between the global shard map manager database and the local shard database in the specified shard location.</span></span>
            </summary>
        <returns><span data-ttu-id="f4a1a-137">さらに解決タスクに使用されるトークンのコレクション (を参照してください<see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.ResolveMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution)" />)。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-137">Collection of tokens to be used for further resolution tasks (see <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.ResolveMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution)" />).</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMappingDifferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingLocation&gt; GetMappingDifferences (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IDictionary`2&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange, valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingLocation&gt; GetMappingDifferences(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.GetMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMappingDifferences (token As RecoveryToken) As IDictionary(Of ShardRange, MappingLocation)" />
      <MemberSignature Language="F#" Value="member this.GetMappingDifferences : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken -&gt; System.Collections.Generic.IDictionary&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingLocation&gt;" Usage="recoveryManager.GetMappingDifferences token" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingLocation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken" />
      </Parameters>
      <Docs>
        <param name="token"><span data-ttu-id="f4a1a-138">返された回復トークン<see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />です。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-138">Recovery token returned from <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />.</span></span></param>
        <summary>
            <span data-ttu-id="f4a1a-139">範囲-場所キー/値ペアのディクショナリを返します。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-139">Returns a dictionary of range-to-location key-value pairs.</span></span> <span data-ttu-id="f4a1a-140">返される場所は、特定の範囲 (またはポイント) がのみローカル シャードのマップだけでは、グローバル シャード マップ、またはその両方に存在するかどうかを示す、列挙子です。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-140">The location returned is an enumerator stating whether a given range (or point) is present only in the local shard map, only in the global shard map, or both.</span></span> <span data-ttu-id="f4a1a-141">範囲のいずれかのシャードのマップに含まれていないは、これらの範囲が表示されないようにの相違点を含めることはできません。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-141">Ranges not contained in either shard map cannot contain differences so those ranges are not shown.</span></span>
            </summary>
        <returns><span data-ttu-id="f4a1a-142">範囲のセットとそれに対応する<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingLocation" />です。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-142">The set of ranges and their corresponding <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingLocation" />.</span></span></returns>
        <remarks>
            <span data-ttu-id="f4a1a-143">この方法では、前の呼び出しに<see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />回復トークン パラメーターを提供します。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-143">This method assumes a previous call to <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" /> that provides the recovery token parameter.</span></span>
            <span data-ttu-id="f4a1a-144">などの不整合を解決するのには後続の呼び出しでこのメソッドの結果が通常使用される<see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.ResolveMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution)" />または<see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.RebuildMappingsOnShard(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken,System.Collections.Generic.IEnumerable{Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange})" />です。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-144">The result of this method is typically used in subsequent calls to resolve inconsistencies such as <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.ResolveMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution)" /> or <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.RebuildMappingsOnShard(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken,System.Collections.Generic.IEnumerable{Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange})" />.</span></span> 
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetShardInfo">
      <MemberSignature Language="C#" Value="public void GetShardInfo (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token, out Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapType mapType, out string shardMapName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void GetShardInfo(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token, [out] valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapType&amp; mapType, [out] string&amp; shardMapName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.GetShardInfo(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapType@,System.String@)" />
      <MemberSignature Language="VB.NET" Value="Public Sub GetShardInfo (token As RecoveryToken, ByRef mapType As ShardMapType, ByRef shardMapName As String)" />
      <MemberSignature Language="F#" Value="member this.GetShardInfo : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken *  *  -&gt; unit" Usage="recoveryManager.GetShardInfo (token, mapType, shardMapName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1021:AvoidOutParameters", MessageId="1#")</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1021:AvoidOutParameters", MessageId="2#")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken" />
        <Parameter Name="mapType" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapType&amp;" RefType="out" />
        <Parameter Name="shardMapName" Type="System.String&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="token"><span data-ttu-id="f4a1a-145">返された回復トークン<see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />です。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-145">Recovery token returned from <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />.</span></span></param>
        <param name="mapType"><span data-ttu-id="f4a1a-146">Shardmap 型 (範囲またはリスト) を出力します。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-146">Output Shardmap type (Range or List).</span></span></param>
        <param name="shardMapName"><span data-ttu-id="f4a1a-147">シャード マップの名前を出力します。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-147">Output name of shard map.</span></span></param>
        <summary>
            <span data-ttu-id="f4a1a-148">シャード マップの種類から返されたトークンに基づく名前を取得<see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />です。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-148">Retrieves shard map type and name based on the token returned from <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetShardInfo">
      <MemberSignature Language="C#" Value="public void GetShardInfo (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token, out Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapType mapType, out string shardMapName, out Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation shardLocation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void GetShardInfo(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token, [out] valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapType&amp; mapType, [out] string&amp; shardMapName, [out] class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&amp; shardLocation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.GetShardInfo(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapType@,System.String@,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation@)" />
      <MemberSignature Language="VB.NET" Value="Public Sub GetShardInfo (token As RecoveryToken, ByRef mapType As ShardMapType, ByRef shardMapName As String, ByRef shardLocation As ShardLocation)" />
      <MemberSignature Language="F#" Value="member this.GetShardInfo : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken *  *  *  -&gt; unit" Usage="recoveryManager.GetShardInfo (token, mapType, shardMapName, shardLocation)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1021:AvoidOutParameters", MessageId="3#")</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1021:AvoidOutParameters", MessageId="1#")</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1021:AvoidOutParameters", MessageId="2#")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken" />
        <Parameter Name="mapType" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapType&amp;" RefType="out" />
        <Parameter Name="shardMapName" Type="System.String&amp;" RefType="out" />
        <Parameter Name="shardLocation" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="token"><span data-ttu-id="f4a1a-149">返された回復トークン<see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />です。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-149">Recovery token returned from <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />.</span></span></param>
        <param name="mapType"><span data-ttu-id="f4a1a-150">出力のシャード マップの種類 (範囲またはリスト)。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-150">Outputs shard map type (Range or List).</span></span></param>
        <param name="shardMapName"><span data-ttu-id="f4a1a-151">シャード マップ名を出力します。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-151">Outputs shard map name.</span></span></param>
        <param name="shardLocation"><span data-ttu-id="f4a1a-152">出力のシャードの場所</span><span class="sxs-lookup"><span data-stu-id="f4a1a-152">Outputs shard location</span></span></param>
        <summary>
            <span data-ttu-id="f4a1a-153">シャード マップの種類、名前、およびシャードの場所を取得から返されたトークンに基づく<see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />です。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-153">Retrieves shard map type, name and shard location based on the token returned from <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetShardLocation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation GetShardLocation (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation GetShardLocation(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.GetShardLocation(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetShardLocation (token As RecoveryToken) As ShardLocation" />
      <MemberSignature Language="F#" Value="member this.GetShardLocation : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" Usage="recoveryManager.GetShardLocation token" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken" />
      </Parameters>
      <Docs>
        <param name="token"><span data-ttu-id="f4a1a-154">返されたトークンの回復<see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" /></span><span class="sxs-lookup"><span data-stu-id="f4a1a-154">Recovery token returned from <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" /></span></span></param>
        <summary>
            <span data-ttu-id="f4a1a-155">によって処理されるローカルのシャードのマップのシャードの場所を返します<see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />です。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-155">Returns the shard location of the local shard map processed by <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />.</span></span>
            </summary>
        <returns><span data-ttu-id="f4a1a-156">相違点の検出のマッピングのセットに対応するシャードの場所<see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />です。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-156">Location of the shard corresponding to the set of mapping differences detected in <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetShardMapName">
      <MemberSignature Language="C#" Value="public string GetShardMapName (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetShardMapName(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.GetShardMapName(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetShardMapName (token As RecoveryToken) As String" />
      <MemberSignature Language="F#" Value="member this.GetShardMapName : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken -&gt; string" Usage="recoveryManager.GetShardMapName token" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken" />
      </Parameters>
      <Docs>
        <param name="token"><span data-ttu-id="f4a1a-157">返された回復トークン<see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />です。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-157">Recovery token returned from <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />.</span></span></param>
        <summary>
            <span data-ttu-id="f4a1a-158">によって処理されたシャードのマップのシャード マップ名を返します<see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />です。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-158">Returns the shard map name of the shard map processed by <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />.</span></span>
            </summary>
        <returns><span data-ttu-id="f4a1a-159">指定した回復トークンのシャードのマップの名前。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-159">The name of the shard map for the given recovery token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetShardMapType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapType GetShardMapType (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapType GetShardMapType(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.GetShardMapType(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetShardMapType (token As RecoveryToken) As ShardMapType" />
      <MemberSignature Language="F#" Value="member this.GetShardMapType : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapType" Usage="recoveryManager.GetShardMapType token" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapType</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken" />
      </Parameters>
      <Docs>
        <param name="token"><span data-ttu-id="f4a1a-160">返された回復トークン<see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />です。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-160">Recovery token returned from <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />.</span></span></param>
        <summary>
            <span data-ttu-id="f4a1a-161">によって処理されたシャードのマップのシャード マップの種類を返します<see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />です。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-161">Returns the shard map type of the shard map processed by <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />.</span></span>
            </summary>
        <returns><span data-ttu-id="f4a1a-162">回復のトークンに対応するシャード マップ (リスト、範囲など) の型。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-162">The type of shard map (list, range, etc...) corresponding to the recovery token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RebuildMappingsOnShard">
      <MemberSignature Language="C#" Value="public void RebuildMappingsOnShard (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange&gt; ranges);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RebuildMappingsOnShard(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange&gt; ranges) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.RebuildMappingsOnShard(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken,System.Collections.Generic.IEnumerable{Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RebuildMappingsOnShard (token As RecoveryToken, ranges As IEnumerable(Of ShardRange))" />
      <MemberSignature Language="F#" Value="member this.RebuildMappingsOnShard : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken * seq&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange&gt; -&gt; unit" Usage="recoveryManager.RebuildMappingsOnShard (token, ranges)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", MessageId="1")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken" />
        <Parameter Name="ranges" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange&gt;" />
      </Parameters>
      <Docs>
        <param name="token"><span data-ttu-id="f4a1a-163">以前の呼び出しから回復トークン<see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />です。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-163">The recovery token from a previous call to <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />.</span></span></param>
        <param name="ranges"><span data-ttu-id="f4a1a-164">ローカル シャードのマップを再構築するときに、ローカルのシャードに保持する範囲のセット。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-164">The set of ranges to keep on the local shard when rebuilding the local shard map.</span></span></param>
        <summary>
             <span data-ttu-id="f4a1a-165">によって検出された一貫性のないシャードの範囲の一覧からローカル範囲シャード マップを再構築<see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />にアクセスして、<see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.GetMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-165">Rebuilds a local range shard map from a list of inconsistent shard ranges detected by <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" /> and then accessed by <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.GetMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken)" />.</span></span>
             <span data-ttu-id="f4a1a-166">結果として得られるローカル範囲シャード マップが常にまだされませんと一致するシャードのマップ manager データベース内のグローバル シャード マップします。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-166">The resulting local range shard map will always still be inconsistent with the global shard map in the shard map manager database.</span></span> <span data-ttu-id="f4a1a-167">後続の呼び出しに<see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.ResolveMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution)" />は正常な状態に戻す、システムを表示するために必要です。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-167">A subsequent call to <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.ResolveMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution)" /> is necessary to bring the system back to a healthy state.</span></span>
             </summary>
        <remarks>
             <span data-ttu-id="f4a1a-168">このメソッドが不可能なデータ損失を招くことに注意してください。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-168">Note that this method can cause unrecoverable data loss.</span></span> <span data-ttu-id="f4a1a-169">バックアップまたはデータベースのコピーを取得した、慎重に進みます. のみを確認してください。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-169">Make sure you have taken backups or copies of your databases and only then proceed with great care.</span></span>
             
            <span data-ttu-id="f4a1a-170">不整合をシャードの範囲内だけは、このメソッドを使用して再構築することができます。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-170">Only shard ranges with inconsistencies can be rebuilt using this method.</span></span> <span data-ttu-id="f4a1a-171">なしの不一致は、ローカルのシャードとグローバル シャードのマップをすべての範囲内では、ローカルのシャードに完全な状態で保持され、この呼び出しの影響は受けません。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-171">All ranges with no inconsistencies between the local shard and the global shard map will be kept intact on the local shard and are not affected by this call.</span></span>
             <span data-ttu-id="f4a1a-172">シャードのマップ マネージャーで正規のインターフェイスを使用して後で、競合しないマッピングを後続の変更ができます。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-172">Subsequent changes to the non-conflicting mappings can be made later using the regular interfaces in the shard map manager.</span></span> <span data-ttu-id="f4a1a-173">回復マネージャーを使用して、競合しないマッピングを変更する必要はありません。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-173">It is not necessary to use the recovery manager to change non-conflicting mappings.</span></span>
             </remarks>
      </Docs>
    </Member>
    <Member MemberName="RebuildMappingsOnShardMapManagerFromShards">
      <MemberSignature Language="C#" Value="public void RebuildMappingsOnShardMapManagerFromShards (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; shardLocations);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RebuildMappingsOnShardMapManagerFromShards(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; shardLocations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.RebuildMappingsOnShardMapManagerFromShards(System.Collections.Generic.IEnumerable{Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RebuildMappingsOnShardMapManagerFromShards (shardLocations As IEnumerable(Of ShardLocation))" />
      <MemberSignature Language="F#" Value="member this.RebuildMappingsOnShardMapManagerFromShards : seq&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; -&gt; unit" Usage="recoveryManager.RebuildMappingsOnShardMapManagerFromShards shardLocations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", MessageId="0")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="shardLocations" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt;" />
      </Parameters>
      <Docs>
        <param name="shardLocations"><span data-ttu-id="f4a1a-174">シャードの場所のコレクション。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-174">Collection of shard locations.</span></span></param>
        <summary>
            <span data-ttu-id="f4a1a-175">指定した場所のシャードのコレクション、個々 のシャードに格納されているマッピング情報に基づいてシャードのマップ マネージャーを再構築します。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-175">Given a collection of shard locations, reconstructs the shard map manager based on mapping information stored in the individual shards.</span></span> <span data-ttu-id="f4a1a-176">指定されたシャードは、グローバルのシャードのマップに既に登録する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-176">The specified shards need to be registered already in the global shard map.</span></span> <span data-ttu-id="f4a1a-177">このメソッドには、マッピングだけ再構築します。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-177">This method only rebuilds mappings.</span></span> <span data-ttu-id="f4a1a-178">グローバルのシャードのマップ内のメンバーシップのシャードを再構築にはできません。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-178">It does not rebuild shard membership within the global shard map.</span></span>
            <span data-ttu-id="f4a1a-179">個々 のシャード マップの情報は、不整合が発生した場合、動作は定義されません。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-179">If the information in the individual shard maps is or becomes inconsistent, the behavior is undefined.</span></span>
            <span data-ttu-id="f4a1a-180">クロス シャード ロックは行われませんため、シャードは、このメソッドの実行中に不整合になると、グローバル シャードのマップの最終的な状態は破損している可能性があります。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-180">No cross shard locks are taken, so if any shards become inconsistent during the execution of this method, the final state of the global shard map may be corrupt.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="f4a1a-181">このメソッドが不可能なデータ損失を招くことに注意してください。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-181">Note that this method can cause unrecoverable data loss.</span></span> <span data-ttu-id="f4a1a-182">バックアップまたはデータベースのコピーを取得した、慎重に進みます. のみを確認してください。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-182">Make sure you have taken backups or copies of your databases and only then proceed with great care.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RebuildMappingsOnShardMapManagerFromShards">
      <MemberSignature Language="C#" Value="public void RebuildMappingsOnShardMapManagerFromShards (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; shardLocations, string shardMapName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RebuildMappingsOnShardMapManagerFromShards(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; shardLocations, string shardMapName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.RebuildMappingsOnShardMapManagerFromShards(System.Collections.Generic.IEnumerable{Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RebuildMappingsOnShardMapManagerFromShards (shardLocations As IEnumerable(Of ShardLocation), shardMapName As String)" />
      <MemberSignature Language="F#" Value="member this.RebuildMappingsOnShardMapManagerFromShards : seq&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; * string -&gt; unit" Usage="recoveryManager.RebuildMappingsOnShardMapManagerFromShards (shardLocations, shardMapName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", MessageId="0")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="shardLocations" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt;" />
        <Parameter Name="shardMapName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="shardLocations"><span data-ttu-id="f4a1a-183">シャードの場所のコレクション。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-183">Collection of shard locations.</span></span></param>
        <param name="shardMapName"><span data-ttu-id="f4a1a-184">シャード マップのオプションの名前。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-184">Optional name of shard map.</span></span> <span data-ttu-id="f4a1a-185">省略した場合は、各シャードにあるすべてのシャード マップからの回復を試みます。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-185">If omitted, will attempt to recover from all shard maps present on each shard.</span></span></param>
        <summary>
            <span data-ttu-id="f4a1a-186">指定した場所のシャードのコレクション、個々 のシャードに格納されているマッピング情報に基づいてシャードのマップ マネージャーを再構築します。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-186">Given a collection of shard locations, reconstructs the shard map manager based on mapping information stored in the individual shards.</span></span> <span data-ttu-id="f4a1a-187">指定されたシャードは、グローバルのシャードのマップに既に登録する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-187">The specified shards need to be registered already in the global shard map.</span></span> <span data-ttu-id="f4a1a-188">このメソッドには、マッピングだけ再構築します。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-188">This method only rebuilds mappings.</span></span> <span data-ttu-id="f4a1a-189">グローバルのシャードのマップ内のメンバーシップのシャードを再構築にはできません。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-189">It does not rebuild shard membership within the global shard map.</span></span>
            <span data-ttu-id="f4a1a-190">個々 のシャード マップの情報は、不整合が発生した場合、動作は定義されません。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-190">If the information in the individual shard maps is or becomes inconsistent, the behavior is undefined.</span></span>
            <span data-ttu-id="f4a1a-191">クロス シャード ロックは行われませんため、シャードは、このメソッドの実行中に不整合になると、グローバル シャードのマップの最終的な状態は破損している可能性があります。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-191">No cross shard locks are taken, so if any shards become inconsistent during the execution of this method, the final state of the global shard map may be corrupt.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="f4a1a-192">このメソッドが不可能なデータ損失を招くことに注意してください。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-192">Note that this method can cause unrecoverable data loss.</span></span> <span data-ttu-id="f4a1a-193">バックアップまたはデータベースのコピーを取得した、慎重に進みます. のみを確認してください。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-193">Make sure you have taken backups or copies of your databases and only then proceed with great care.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RebuildMappingsOnShardsFromShardMapManager">
      <MemberSignature Language="C#" Value="public void RebuildMappingsOnShardsFromShardMapManager (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; shardLocations);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RebuildMappingsOnShardsFromShardMapManager(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; shardLocations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.RebuildMappingsOnShardsFromShardMapManager(System.Collections.Generic.IEnumerable{Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RebuildMappingsOnShardsFromShardMapManager (shardLocations As IEnumerable(Of ShardLocation))" />
      <MemberSignature Language="F#" Value="member this.RebuildMappingsOnShardsFromShardMapManager : seq&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; -&gt; unit" Usage="recoveryManager.RebuildMappingsOnShardsFromShardMapManager shardLocations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", MessageId="0")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="shardLocations" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt;" />
      </Parameters>
      <Docs>
        <param name="shardLocations"><span data-ttu-id="f4a1a-194">シャードの場所のコレクション。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-194">Collection of shard locations.</span></span></param>
        <summary>
            <span data-ttu-id="f4a1a-195">シャードの場所のコレクションを指定するには、ローカルのシャードのマップを再構築は、グローバルのシャードのマップに格納されているマッピング情報に基づいています。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-195">Given a collection of shard locations, reconstructs local shard maps based on the mapping information stored in the global shard map.</span></span> <span data-ttu-id="f4a1a-196">指定されたシャードは、グローバルのシャードのマップに既に登録する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-196">The specified shards need to be registered already in the global shard map.</span></span> <span data-ttu-id="f4a1a-197">このメソッドには、マッピングだけ再構築します。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-197">This method only rebuilds mappings.</span></span> <span data-ttu-id="f4a1a-198">グローバルのシャードのマップ内のメンバーシップのシャードを再構築にはできません。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-198">It does not rebuild shard membership within the global shard map.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="f4a1a-199">このメソッドが不可能なデータ損失を招くことに注意してください。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-199">Note that this method can cause unrecoverable data loss.</span></span> <span data-ttu-id="f4a1a-200">バックアップまたはデータベースのコピーを取得した、慎重に進みます. のみを確認してください。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-200">Make sure you have taken backups or copies of your databases and only then proceed with great care.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RebuildMappingsOnShardsFromShardMapManager">
      <MemberSignature Language="C#" Value="public void RebuildMappingsOnShardsFromShardMapManager (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; shardLocations, string shardMapName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RebuildMappingsOnShardsFromShardMapManager(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; shardLocations, string shardMapName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.RebuildMappingsOnShardsFromShardMapManager(System.Collections.Generic.IEnumerable{Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RebuildMappingsOnShardsFromShardMapManager (shardLocations As IEnumerable(Of ShardLocation), shardMapName As String)" />
      <MemberSignature Language="F#" Value="member this.RebuildMappingsOnShardsFromShardMapManager : seq&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; * string -&gt; unit" Usage="recoveryManager.RebuildMappingsOnShardsFromShardMapManager (shardLocations, shardMapName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", MessageId="0")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="shardLocations" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt;" />
        <Parameter Name="shardMapName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="shardLocations"><span data-ttu-id="f4a1a-201">シャードの場所のコレクション。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-201">Collection of shard locations.</span></span></param>
        <param name="shardMapName"><span data-ttu-id="f4a1a-202">シャード マップ名でフィルター処理する省略可能なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-202">Optional parameter to filter by shard map name.</span></span> <span data-ttu-id="f4a1a-203">省略した場合、すべてのシャード マップが再構築されます。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-203">If omitted, all shard maps will be rebuilt.</span></span></param>
        <summary>
            <span data-ttu-id="f4a1a-204">シャードの場所のコレクションを指定するには、ローカルのシャードのマップを再構築は、グローバルのシャードのマップに格納されているマッピング情報に基づいています。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-204">Given a collection of shard locations, reconstructs local shard maps based on the mapping information stored in the global shard map.</span></span> <span data-ttu-id="f4a1a-205">指定されたシャードは、グローバルのシャードのマップに既に登録する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-205">The specified shards need to be registered already in the global shard map.</span></span> <span data-ttu-id="f4a1a-206">このメソッドには、マッピングだけ再構築します。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-206">This method only rebuilds mappings.</span></span> <span data-ttu-id="f4a1a-207">グローバルのシャードのマップ内のメンバーシップのシャードを再構築にはできません。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-207">It does not rebuild shard membership within the global shard map.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="f4a1a-208">このメソッドが不可能なデータ損失を招くことに注意してください。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-208">Note that this method can cause unrecoverable data loss.</span></span> <span data-ttu-id="f4a1a-209">バックアップまたはデータベースのコピーを取得した、慎重に進みます. のみを確認してください。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-209">Make sure you have taken backups or copies of your databases and only then proceed with great care.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResolveMappingDifferences">
      <MemberSignature Language="C#" Value="public void ResolveMappingDifferences (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution resolution);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void ResolveMappingDifferences(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token, valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution resolution) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.ResolveMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ResolveMappingDifferences (token As RecoveryToken, resolution As MappingDifferenceResolution)" />
      <MemberSignature Language="F#" Value="member this.ResolveMappingDifferences : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution -&gt; unit" Usage="recoveryManager.ResolveMappingDifferences (token, resolution)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken" />
        <Parameter Name="resolution" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution" />
      </Parameters>
      <Docs>
        <param name="token"><span data-ttu-id="f4a1a-210">返された回復トークン<see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />です。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-210">Recovery token returned from <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />.</span></span></param>
        <param name="resolution"><span data-ttu-id="f4a1a-211">解決に使用する解決方法です。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-211">The resolution strategy to be used for resolution.</span></span></param>
        <summary>
            <span data-ttu-id="f4a1a-212">情報源として、シャード マップ (ローカルまたはグローバルのいずれか) のいずれかを選択し、両方の同期のシャード マップ上のマッピングを表示します。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-212">Selects one of the shard maps (either local or global) as a source of truth and brings mappings on both shard maps in sync.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="f4a1a-213">このメソッドが不可能なデータ損失を招くことに注意してください。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-213">Note that this method can cause unrecoverable data loss.</span></span> <span data-ttu-id="f4a1a-214">バックアップまたはデータベースのコピーを取得した、慎重に進みます. のみを確認してください。</span><span class="sxs-lookup"><span data-stu-id="f4a1a-214">Make sure you have taken backups or copies of your databases and only then proceed with great care.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>