<Type Name="IFeedResponse&lt;T&gt;" FullName="Microsoft.Azure.Documents.Client.IFeedResponse&lt;T&gt;">
  <TypeSignature Language="C#" Value="public interface IFeedResponse&lt;T&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IFeedResponse`1&lt;T&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Client.IFeedResponse`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IFeedResponse(Of T)" />
  <TypeSignature Language="F#" Value="type IFeedResponse&lt;'T&gt; = interface" />
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
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="T"><span data-ttu-id="62112-101">フィードの種類。</span><span class="sxs-lookup"><span data-stu-id="62112-101">The feed type.</span></span></typeparam>
    <summary>
            <span data-ttu-id="62112-102">Cosmos DB の Azure サービス内のフィード メソッド (列挙操作) に関連付けられている応答の Api をキャプチャします。</span><span class="sxs-lookup"><span data-stu-id="62112-102">Captures APIs for responses associated with feed methods (enumeration operations) in the Azure Cosmos DB service.</span></span>
            <span data-ttu-id="62112-103">目的のモックに公開されるインターフェイス。</span><span class="sxs-lookup"><span data-stu-id="62112-103">Interface exposed for mocking purposes.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ActivityId">
      <MemberSignature Language="C#" Value="public string ActivityId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ActivityId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IFeedResponse`1.ActivityId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActivityId As String" />
      <MemberSignature Language="F#" Value="member this.ActivityId : string" Usage="Microsoft.Azure.Documents.Client.IFeedResponse&lt;'T&gt;.ActivityId" />
      <MemberType>Property</MemberType>
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
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="62112-104">Azure Cosmos DB サービスの要求のアクティビティ ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="62112-104">Gets the activity ID for the request in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="62112-105">要求のアクティビティ ID。</span><span class="sxs-lookup"><span data-stu-id="62112-105">The activity ID for the request.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CollectionQuota">
      <MemberSignature Language="C#" Value="public long CollectionQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 CollectionQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IFeedResponse`1.CollectionQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CollectionQuota As Long" />
      <MemberSignature Language="F#" Value="member this.CollectionQuota : int64" Usage="Microsoft.Azure.Documents.Client.IFeedResponse&lt;'T&gt;.CollectionQuota" />
      <MemberType>Property</MemberType>
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
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="62112-106">Azure Cosmos DB データベース アカウント内のコレクション リソースの最大クォータを取得します。</span><span class="sxs-lookup"><span data-stu-id="62112-106">Gets the maximum quota for collection resources within the Azure Cosmos DB database account.</span></span>
            </summary>
        <value>
            <span data-ttu-id="62112-107">アカウントの最大クォータです。</span><span class="sxs-lookup"><span data-stu-id="62112-107">The maximum quota for the account.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CollectionSizeQuota">
      <MemberSignature Language="C#" Value="public long CollectionSizeQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 CollectionSizeQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IFeedResponse`1.CollectionSizeQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CollectionSizeQuota As Long" />
      <MemberSignature Language="F#" Value="member this.CollectionSizeQuota : int64" Usage="Microsoft.Azure.Documents.Client.IFeedResponse&lt;'T&gt;.CollectionSizeQuota" />
      <MemberType>Property</MemberType>
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
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="62112-108">キロバイト単位で Azure Cosmos DB データベースでのコレクションの最大サイズ。</span><span class="sxs-lookup"><span data-stu-id="62112-108">Maximum size of a collection in the Azure Cosmos DB database in kilobytes.</span></span>
            </summary>
        <value>
            <span data-ttu-id="62112-109">クォータ (キロバイト単位)。</span><span class="sxs-lookup"><span data-stu-id="62112-109">Quota in kilobytes.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CollectionSizeUsage">
      <MemberSignature Language="C#" Value="public long CollectionSizeUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 CollectionSizeUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IFeedResponse`1.CollectionSizeUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CollectionSizeUsage As Long" />
      <MemberSignature Language="F#" Value="member this.CollectionSizeUsage : int64" Usage="Microsoft.Azure.Documents.Client.IFeedResponse&lt;'T&gt;.CollectionSizeUsage" />
      <MemberType>Property</MemberType>
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
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="62112-110">キロバイト単位で Azure Cosmos DB データベースでのコレクションの現在のサイズ。</span><span class="sxs-lookup"><span data-stu-id="62112-110">Current size of a collection in the Azure Cosmos DB database in kilobytes.</span></span> 
            </summary>
        <value>
            <span data-ttu-id="62112-111">現在コレクション サイズ。</span><span class="sxs-lookup"><span data-stu-id="62112-111">Current collection size in kilobytes.</span></span>
            </value>
        <remarks>To be added.</remarks>
        <vallue>
            <span data-ttu-id="62112-112">現在コレクション サイズ。</span><span class="sxs-lookup"><span data-stu-id="62112-112">Current collection size in kilobytes.</span></span>
            </vallue>
      </Docs>
    </Member>
    <Member MemberName="CollectionUsage">
      <MemberSignature Language="C#" Value="public long CollectionUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 CollectionUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IFeedResponse`1.CollectionUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CollectionUsage As Long" />
      <MemberSignature Language="F#" Value="member this.CollectionUsage : int64" Usage="Microsoft.Azure.Documents.Client.IFeedResponse&lt;'T&gt;.CollectionUsage" />
      <MemberType>Property</MemberType>
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
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="62112-113">現在、Azure Cosmos DB データベース アカウント内でコレクションのリソースの数。</span><span class="sxs-lookup"><span data-stu-id="62112-113">The current number of collection resources within the Azure Cosmos DB database account.</span></span>
            </summary>
        <value>
            <span data-ttu-id="62112-114">コレクションの数。</span><span class="sxs-lookup"><span data-stu-id="62112-114">The number of collections.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentLocation">
      <MemberSignature Language="C#" Value="public string ContentLocation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IFeedResponse`1.ContentLocation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContentLocation As String" />
      <MemberSignature Language="F#" Value="member this.ContentLocation : string" Usage="Microsoft.Azure.Documents.Client.IFeedResponse&lt;'T&gt;.ContentLocation" />
      <MemberType>Property</MemberType>
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
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="62112-115">コンテンツの親の Azure Cosmos DB データベースの場所を db、foo、colls/バー</span><span class="sxs-lookup"><span data-stu-id="62112-115">The content parent location in the Azure Cosmos DB database, for example, dbs/foo/colls/bar</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public int Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IFeedResponse`1.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Integer" />
      <MemberSignature Language="F#" Value="member this.Count : int" Usage="Microsoft.Azure.Documents.Client.IFeedResponse&lt;'T&gt;.Count" />
      <MemberType>Property</MemberType>
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
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="62112-116">Azure Cosmos DB サービスのフィードの操作に関連付けられた応答で返される項目数を取得します。</span><span class="sxs-lookup"><span data-stu-id="62112-116">Gets the number of items returned in the response associated with the feed operations for the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="62112-117">応答内の項目の数。</span><span class="sxs-lookup"><span data-stu-id="62112-117">Count of items in the response.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentResourceQuotaUsage">
      <MemberSignature Language="C#" Value="public string CurrentResourceQuotaUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CurrentResourceQuotaUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IFeedResponse`1.CurrentResourceQuotaUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentResourceQuotaUsage As String" />
      <MemberSignature Language="F#" Value="member this.CurrentResourceQuotaUsage : string" Usage="Microsoft.Azure.Documents.Client.IFeedResponse&lt;'T&gt;.CurrentResourceQuotaUsage" />
      <MemberType>Property</MemberType>
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
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="62112-118">Cosmos DB の Azure サービスでは、このエンティティの現在のサイズを取得します。</span><span class="sxs-lookup"><span data-stu-id="62112-118">Gets the current size of this entity in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="62112-119">このエンティティの現在のサイズ。</span><span class="sxs-lookup"><span data-stu-id="62112-119">The current size for this entity.</span></span> <span data-ttu-id="62112-120">その他のリソースのカウント ドキュメント リソースをキロバイト単位で測定されます。</span><span class="sxs-lookup"><span data-stu-id="62112-120">Measured in kilobytes for document resources and in counts for other resources.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseQuota">
      <MemberSignature Language="C#" Value="public long DatabaseQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DatabaseQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IFeedResponse`1.DatabaseQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseQuota As Long" />
      <MemberSignature Language="F#" Value="member this.DatabaseQuota : int64" Usage="Microsoft.Azure.Documents.Client.IFeedResponse&lt;'T&gt;.DatabaseQuota" />
      <MemberType>Property</MemberType>
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
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="62112-121">Azure Cosmos DB データベース アカウント内のデータベース リソースの最大クォータを取得します。</span><span class="sxs-lookup"><span data-stu-id="62112-121">Gets the maximum quota for database resources within the Azure Cosmos DB database account.</span></span> 
            </summary>
        <value>
            <span data-ttu-id="62112-122">アカウントの最大クォータです。</span><span class="sxs-lookup"><span data-stu-id="62112-122">The maximum quota for the account.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseUsage">
      <MemberSignature Language="C#" Value="public long DatabaseUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DatabaseUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IFeedResponse`1.DatabaseUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseUsage As Long" />
      <MemberSignature Language="F#" Value="member this.DatabaseUsage : int64" Usage="Microsoft.Azure.Documents.Client.IFeedResponse&lt;'T&gt;.DatabaseUsage" />
      <MemberType>Property</MemberType>
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
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="62112-123">現在 Azure Cosmos DB データベース アカウント内のデータベース リソースの数。</span><span class="sxs-lookup"><span data-stu-id="62112-123">The current number of database resources within the Azure Cosmos DB database account.</span></span>
            </summary>
        <value>
            <span data-ttu-id="62112-124">データベースの数。</span><span class="sxs-lookup"><span data-stu-id="62112-124">The number of databases.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEnumerator">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;T&gt; GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerator`1&lt;!T&gt; GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.IFeedResponse`1.GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEnumerator () As IEnumerator(Of T)" />
      <MemberSignature Language="F#" Value="abstract member GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;'T&gt;" Usage="iFeedResponse.GetEnumerator " />
      <MemberType>Method</MemberType>
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
        <ReturnType>System.Collections.Generic.IEnumerator&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="62112-125">Azure Cosmos DB サービスのコレクションを反復処理する列挙子を返します。</span><span class="sxs-lookup"><span data-stu-id="62112-125">Returns an enumerator that iterates through a collection in the Azure Cosmos DB service.</span></span>
            </summary>
        <returns><span data-ttu-id="62112-126">コレクションを反復処理に使用できる IEnumerator オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="62112-126">An IEnumerator object that can be used to iterate through the collection.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxResourceQuota">
      <MemberSignature Language="C#" Value="public string MaxResourceQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MaxResourceQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IFeedResponse`1.MaxResourceQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxResourceQuota As String" />
      <MemberSignature Language="F#" Value="member this.MaxResourceQuota : string" Usage="Microsoft.Azure.Documents.Client.IFeedResponse&lt;'T&gt;.MaxResourceQuota" />
      <MemberType>Property</MemberType>
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
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="62112-127">このサービスのエンティティに Azure Cosmos DB のサイズの上限を取得します。</span><span class="sxs-lookup"><span data-stu-id="62112-127">Gets the maximum size limit for this entity in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="62112-128">このエンティティの最大サイズの制限。</span><span class="sxs-lookup"><span data-stu-id="62112-128">The maximum size limit for this entity.</span></span> <span data-ttu-id="62112-129">その他のリソースのカウント ドキュメント リソースをキロバイト単位で測定されます。</span><span class="sxs-lookup"><span data-stu-id="62112-129">Measured in kilobytes for document resources and in counts for other resources.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PermissionQuota">
      <MemberSignature Language="C#" Value="public long PermissionQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 PermissionQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IFeedResponse`1.PermissionQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PermissionQuota As Long" />
      <MemberSignature Language="F#" Value="member this.PermissionQuota : int64" Usage="Microsoft.Azure.Documents.Client.IFeedResponse&lt;'T&gt;.PermissionQuota" />
      <MemberType>Property</MemberType>
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
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="62112-130">Azure Cosmos DB データベース アカウント内のアクセス許可リソースの最大クォータを取得します。</span><span class="sxs-lookup"><span data-stu-id="62112-130">Gets the maximum quota for permission resources within the Azure Cosmos DB database account.</span></span>
            </summary>
        <value>
            <span data-ttu-id="62112-131">アカウントの最大クォータです。</span><span class="sxs-lookup"><span data-stu-id="62112-131">The maximum quota for the account.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PermissionUsage">
      <MemberSignature Language="C#" Value="public long PermissionUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 PermissionUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IFeedResponse`1.PermissionUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PermissionUsage As Long" />
      <MemberSignature Language="F#" Value="member this.PermissionUsage : int64" Usage="Microsoft.Azure.Documents.Client.IFeedResponse&lt;'T&gt;.PermissionUsage" />
      <MemberType>Property</MemberType>
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
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="62112-132">現在 Azure Cosmos DB データベース アカウント内のアクセス許可リソースの数。</span><span class="sxs-lookup"><span data-stu-id="62112-132">The current number of permission resources within the Azure Cosmos DB database account.</span></span> 
            </summary>
        <value>
            <span data-ttu-id="62112-133">アクセス許可の数。</span><span class="sxs-lookup"><span data-stu-id="62112-133">The number of permissions.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestCharge">
      <MemberSignature Language="C#" Value="public double RequestCharge { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 RequestCharge" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IFeedResponse`1.RequestCharge" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestCharge As Double" />
      <MemberSignature Language="F#" Value="member this.RequestCharge : double" Usage="Microsoft.Azure.Documents.Client.IFeedResponse&lt;'T&gt;.RequestCharge" />
      <MemberType>Property</MemberType>
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
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="62112-134">この要求に対して Azure Cosmos DB データベース アカウントの要求の料金を取得します。</span><span class="sxs-lookup"><span data-stu-id="62112-134">Gets the request charge for the Azure Cosmos DB database account for this request</span></span>
            </summary>
        <value>
            <span data-ttu-id="62112-135">要求の料金は、reqest 単位で測定されます。</span><span class="sxs-lookup"><span data-stu-id="62112-135">The request charge measured in reqest units.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResponseContinuation">
      <MemberSignature Language="C#" Value="public string ResponseContinuation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResponseContinuation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IFeedResponse`1.ResponseContinuation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResponseContinuation As String" />
      <MemberSignature Language="F#" Value="member this.ResponseContinuation : string" Usage="Microsoft.Azure.Documents.Client.IFeedResponse&lt;'T&gt;.ResponseContinuation" />
      <MemberType>Property</MemberType>
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
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="62112-136">Azure Cosmos DB サービスの列挙を継続するために使用する継続トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="62112-136">Gets the continuation token to be used for continuing enumeration in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="62112-137">列挙体を継続するために使用する継続トークンです。</span><span class="sxs-lookup"><span data-stu-id="62112-137">The continuation token to be used for continuing enumeration.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResponseHeaders">
      <MemberSignature Language="C#" Value="public System.Collections.Specialized.NameValueCollection ResponseHeaders { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Specialized.NameValueCollection ResponseHeaders" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IFeedResponse`1.ResponseHeaders" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResponseHeaders As NameValueCollection" />
      <MemberSignature Language="F#" Value="member this.ResponseHeaders : System.Collections.Specialized.NameValueCollection" Usage="Microsoft.Azure.Documents.Client.IFeedResponse&lt;'T&gt;.ResponseHeaders" />
      <MemberType>Property</MemberType>
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
        <ReturnType>System.Collections.Specialized.NameValueCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="62112-138">応答ヘッダーを取得します。</span><span class="sxs-lookup"><span data-stu-id="62112-138">Gets the response headers.</span></span>
            </summary>
        <value>
            <span data-ttu-id="62112-139">応答ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="62112-139">The response headers.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SessionToken">
      <MemberSignature Language="C#" Value="public string SessionToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SessionToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IFeedResponse`1.SessionToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SessionToken As String" />
      <MemberSignature Language="F#" Value="member this.SessionToken : string" Usage="Microsoft.Azure.Documents.Client.IFeedResponse&lt;'T&gt;.SessionToken" />
      <MemberType>Property</MemberType>
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
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="62112-140">Azure Cosmos DB サービスのセッションの整合性の読み取りに使用するため、セッション トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="62112-140">Gets the session token for use in sesssion consistency reads in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="62112-141">セッションで使用するためのセッション トークンです。</span><span class="sxs-lookup"><span data-stu-id="62112-141">The session token for use in session consistency.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoredProceduresQuota">
      <MemberSignature Language="C#" Value="public long StoredProceduresQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 StoredProceduresQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IFeedResponse`1.StoredProceduresQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StoredProceduresQuota As Long" />
      <MemberSignature Language="F#" Value="member this.StoredProceduresQuota : int64" Usage="Microsoft.Azure.Documents.Client.IFeedResponse&lt;'T&gt;.StoredProceduresQuota" />
      <MemberType>Property</MemberType>
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
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="62112-142">Azure Cosmos DB サービスのコレクションのストアド プロシージャの最大クォータを取得します。</span><span class="sxs-lookup"><span data-stu-id="62112-142">Gets the maximum quota of stored procedures for a collection in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="62112-143">最大クォータです。</span><span class="sxs-lookup"><span data-stu-id="62112-143">The maximum quota.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoredProceduresUsage">
      <MemberSignature Language="C#" Value="public long StoredProceduresUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 StoredProceduresUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IFeedResponse`1.StoredProceduresUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StoredProceduresUsage As Long" />
      <MemberSignature Language="F#" Value="member this.StoredProceduresUsage : int64" Usage="Microsoft.Azure.Documents.Client.IFeedResponse&lt;'T&gt;.StoredProceduresUsage" />
      <MemberType>Property</MemberType>
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
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="62112-144">現在では、Azure Cosmos DB サービスのコレクション用のストアド プロシージャの数。</span><span class="sxs-lookup"><span data-stu-id="62112-144">The current number of stored procedures for a collection in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="62112-145">現在のストアド プロシージャの数。</span><span class="sxs-lookup"><span data-stu-id="62112-145">Current number of stored procedures.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TriggersQuota">
      <MemberSignature Language="C#" Value="public long TriggersQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TriggersQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IFeedResponse`1.TriggersQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TriggersQuota As Long" />
      <MemberSignature Language="F#" Value="member this.TriggersQuota : int64" Usage="Microsoft.Azure.Documents.Client.IFeedResponse&lt;'T&gt;.TriggersQuota" />
      <MemberType>Property</MemberType>
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
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="62112-146">Azure Cosmos DB サービスのコレクションのトリガーの最大クォータを取得します。</span><span class="sxs-lookup"><span data-stu-id="62112-146">Gets the maximum quota of triggers for a collection in the Azure Cosmos DB service.</span></span> 
            </summary>
        <value>
            <span data-ttu-id="62112-147">最大クォータです。</span><span class="sxs-lookup"><span data-stu-id="62112-147">The maximum quota.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TriggersUsage">
      <MemberSignature Language="C#" Value="public long TriggersUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TriggersUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IFeedResponse`1.TriggersUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TriggersUsage As Long" />
      <MemberSignature Language="F#" Value="member this.TriggersUsage : int64" Usage="Microsoft.Azure.Documents.Client.IFeedResponse&lt;'T&gt;.TriggersUsage" />
      <MemberType>Property</MemberType>
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
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="62112-148">現在では、Azure Cosmos DB サービスのコレクションのトリガーの数。</span><span class="sxs-lookup"><span data-stu-id="62112-148">The current number of triggers for a collection in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="62112-149">現在のトリガーの数。</span><span class="sxs-lookup"><span data-stu-id="62112-149">Current number of triggers.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserDefinedFunctionsQuota">
      <MemberSignature Language="C#" Value="public long UserDefinedFunctionsQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 UserDefinedFunctionsQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IFeedResponse`1.UserDefinedFunctionsQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UserDefinedFunctionsQuota As Long" />
      <MemberSignature Language="F#" Value="member this.UserDefinedFunctionsQuota : int64" Usage="Microsoft.Azure.Documents.Client.IFeedResponse&lt;'T&gt;.UserDefinedFunctionsQuota" />
      <MemberType>Property</MemberType>
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
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="62112-150">Azure Cosmos DB サービスのコレクションのユーザー定義関数の最大クォータを取得します。</span><span class="sxs-lookup"><span data-stu-id="62112-150">Gets the maximum quota of user defined functions for a collection in the Azure Cosmos DB service.</span></span> 
            </summary>
        <value>
            <span data-ttu-id="62112-151">最大クォータです。</span><span class="sxs-lookup"><span data-stu-id="62112-151">Maximum quota.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserDefinedFunctionsUsage">
      <MemberSignature Language="C#" Value="public long UserDefinedFunctionsUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 UserDefinedFunctionsUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IFeedResponse`1.UserDefinedFunctionsUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UserDefinedFunctionsUsage As Long" />
      <MemberSignature Language="F#" Value="member this.UserDefinedFunctionsUsage : int64" Usage="Microsoft.Azure.Documents.Client.IFeedResponse&lt;'T&gt;.UserDefinedFunctionsUsage" />
      <MemberType>Property</MemberType>
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
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="62112-152">ユーザーの現在の数は、Azure Cosmos DB サービスでコレクションの機能を定義します。</span><span class="sxs-lookup"><span data-stu-id="62112-152">The current number of user defined functions for a collection in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="62112-153">ユーザーの現在の数は、関数を定義します。</span><span class="sxs-lookup"><span data-stu-id="62112-153">Current number of user defined functions.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserQuota">
      <MemberSignature Language="C#" Value="public long UserQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 UserQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IFeedResponse`1.UserQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UserQuota As Long" />
      <MemberSignature Language="F#" Value="member this.UserQuota : int64" Usage="Microsoft.Azure.Documents.Client.IFeedResponse&lt;'T&gt;.UserQuota" />
      <MemberType>Property</MemberType>
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
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="62112-154">Azure Cosmos DB データベース アカウント内のユーザー リソースの最大クォータを取得します。</span><span class="sxs-lookup"><span data-stu-id="62112-154">Gets the maximum quota for user resources within the Azure Cosmos DB database account.</span></span>
            </summary>
        <value>
            <span data-ttu-id="62112-155">アカウントの最大クォータです。</span><span class="sxs-lookup"><span data-stu-id="62112-155">The maximum quota for the account.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserUsage">
      <MemberSignature Language="C#" Value="public long UserUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 UserUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IFeedResponse`1.UserUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UserUsage As Long" />
      <MemberSignature Language="F#" Value="member this.UserUsage : int64" Usage="Microsoft.Azure.Documents.Client.IFeedResponse&lt;'T&gt;.UserUsage" />
      <MemberType>Property</MemberType>
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
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="62112-156">現在 Azure Cosmos DB データベース アカウント内のユーザー リソースの数。</span><span class="sxs-lookup"><span data-stu-id="62112-156">The current number of user resources within the Azure Cosmos DB database account.</span></span>
            </summary>
        <value>
            <span data-ttu-id="62112-157">ユーザーの数。</span><span class="sxs-lookup"><span data-stu-id="62112-157">The number of users.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>