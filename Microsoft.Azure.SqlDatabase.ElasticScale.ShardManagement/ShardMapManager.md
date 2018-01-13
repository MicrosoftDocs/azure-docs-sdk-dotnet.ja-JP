<Type Name="ShardMapManager" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager">
  <TypeSignature Language="C#" Value="public sealed class ShardMapManager" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ShardMapManager extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ShardMapManager" />
  <TypeSignature Language="F#" Value="type ShardMapManager = class" />
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
            <span data-ttu-id="bb83a-101">シャード マップを作成、管理、検索操作のエントリ ポイントとして機能します。</span><span class="sxs-lookup"><span data-stu-id="bb83a-101">Serves as the entry point for creation, management and lookup operations over shard maps.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateListShardMap&lt;TKey&gt;">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap&lt;TKey&gt; CreateListShardMap&lt;TKey&gt; (string shardMapName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1&lt;!!TKey&gt; CreateListShardMap&lt;TKey&gt;(string shardMapName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager.CreateListShardMap``1(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateListShardMap(Of TKey) (shardMapName As String) As ListShardMap(Of TKey)" />
      <MemberSignature Language="F#" Value="member this.CreateListShardMap : string -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap&lt;'Key&gt;" Usage="shardMapManager.CreateListShardMap shardMapName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap&lt;TKey&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TKey" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="shardMapName" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="TKey"><span data-ttu-id="bb83a-102">キーの型。</span><span class="sxs-lookup"><span data-stu-id="bb83a-102">Type of keys.</span></span></typeparam>
        <param name="shardMapName"><span data-ttu-id="bb83a-103">シャード マップの名前です。</span><span class="sxs-lookup"><span data-stu-id="bb83a-103">Name of shard map.</span></span></param>
        <summary>
            <span data-ttu-id="bb83a-104">基にリストを作成<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1" />です。</span><span class="sxs-lookup"><span data-stu-id="bb83a-104">Creates a list based <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1" />.</span></span>
            </summary>
        <returns><span data-ttu-id="bb83a-105">指定した名前には、シャードのマップをリストします。</span><span class="sxs-lookup"><span data-stu-id="bb83a-105">List shard map with the specified name.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateRangeShardMap&lt;TKey&gt;">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap&lt;TKey&gt; CreateRangeShardMap&lt;TKey&gt; (string shardMapName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap`1&lt;!!TKey&gt; CreateRangeShardMap&lt;TKey&gt;(string shardMapName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager.CreateRangeShardMap``1(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateRangeShardMap(Of TKey) (shardMapName As String) As RangeShardMap(Of TKey)" />
      <MemberSignature Language="F#" Value="member this.CreateRangeShardMap : string -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap&lt;'Key&gt;" Usage="shardMapManager.CreateRangeShardMap shardMapName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap&lt;TKey&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TKey" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="shardMapName" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="TKey"><span data-ttu-id="bb83a-106">キーの型。</span><span class="sxs-lookup"><span data-stu-id="bb83a-106">Type of keys.</span></span></typeparam>
        <param name="shardMapName"><span data-ttu-id="bb83a-107">シャード マップの名前です。</span><span class="sxs-lookup"><span data-stu-id="bb83a-107">Name of shard map.</span></span></param>
        <summary>
            <span data-ttu-id="bb83a-108">作成、範囲に基づく<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap`1" />です。</span><span class="sxs-lookup"><span data-stu-id="bb83a-108">Create a range based <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap`1" />.</span></span>
            </summary>
        <returns><span data-ttu-id="bb83a-109">指定した名前のシャードのマップの範囲です。</span><span class="sxs-lookup"><span data-stu-id="bb83a-109">Range shard map with the specified name.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteShardMap">
      <MemberSignature Language="C#" Value="public void DeleteShardMap (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap shardMap);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteShardMap(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap shardMap) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager.DeleteShardMap(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap)" />
      <MemberSignature Language="F#" Value="member this.DeleteShardMap : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap -&gt; unit" Usage="shardMapManager.DeleteShardMap shardMap" />
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
        <Parameter Name="shardMap" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap" />
      </Parameters>
      <Docs>
        <param name="shardMap"><span data-ttu-id="bb83a-110">削除する Shardmap です。</span><span class="sxs-lookup"><span data-stu-id="bb83a-110">Shardmap to be removed.</span></span></param>
        <summary>
            <span data-ttu-id="bb83a-111">指定されたシャードのマップを削除します。</span><span class="sxs-lookup"><span data-stu-id="bb83a-111">Removes the specified shard map.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDistinctShardLocations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; GetDistinctShardLocations ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; GetDistinctShardLocations() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager.GetDistinctShardLocations" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDistinctShardLocations () As IEnumerable(Of ShardLocation)" />
      <MemberSignature Language="F#" Value="member this.GetDistinctShardLocations : unit -&gt; seq&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt;" Usage="shardMapManager.GetDistinctShardLocations " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1024:UsePropertiesWhereAppropriate", Justification="Method is appropriate here because we're not just returning object state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="bb83a-112">シャードのマップ マネージャーから個別のシャードの場所を取得します。</span><span class="sxs-lookup"><span data-stu-id="bb83a-112">Obtains distinct shard locations from the shard map manager.</span></span>
            </summary>
        <returns><span data-ttu-id="bb83a-113">シャードのマップ マネージャーに関連付けられているシャード場所のコレクション。</span><span class="sxs-lookup"><span data-stu-id="bb83a-113">Collection of shard locations associated with the shard map manager.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetListShardMap&lt;TKey&gt;">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap&lt;TKey&gt; GetListShardMap&lt;TKey&gt; (string shardMapName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1&lt;!!TKey&gt; GetListShardMap&lt;TKey&gt;(string shardMapName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager.GetListShardMap``1(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetListShardMap(Of TKey) (shardMapName As String) As ListShardMap(Of TKey)" />
      <MemberSignature Language="F#" Value="member this.GetListShardMap : string -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap&lt;'Key&gt;" Usage="shardMapManager.GetListShardMap shardMapName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap&lt;TKey&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TKey" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="shardMapName" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="TKey"><span data-ttu-id="bb83a-114">キーの型。</span><span class="sxs-lookup"><span data-stu-id="bb83a-114">Key type.</span></span></typeparam>
        <param name="shardMapName"><span data-ttu-id="bb83a-115">シャード マップの名前です。</span><span class="sxs-lookup"><span data-stu-id="bb83a-115">Name of shard map.</span></span></param>
        <summary>
            <span data-ttu-id="bb83a-116">取得、<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1" />名を指定します。</span><span class="sxs-lookup"><span data-stu-id="bb83a-116">Obtains a <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1" /> given the name.</span></span> 
            </summary>
        <returns><span data-ttu-id="bb83a-117">結果として得られる ShardMap です。</span><span class="sxs-lookup"><span data-stu-id="bb83a-117">Resulting ShardMap.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRangeShardMap&lt;TKey&gt;">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap&lt;TKey&gt; GetRangeShardMap&lt;TKey&gt; (string shardMapName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap`1&lt;!!TKey&gt; GetRangeShardMap&lt;TKey&gt;(string shardMapName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager.GetRangeShardMap``1(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRangeShardMap(Of TKey) (shardMapName As String) As RangeShardMap(Of TKey)" />
      <MemberSignature Language="F#" Value="member this.GetRangeShardMap : string -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap&lt;'Key&gt;" Usage="shardMapManager.GetRangeShardMap shardMapName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap&lt;TKey&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TKey" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="shardMapName" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="TKey"><span data-ttu-id="bb83a-118">キーの型。</span><span class="sxs-lookup"><span data-stu-id="bb83a-118">Key type.</span></span></typeparam>
        <param name="shardMapName"><span data-ttu-id="bb83a-119">シャード マップの名前です。</span><span class="sxs-lookup"><span data-stu-id="bb83a-119">Name of shard map.</span></span></param>
        <summary>
            <span data-ttu-id="bb83a-120">取得、<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap`1" />名を指定します。</span><span class="sxs-lookup"><span data-stu-id="bb83a-120">Obtains a <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap`1" /> given the name.</span></span> 
            </summary>
        <returns><span data-ttu-id="bb83a-121">結果として得られる ShardMap です。</span><span class="sxs-lookup"><span data-stu-id="bb83a-121">Resulting ShardMap.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRecoveryManager">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager GetRecoveryManager ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager GetRecoveryManager() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager.GetRecoveryManager" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRecoveryManager () As RecoveryManager" />
      <MemberSignature Language="F#" Value="member this.GetRecoveryManager : unit -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager" Usage="shardMapManager.GetRecoveryManager " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1024:UsePropertiesWhereAppropriate", Justification="Method is appropriate here because we're not just returning object state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="bb83a-122">現在のシャードのマップ マネージャー インスタンスの回復マネージャーを取得します。</span><span class="sxs-lookup"><span data-stu-id="bb83a-122">Obtains the recovery manager for the current shard map manager instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="bb83a-123">シャードのマップ マネージャーの回復マネージャーです。</span><span class="sxs-lookup"><span data-stu-id="bb83a-123">Recovery manager for the shard map manager.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSchemaInfoCollection">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoCollection GetSchemaInfoCollection ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoCollection GetSchemaInfoCollection() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager.GetSchemaInfoCollection" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSchemaInfoCollection () As SchemaInfoCollection" />
      <MemberSignature Language="F#" Value="member this.GetSchemaInfoCollection : unit -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoCollection" Usage="shardMapManager.GetSchemaInfoCollection " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1024:UsePropertiesWhereAppropriate", Justification="Method is appropriate here because we're not just returning object state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoCollection</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="bb83a-124">シャード マップ マネージャーの現在のインスタンスのスキーマ情報のコレクション オブジェクトを取得します。</span><span class="sxs-lookup"><span data-stu-id="bb83a-124">Obtains the schema info collection object for the current shard map manager instance.</span></span>
            </summary>
        <returns><span data-ttu-id="bb83a-125">シャードのマップ manager のスキーマ情報のコレクションです。</span><span class="sxs-lookup"><span data-stu-id="bb83a-125">schema info collection for shard map manager.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetShardMap">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap GetShardMap (string shardMapName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap GetShardMap(string shardMapName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager.GetShardMap(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetShardMap (shardMapName As String) As ShardMap" />
      <MemberSignature Language="F#" Value="member this.GetShardMap : string -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap" Usage="shardMapManager.GetShardMap shardMapName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="shardMapName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="shardMapName"><span data-ttu-id="bb83a-126">シャード マップの名前です。</span><span class="sxs-lookup"><span data-stu-id="bb83a-126">Name of shard map.</span></span></param>
        <summary>
            <span data-ttu-id="bb83a-127">取得、<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap" />名を指定します。</span><span class="sxs-lookup"><span data-stu-id="bb83a-127">Obtains a <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap" /> given the name.</span></span>
            </summary>
        <returns><span data-ttu-id="bb83a-128">特定の名前を持つ Shardmap します。</span><span class="sxs-lookup"><span data-stu-id="bb83a-128">Shardmap with the specificed name.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetShardMaps">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap&gt; GetShardMaps ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap&gt; GetShardMaps() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager.GetShardMaps" />
      <MemberSignature Language="VB.NET" Value="Public Function GetShardMaps () As IEnumerable(Of ShardMap)" />
      <MemberSignature Language="F#" Value="member this.GetShardMaps : unit -&gt; seq&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap&gt;" Usage="shardMapManager.GetShardMaps " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1024:UsePropertiesWhereAppropriate", Justification="Method is appropriate here because we're not just returning object state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="bb83a-129">シャードのマップ マネージャーに関連付けられているすべてのシャード マップを取得します。</span><span class="sxs-lookup"><span data-stu-id="bb83a-129">Obtains all shard maps associated with the shard map manager.</span></span>
            </summary>
        <returns><span data-ttu-id="bb83a-130">シャードのマップ マネージャーに関連付けられたシャード マップのコレクションです。</span><span class="sxs-lookup"><span data-stu-id="bb83a-130">Collection of shard maps associated with the shard map manager.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGetListShardMap&lt;TKey&gt;">
      <MemberSignature Language="C#" Value="public bool TryGetListShardMap&lt;TKey&gt; (string shardMapName, out Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap&lt;TKey&gt; shardMap);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool TryGetListShardMap&lt;TKey&gt;(string shardMapName, [out] class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1&lt;!!TKey&gt;&amp; shardMap) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager.TryGetListShardMap``1(System.String,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap{``0}@)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryGetListShardMap(Of TKey) (shardMapName As String, ByRef shardMap As ListShardMap(Of TKey)) As Boolean" />
      <MemberSignature Language="F#" Value="member this.TryGetListShardMap : string *  -&gt; bool" Usage="shardMapManager.TryGetListShardMap (shardMapName, shardMap)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TKey" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="shardMapName" Type="System.String" />
        <Parameter Name="shardMap" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap&lt;TKey&gt;&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <typeparam name="TKey"><span data-ttu-id="bb83a-131">キーの型。</span><span class="sxs-lookup"><span data-stu-id="bb83a-131">Key type.</span></span></typeparam>
        <param name="shardMapName"><span data-ttu-id="bb83a-132">シャード マップの名前です。</span><span class="sxs-lookup"><span data-stu-id="bb83a-132">Name of shard map.</span></span></param>
        <param name="shardMap"><span data-ttu-id="bb83a-133">指定した名前のシャードのマップ。</span><span class="sxs-lookup"><span data-stu-id="bb83a-133">Shard map with the specified name.</span></span></param>
        <summary>
            <span data-ttu-id="bb83a-134">取得しようとする、<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1" />名を指定します。</span><span class="sxs-lookup"><span data-stu-id="bb83a-134">Tries to obtains a <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1" /> given the name.</span></span> 
            </summary>
        <returns>
          <span data-ttu-id="bb83a-135"><c>true</c>場合は、指定した名前のシャードのマップが見つかりましたが、 <c>false</c>それ以外の場合。</span><span class="sxs-lookup"><span data-stu-id="bb83a-135"><c>true</c> if shard map with the specified name was found, <c>false</c> otherwise.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGetRangeShardMap&lt;TKey&gt;">
      <MemberSignature Language="C#" Value="public bool TryGetRangeShardMap&lt;TKey&gt; (string shardMapName, out Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap&lt;TKey&gt; shardMap);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool TryGetRangeShardMap&lt;TKey&gt;(string shardMapName, [out] class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap`1&lt;!!TKey&gt;&amp; shardMap) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager.TryGetRangeShardMap``1(System.String,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap{``0}@)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryGetRangeShardMap(Of TKey) (shardMapName As String, ByRef shardMap As RangeShardMap(Of TKey)) As Boolean" />
      <MemberSignature Language="F#" Value="member this.TryGetRangeShardMap : string *  -&gt; bool" Usage="shardMapManager.TryGetRangeShardMap (shardMapName, shardMap)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TKey" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="shardMapName" Type="System.String" />
        <Parameter Name="shardMap" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap&lt;TKey&gt;&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <typeparam name="TKey"><span data-ttu-id="bb83a-136">キーの型。</span><span class="sxs-lookup"><span data-stu-id="bb83a-136">Key type.</span></span></typeparam>
        <param name="shardMapName"><span data-ttu-id="bb83a-137">シャード マップの名前です。</span><span class="sxs-lookup"><span data-stu-id="bb83a-137">Name of shard map.</span></span></param>
        <param name="shardMap"><span data-ttu-id="bb83a-138">指定した名前のシャードのマップ。</span><span class="sxs-lookup"><span data-stu-id="bb83a-138">Shard map with the specified name.</span></span></param>
        <summary>
            <span data-ttu-id="bb83a-139">取得しようとする、<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap`1" />名を指定します。</span><span class="sxs-lookup"><span data-stu-id="bb83a-139">Tries to obtains a <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap`1" /> given the name.</span></span> 
            </summary>
        <returns>
          <span data-ttu-id="bb83a-140"><c>true</c>場合は、指定した名前のシャードのマップが見つかりましたが、 <c>false</c>それ以外の場合。</span><span class="sxs-lookup"><span data-stu-id="bb83a-140"><c>true</c> if shard map with the specified name was found, <c>false</c> otherwise.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGetShardMap">
      <MemberSignature Language="C#" Value="public bool TryGetShardMap (string shardMapName, out Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap shardMap);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool TryGetShardMap(string shardMapName, [out] class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap&amp; shardMap) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager.TryGetShardMap(System.String,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap@)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryGetShardMap (shardMapName As String, ByRef shardMap As ShardMap) As Boolean" />
      <MemberSignature Language="F#" Value="member this.TryGetShardMap : string *  -&gt; bool" Usage="shardMapManager.TryGetShardMap (shardMapName, shardMap)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="shardMapName" Type="System.String" />
        <Parameter Name="shardMap" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="shardMapName"><span data-ttu-id="bb83a-141">シャード マップの名前です。</span><span class="sxs-lookup"><span data-stu-id="bb83a-141">Name of shard map.</span></span></param>
        <param name="shardMap"><span data-ttu-id="bb83a-142">指定した名前のシャードのマップ。</span><span class="sxs-lookup"><span data-stu-id="bb83a-142">Shard map with the specified name.</span></span></param>
        <summary>
            <span data-ttu-id="bb83a-143">取得しようとする、<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap" />名を指定します。</span><span class="sxs-lookup"><span data-stu-id="bb83a-143">Tries to obtains a <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap" /> given the name.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="bb83a-144"><c>true</c>場合は、指定した名前のシャードのマップが見つかりましたが、 <c>false</c>それ以外の場合。</span><span class="sxs-lookup"><span data-stu-id="bb83a-144"><c>true</c> if shard map with the specified name was found, <c>false</c> otherwise.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeGlobalStore">
      <MemberSignature Language="C#" Value="public void UpgradeGlobalStore ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void UpgradeGlobalStore() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager.UpgradeGlobalStore" />
      <MemberSignature Language="VB.NET" Value="Public Sub UpgradeGlobalStore ()" />
      <MemberSignature Language="F#" Value="member this.UpgradeGlobalStore : unit -&gt; unit" Usage="shardMapManager.UpgradeGlobalStore " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="bb83a-145">アップグレードでは、ライブラリでサポートされている最新バージョンにグローバル シャード マップのホストを格納します。</span><span class="sxs-lookup"><span data-stu-id="bb83a-145">Upgrades store hosting global shard map to the latest version supported by library.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeLocalStore">
      <MemberSignature Language="C#" Value="public void UpgradeLocalStore (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void UpgradeLocalStore(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager.UpgradeLocalStore(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation)" />
      <MemberSignature Language="VB.NET" Value="Public Sub UpgradeLocalStore (location As ShardLocation)" />
      <MemberSignature Language="F#" Value="member this.UpgradeLocalStore : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation -&gt; unit" Usage="shardMapManager.UpgradeLocalStore location" />
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
        <param name="location"><span data-ttu-id="bb83a-146">アップグレードするシャード場所です。</span><span class="sxs-lookup"><span data-stu-id="bb83a-146">Shard location to upgrade.</span></span></param>
        <summary>
            <span data-ttu-id="bb83a-147">アップグレードでは、ライブラリでサポートされている最新バージョンに場所を格納します。</span><span class="sxs-lookup"><span data-stu-id="bb83a-147">Upgrades store location to the latest version supported by library.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>