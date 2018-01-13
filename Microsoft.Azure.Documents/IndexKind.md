<Type Name="IndexKind" FullName="Microsoft.Azure.Documents.IndexKind">
  <TypeSignature Language="C#" Value="public enum IndexKind" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed IndexKind extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.IndexKind" />
  <TypeSignature Language="VB.NET" Value="Public Enum IndexKind" />
  <TypeSignature Language="F#" Value="type IndexKind = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            <span data-ttu-id="cf144-101">これらは、Azure Cosmos DB サービスのパスのインデックスを作成できるインデックスの種類です。</span><span class="sxs-lookup"><span data-stu-id="cf144-101">These are the indexing types available for indexing a path in the Azure Cosmos DB service.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="cf144-102">追加の詳細については、http://azure.microsoft.com/documentation/articles/documentdb-indexing-policies/#ConfigPolicy を参照してください。</span><span class="sxs-lookup"><span data-stu-id="cf144-102">For additional details, refer to http://azure.microsoft.com/documentation/articles/documentdb-indexing-policies/#ConfigPolicy.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="Hash">
      <MemberSignature Language="C#" Value="Hash" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Documents.IndexKind Hash = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Documents.IndexKind.Hash" />
      <MemberSignature Language="VB.NET" Value="Hash" />
      <MemberSignature Language="F#" Value="Hash = 0" Usage="Microsoft.Azure.Documents.IndexKind.Hash" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.IndexKind</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="cf144-103">インデックス エントリは、クエリを検索してポイントを使用するハッシュされます。</span><span class="sxs-lookup"><span data-stu-id="cf144-103">The index entries are hashed to serve point look up queries.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="cf144-104">ようにクエリを処理するために使用する: 選択 \* docs d WHERE d.prop から 5 を =</span><span class="sxs-lookup"><span data-stu-id="cf144-104">Can be used to serve queries like: SELECT \* FROM docs d WHERE d.prop = 5</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Range">
      <MemberSignature Language="C#" Value="Range" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Documents.IndexKind Range = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Documents.IndexKind.Range" />
      <MemberSignature Language="VB.NET" Value="Range" />
      <MemberSignature Language="F#" Value="Range = 1" Usage="Microsoft.Azure.Documents.IndexKind.Range" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.IndexKind</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="cf144-105">インデックス エントリが並べ替えられています。</span><span class="sxs-lookup"><span data-stu-id="cf144-105">The index entries are ordered.</span></span> <span data-ttu-id="cf144-106">範囲のインデックスは、非等値述語の効率的な範囲スキャン クエリに対して最適化されています。</span><span class="sxs-lookup"><span data-stu-id="cf144-106">Range indexes are optimized for inequality predicate queries with efficient range scans.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="cf144-107">ようにクエリを処理するために使用できます選択 \* docs d WHERE d.prop から&gt;5。</span><span class="sxs-lookup"><span data-stu-id="cf144-107">Can be used to serve queries like: SELECT \* FROM docs d WHERE d.prop &gt; 5</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Spatial">
      <MemberSignature Language="C#" Value="Spatial" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Documents.IndexKind Spatial = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Documents.IndexKind.Spatial" />
      <MemberSignature Language="VB.NET" Value="Spatial" />
      <MemberSignature Language="F#" Value="Spatial = 2" Usage="Microsoft.Azure.Documents.IndexKind.Spatial" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.IndexKind</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="cf144-108">インデックス エントリでは、インデックス空間クエリを提供します。</span><span class="sxs-lookup"><span data-stu-id="cf144-108">The index entries are indexed to serve spatial queries.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="cf144-109">ようにクエリを処理するために使用できます選択 \* FROM Root r ST_DISTANCE({"type":"Point","coordinates":[71.0589,42.3601]}, r.location) $LE 10000 場所。</span><span class="sxs-lookup"><span data-stu-id="cf144-109">Can be used to serve queries like: SELECT \* FROM Root r WHERE ST_DISTANCE({"type":"Point","coordinates":[71.0589,42.3601]}, r.location) $LE 10000</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>