<Type Name="ConsistencyLevel" FullName="Microsoft.Azure.CosmosDB.ConsistencyLevel">
  <TypeSignature Language="C#" Value="public enum ConsistencyLevel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ConsistencyLevel extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.CosmosDB.ConsistencyLevel" />
  <TypeSignature Language="VB.NET" Value="Public Enum ConsistencyLevel" />
  <TypeSignature Language="F#" Value="type ConsistencyLevel = " />
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
            <span data-ttu-id="52366-101">これらは、Azure Cosmos DB サービスによってサポートされる一貫性レベルです。</span><span class="sxs-lookup"><span data-stu-id="52366-101">These are the consistency levels supported by the Azure Cosmos DB service.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="52366-102">要求の一貫性レベルは、一致か、データベース アカウントのプロビジョニングよりも弱くなりますする必要があります。</span><span class="sxs-lookup"><span data-stu-id="52366-102">The requested Consistency Level must match or be weaker than that provisioned for the database account.</span></span>
            <span data-ttu-id="52366-103">一貫性レベルの詳細についてを参照してください<see>http://azure.microsoft.com/documentation/articles/documentdb-consistency-levels/"</see>整合性レベルに関する記事です。</span><span class="sxs-lookup"><span data-stu-id="52366-103">For more information on consistency levels, please see <see>http://azure.microsoft.com/documentation/articles/documentdb-consistency-levels/"</see> Consistency Levels article.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="BoundedStaleness">
      <MemberSignature Language="C#" Value="BoundedStaleness" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.CosmosDB.ConsistencyLevel BoundedStaleness = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.CosmosDB.ConsistencyLevel.BoundedStaleness" />
      <MemberSignature Language="VB.NET" Value="BoundedStaleness" />
      <MemberSignature Language="F#" Value="BoundedStaleness = 1" Usage="Microsoft.Azure.CosmosDB.ConsistencyLevel.BoundedStaleness" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.ConsistencyLevel</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="52366-104">境界のある陳腐化では、読み取りがすぎる古くなっていないことを保証します。</span><span class="sxs-lookup"><span data-stu-id="52366-104">Bounded Staleness guarantees that reads are not too out-of-date.</span></span> <span data-ttu-id="52366-105">これは、操作 (MaxStalenessPrefix) または時刻 (MaxStalenessIntervalInSeconds) の数に基づいて構成できます。</span><span class="sxs-lookup"><span data-stu-id="52366-105">This can be configured based on number of operations (MaxStalenessPrefix) or time (MaxStalenessIntervalInSeconds).</span></span>  <span data-ttu-id="52366-106">MaxStalenessPrefix と MaxStalenessIntervalInSeconds の詳細についてを参照してください<see cref="T:Microsoft.Azure.Documents.ConsistencyPolicy" />です。</span><span class="sxs-lookup"><span data-stu-id="52366-106">For more information on MaxStalenessPrefix and MaxStalenessIntervalInSeconds, please see <see cref="T:Microsoft.Azure.Documents.ConsistencyPolicy" />.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="ConsistentPrefix">
      <MemberSignature Language="C#" Value="ConsistentPrefix" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.CosmosDB.ConsistencyLevel ConsistentPrefix = int32(4)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.CosmosDB.ConsistencyLevel.ConsistentPrefix" />
      <MemberSignature Language="VB.NET" Value="ConsistentPrefix" />
      <MemberSignature Language="F#" Value="ConsistentPrefix = 4" Usage="Microsoft.Azure.CosmosDB.ConsistencyLevel.ConsistentPrefix" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.ConsistencyLevel</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="52366-107">ConsistentPrefix 整合性では、読み取りのギャップのすべての書き込みのいくつかのプレフィックスが返されることを保証します。</span><span class="sxs-lookup"><span data-stu-id="52366-107">ConsistentPrefix Consistency guarantees that reads will return some prefix of all writes with no gaps.</span></span>
            <span data-ttu-id="52366-108">すべての書き込みはで最終的に使用できますの読み取り。</span><span class="sxs-lookup"><span data-stu-id="52366-108">All writes will be eventually be available for reads.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Eventual">
      <MemberSignature Language="C#" Value="Eventual" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.CosmosDB.ConsistencyLevel Eventual = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.CosmosDB.ConsistencyLevel.Eventual" />
      <MemberSignature Language="VB.NET" Value="Eventual" />
      <MemberSignature Language="F#" Value="Eventual = 3" Usage="Microsoft.Azure.CosmosDB.ConsistencyLevel.Eventual" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.ConsistencyLevel</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="52366-109">最終的整合性では、読み取りが書き込みのサブセットを返すことを保証します。</span><span class="sxs-lookup"><span data-stu-id="52366-109">Eventual Consistency guarantees that reads will return a subset of writes.</span></span> <span data-ttu-id="52366-110">すべての書き込みはで最終的に使用できますの読み取り。</span><span class="sxs-lookup"><span data-stu-id="52366-110">All writes will be eventually be available for reads.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Session">
      <MemberSignature Language="C#" Value="Session" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.CosmosDB.ConsistencyLevel Session = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.CosmosDB.ConsistencyLevel.Session" />
      <MemberSignature Language="VB.NET" Value="Session" />
      <MemberSignature Language="F#" Value="Session = 2" Usage="Microsoft.Azure.CosmosDB.ConsistencyLevel.Session" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.ConsistencyLevel</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="52366-111">セッションの整合性を保証単調読み取り (、古いデータの読み取りは行わないでください新しい、古い再度)、(書き込みが順序付け) 単調の書き込みと読み取りが単一セッションの中で、書き込み (、書き込みでは、読み取りをすぐに表示)。</span><span class="sxs-lookup"><span data-stu-id="52366-111">Session Consistency guarantees monotonic reads (you never read old data, then new, then old again), monotonic writes (writes are ordered) and read your writes (your writes are immediately visible to your reads) within any single session.</span></span> 
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Strong">
      <MemberSignature Language="C#" Value="Strong" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.CosmosDB.ConsistencyLevel Strong = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.CosmosDB.ConsistencyLevel.Strong" />
      <MemberSignature Language="VB.NET" Value="Strong" />
      <MemberSignature Language="F#" Value="Strong = 0" Usage="Microsoft.Azure.CosmosDB.ConsistencyLevel.Strong" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.ConsistencyLevel</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="52366-112">読み取り操作は常に強力な一貫性の保証は、最後に書き込まれた値を返します。</span><span class="sxs-lookup"><span data-stu-id="52366-112">Strong Consistency guarantees that read operations always return the value that was last written.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>