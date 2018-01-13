<Type Name="IndexingMode" FullName="Microsoft.Azure.CosmosDB.IndexingMode">
  <TypeSignature Language="C#" Value="public enum IndexingMode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed IndexingMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.CosmosDB.IndexingMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum IndexingMode" />
  <TypeSignature Language="F#" Value="type IndexingMode = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
    <AssemblyVersion>0.9.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary> 
            <span data-ttu-id="8ee4b-101">Cosmos DB の Azure サービスでサポートされているインデックス作成モードを指定します。</span><span class="sxs-lookup"><span data-stu-id="8ee4b-101">Specifies the supported indexing modes in the Azure Cosmos DB service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Consistent">
      <MemberSignature Language="C#" Value="Consistent" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.CosmosDB.IndexingMode Consistent = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.CosmosDB.IndexingMode.Consistent" />
      <MemberSignature Language="VB.NET" Value="Consistent" />
      <MemberSignature Language="F#" Value="Consistent = 0" Usage="Microsoft.Azure.CosmosDB.IndexingMode.Consistent" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.IndexingMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="8ee4b-102">インデックスは、作成、更新または削除操作で同期的に更新されます。</span><span class="sxs-lookup"><span data-stu-id="8ee4b-102">Index is updated synchronously with a create, update or delete operation.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="8ee4b-103">一貫性のあるインデックスを使用するクエリの整合性とは、データベース アカウントの既定の一貫性レベルと同じです。</span><span class="sxs-lookup"><span data-stu-id="8ee4b-103">With consistent indexing, query consistency is the same as the default consistency level for the database account.</span></span> <span data-ttu-id="8ee4b-104">インデックスのデータを最新状態保持は常にします。</span><span class="sxs-lookup"><span data-stu-id="8ee4b-104">The index is always kept up to date with the data.</span></span>
            
            <span data-ttu-id="8ee4b-105">既定値 IndexingMode は Consistent です。</span><span class="sxs-lookup"><span data-stu-id="8ee4b-105">The default IndexingMode is Consistent.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Lazy">
      <MemberSignature Language="C#" Value="Lazy" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.CosmosDB.IndexingMode Lazy = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.CosmosDB.IndexingMode.Lazy" />
      <MemberSignature Language="VB.NET" Value="Lazy" />
      <MemberSignature Language="F#" Value="Lazy = 1" Usage="Microsoft.Azure.CosmosDB.IndexingMode.Lazy" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.IndexingMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="8ee4b-106">インデックスが作成、更新または削除操作に関して非同期的に更新されます。</span><span class="sxs-lookup"><span data-stu-id="8ee4b-106">Index is updated asynchronously with respect to a create, update or delete operation.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="8ee4b-107">遅延インデックスを使用するクエリは、最終的に適合しています。</span><span class="sxs-lookup"><span data-stu-id="8ee4b-107">With lazy indexing, queries are eventually consistent.</span></span> <span data-ttu-id="8ee4b-108">全体のスループット容量 (1 秒あたりの要求単位) の下にコレクションが動作しているときに、インデックスが更新されます。</span><span class="sxs-lookup"><span data-stu-id="8ee4b-108">The index is updated when the collection is operating below full throughput capacity (Request units per second).</span></span> 
            
            <span data-ttu-id="8ee4b-109">書き込み操作は、書き込み時に以下の要求単位 (RequestCharge) を消費します。</span><span class="sxs-lookup"><span data-stu-id="8ee4b-109">Write operations will consume fewer request units (RequestCharge) at the time of write.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="None">
      <MemberSignature Language="C#" Value="None" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.CosmosDB.IndexingMode None = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.CosmosDB.IndexingMode.None" />
      <MemberSignature Language="VB.NET" Value="None" />
      <MemberSignature Language="F#" Value="None = 2" Usage="Microsoft.Azure.CosmosDB.IndexingMode.None" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.IndexingMode</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="8ee4b-110">インデックスが指定されていません。</span><span class="sxs-lookup"><span data-stu-id="8ee4b-110">No index is provided.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="8ee4b-111">IndexingMode を"None"に設定は、インデックスを削除します。</span><span class="sxs-lookup"><span data-stu-id="8ee4b-111">Setting IndexingMode to "None" drops the index.</span></span> <span data-ttu-id="8ee4b-112">ドキュメント コレクションは、記憶域のコストを節約または書き込みのスループットを向上させるインデックスを保持したくない場合は、これを使用します。</span><span class="sxs-lookup"><span data-stu-id="8ee4b-112">Use this if you don't want to maintain the index for a document collection, to save the storage cost or improve the write throughput.</span></span> <span data-ttu-id="8ee4b-113">クエリは、コレクション全体のスキャンを実行する逆されます。</span><span class="sxs-lookup"><span data-stu-id="8ee4b-113">Your queries will degenerate to scans of the entire collection.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>