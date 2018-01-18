<Type Name="FeedResponse&lt;T&gt;" FullName="Microsoft.Azure.Documents.Client.FeedResponse&lt;T&gt;">
  <TypeSignature Language="C#" Value="public class FeedResponse&lt;T&gt; : Microsoft.Azure.Documents.Client.IFeedResponse&lt;T&gt;, System.Collections.Generic.IEnumerable&lt;T&gt;, System.Dynamic.IDynamicMetaObjectProvider" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FeedResponse`1&lt;T&gt; extends System.Object implements class Microsoft.Azure.Documents.Client.IFeedResponse`1&lt;!T&gt;, class System.Collections.Generic.IEnumerable`1&lt;!T&gt;, class System.Collections.IEnumerable, class System.Dynamic.IDynamicMetaObjectProvider" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Client.FeedResponse`1" />
  <TypeSignature Language="VB.NET" Value="Public Class FeedResponse(Of T)&#xA;Implements IDynamicMetaObjectProvider, IEnumerable(Of T), IFeedResponse(Of T)" />
  <TypeSignature Language="F#" Value="type FeedResponse&lt;'T&gt; = class&#xA;    interface seq&lt;'T&gt;&#xA;    interface IEnumerable&#xA;    interface IDynamicMetaObjectProvider&#xA;    interface IFeedResponse&lt;'T&gt;" />
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
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Documents.Client.IFeedResponse&lt;T&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;T&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Dynamic.IDynamicMetaObjectProvider</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="T"><span data-ttu-id="23067-101">フィードの種類。</span><span class="sxs-lookup"><span data-stu-id="23067-101">The feed type.</span></span></typeparam>
    <summary>
            <span data-ttu-id="23067-102">Azure Cosmos DB サービスのメソッド (列挙操作) フィードで使用されるテンプレート クラスを表します。</span><span class="sxs-lookup"><span data-stu-id="23067-102">Represents the template class used by feed methods (enumeration operations) for the Azure Cosmos DB service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FeedResponse ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.FeedResponse`1.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
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
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="23067-103">目的のモックに公開されているコンス トラクターです。</span><span class="sxs-lookup"><span data-stu-id="23067-103">Constructor exposed for mocking purposes.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FeedResponse (System.Collections.Generic.IEnumerable&lt;T&gt; result);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;!T&gt; result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.FeedResponse`1.#ctor(System.Collections.Generic.IEnumerable{`0})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (result As IEnumerable(Of T))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Client.FeedResponse&lt;'T&gt; : seq&lt;'T&gt; -&gt; Microsoft.Azure.Documents.Client.FeedResponse&lt;'T&gt;" Usage="new Microsoft.Azure.Documents.Client.FeedResponse&lt;'T&gt; result" />
      <MemberType>Constructor</MemberType>
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
      <Parameters>
        <Parameter Name="result" Type="System.Collections.Generic.IEnumerable&lt;T&gt;" />
      </Parameters>
      <Docs>
        <param name="result"></param>
        <summary>
            <span data-ttu-id="23067-104">目的のモックに公開されているコンス トラクターです。</span><span class="sxs-lookup"><span data-stu-id="23067-104">Constructor exposed for mocking purposes.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActivityId">
      <MemberSignature Language="C#" Value="public string ActivityId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ActivityId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedResponse`1.ActivityId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActivityId As String" />
      <MemberSignature Language="F#" Value="member this.ActivityId : string" Usage="Microsoft.Azure.Documents.Client.FeedResponse&lt;'T&gt;.ActivityId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IFeedResponse`1.ActivityId</InterfaceMember>
      </Implements>
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
            <span data-ttu-id="23067-105">Azure Cosmos DB サービスからの要求のアクティビティ ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="23067-105">Gets the activity ID for the request from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="23067-106">要求のアクティビティ ID。</span><span class="sxs-lookup"><span data-stu-id="23067-106">The activity ID for the request.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CollectionQuota">
      <MemberSignature Language="C#" Value="public long CollectionQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 CollectionQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedResponse`1.CollectionQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CollectionQuota As Long" />
      <MemberSignature Language="F#" Value="member this.CollectionQuota : int64" Usage="Microsoft.Azure.Documents.Client.FeedResponse&lt;'T&gt;.CollectionQuota" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IFeedResponse`1.CollectionQuota</InterfaceMember>
      </Implements>
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
            <span data-ttu-id="23067-107">Azure Cosmos DB サービスから、アカウント内のコレクション リソースの最大クォータを取得します。</span><span class="sxs-lookup"><span data-stu-id="23067-107">Gets the maximum quota for collection resources within an account from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="23067-108">アカウントの最大クォータです。</span><span class="sxs-lookup"><span data-stu-id="23067-108">The maximum quota for the account.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CollectionSizeQuota">
      <MemberSignature Language="C#" Value="public long CollectionSizeQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 CollectionSizeQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedResponse`1.CollectionSizeQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CollectionSizeQuota As Long" />
      <MemberSignature Language="F#" Value="member this.CollectionSizeQuota : int64" Usage="Microsoft.Azure.Documents.Client.FeedResponse&lt;'T&gt;.CollectionSizeQuota" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IFeedResponse`1.CollectionSizeQuota</InterfaceMember>
      </Implements>
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
            <span data-ttu-id="23067-109">コレクションの最大サイズをキロバイト単位で Azure Cosmos DB サービスから取得します。</span><span class="sxs-lookup"><span data-stu-id="23067-109">Gets the maximum size of a collection in kilobytes from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="23067-110">クォータ (キロバイト単位)。</span><span class="sxs-lookup"><span data-stu-id="23067-110">Quota in kilobytes.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CollectionSizeUsage">
      <MemberSignature Language="C#" Value="public long CollectionSizeUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 CollectionSizeUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedResponse`1.CollectionSizeUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CollectionSizeUsage As Long" />
      <MemberSignature Language="F#" Value="member this.CollectionSizeUsage : int64" Usage="Microsoft.Azure.Documents.Client.FeedResponse&lt;'T&gt;.CollectionSizeUsage" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IFeedResponse`1.CollectionSizeUsage</InterfaceMember>
      </Implements>
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
            <span data-ttu-id="23067-111">コレクションの現在のサイズをキロバイト単位で Azure Cosmos DB サービスから取得します。</span><span class="sxs-lookup"><span data-stu-id="23067-111">Gets the current size of a collection in kilobytes from the Azure Cosmos DB service.</span></span> 
            </summary>
        <value><span data-ttu-id="23067-112">現在コレクション サイズ。</span><span class="sxs-lookup"><span data-stu-id="23067-112">Current collection size in kilobytes.</span></span></value>
        <remarks>To be added.</remarks>
        <vallue>
            <span data-ttu-id="23067-113">現在コレクション サイズ。</span><span class="sxs-lookup"><span data-stu-id="23067-113">Current collection size in kilobytes.</span></span>
            </vallue>
      </Docs>
    </Member>
    <Member MemberName="CollectionUsage">
      <MemberSignature Language="C#" Value="public long CollectionUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 CollectionUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedResponse`1.CollectionUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CollectionUsage As Long" />
      <MemberSignature Language="F#" Value="member this.CollectionUsage : int64" Usage="Microsoft.Azure.Documents.Client.FeedResponse&lt;'T&gt;.CollectionUsage" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IFeedResponse`1.CollectionUsage</InterfaceMember>
      </Implements>
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
            <span data-ttu-id="23067-114">Azure Cosmos DB サービスから、アカウント内のコレクション リソースの現在の数を取得します。</span><span class="sxs-lookup"><span data-stu-id="23067-114">Gets the current number of collection resources within the account from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="23067-115">コレクションの数。</span><span class="sxs-lookup"><span data-stu-id="23067-115">The number of collections.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentLocation">
      <MemberSignature Language="C#" Value="public string ContentLocation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedResponse`1.ContentLocation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContentLocation As String" />
      <MemberSignature Language="F#" Value="member this.ContentLocation : string" Usage="Microsoft.Azure.Documents.Client.FeedResponse&lt;'T&gt;.ContentLocation" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IFeedResponse`1.ContentLocation</InterfaceMember>
      </Implements>
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
            <span data-ttu-id="23067-116">バーを取得、親のコンテンツの場所など、db/foo/colls/、Cosmos DB の Azure サービスからです。</span><span class="sxs-lookup"><span data-stu-id="23067-116">Gets the content parent location, for example, dbs/foo/colls/bar, from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public int Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedResponse`1.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Integer" />
      <MemberSignature Language="F#" Value="member this.Count : int" Usage="Microsoft.Azure.Documents.Client.FeedResponse&lt;'T&gt;.Count" />
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
            <span data-ttu-id="23067-117">Azure Cosmos DB サービスからの応答で返される項目数を取得します。</span><span class="sxs-lookup"><span data-stu-id="23067-117">Gets the number of items returned in the response from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="23067-118">応答内の項目の数。</span><span class="sxs-lookup"><span data-stu-id="23067-118">Count of items in the response.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentResourceQuotaUsage">
      <MemberSignature Language="C#" Value="public string CurrentResourceQuotaUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CurrentResourceQuotaUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedResponse`1.CurrentResourceQuotaUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentResourceQuotaUsage As String" />
      <MemberSignature Language="F#" Value="member this.CurrentResourceQuotaUsage : string" Usage="Microsoft.Azure.Documents.Client.FeedResponse&lt;'T&gt;.CurrentResourceQuotaUsage" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IFeedResponse`1.CurrentResourceQuotaUsage</InterfaceMember>
      </Implements>
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
            <span data-ttu-id="23067-119">Azure Cosmos DB サービスからこのエンティティの現在のサイズを取得します。</span><span class="sxs-lookup"><span data-stu-id="23067-119">Gets the current size of this entity from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="23067-120">このエンティティの現在のサイズ。</span><span class="sxs-lookup"><span data-stu-id="23067-120">The current size for this entity.</span></span> <span data-ttu-id="23067-121">その他のリソースのカウント ドキュメント リソースをキロバイト単位で測定されます。</span><span class="sxs-lookup"><span data-stu-id="23067-121">Measured in kilobytes for document resources and in counts for other resources.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseQuota">
      <MemberSignature Language="C#" Value="public long DatabaseQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DatabaseQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedResponse`1.DatabaseQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseQuota As Long" />
      <MemberSignature Language="F#" Value="member this.DatabaseQuota : int64" Usage="Microsoft.Azure.Documents.Client.FeedResponse&lt;'T&gt;.DatabaseQuota" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IFeedResponse`1.DatabaseQuota</InterfaceMember>
      </Implements>
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
            <span data-ttu-id="23067-122">Azure Cosmos DB サービスから、アカウント内のデータベース リソースの最大クォータを取得します。</span><span class="sxs-lookup"><span data-stu-id="23067-122">Gets the maximum quota for database resources within the account from the Azure Cosmos DB service.</span></span> 
            </summary>
        <value>
            <span data-ttu-id="23067-123">アカウントの最大クォータです。</span><span class="sxs-lookup"><span data-stu-id="23067-123">The maximum quota for the account.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseUsage">
      <MemberSignature Language="C#" Value="public long DatabaseUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DatabaseUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedResponse`1.DatabaseUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseUsage As Long" />
      <MemberSignature Language="F#" Value="member this.DatabaseUsage : int64" Usage="Microsoft.Azure.Documents.Client.FeedResponse&lt;'T&gt;.DatabaseUsage" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IFeedResponse`1.DatabaseUsage</InterfaceMember>
      </Implements>
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
            <span data-ttu-id="23067-124">Azure Cosmos DB サービスから、アカウント内のデータベース リソースの現在の数を取得します。</span><span class="sxs-lookup"><span data-stu-id="23067-124">Gets the current number of database resources within the account from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="23067-125">データベースの数。</span><span class="sxs-lookup"><span data-stu-id="23067-125">The number of databases.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedResponse`1.ETag" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string" Usage="Microsoft.Azure.Documents.Client.FeedResponse&lt;'T&gt;.ETag" />
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
            <span data-ttu-id="23067-126">ReadFeed REST 要求またはの ContinuationToken プロパティの非-If-match アクセス条件として使用できる Azure Cosmos DB サービス内の最後のトランザクションに関連付けられているエンティティ タグを取得<see cref="T:Microsoft.Azure.Documents.Client.ChangeFeedOptions" />パラメーター<see cref="M:Microsoft.Azure.Documents.Client.DocumentClient.CreateDocumentChangeFeedQuery(System.String,Microsoft.Azure.Documents.Client.ChangeFeedOptions)" />に変更をフィードの取得このエンティティ タグで指定されたトランザクション以降です。</span><span class="sxs-lookup"><span data-stu-id="23067-126">Gets the entity tag associated with last transaction in the Azure Cosmos DB service, which can be used as If-Non-Match Access condition for ReadFeed REST request or ContinuationToken property of <see cref="T:Microsoft.Azure.Documents.Client.ChangeFeedOptions" /> parameter for <see cref="M:Microsoft.Azure.Documents.Client.DocumentClient.CreateDocumentChangeFeedQuery(System.String,Microsoft.Azure.Documents.Client.ChangeFeedOptions)" /> to get feed changes since the transaction specified by this entity tag.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEnumerator">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;T&gt; GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerator`1&lt;!T&gt; GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.FeedResponse`1.GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEnumerator () As IEnumerator(Of T)" />
      <MemberSignature Language="F#" Value="abstract member GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;'T&gt;&#xA;override this.GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;'T&gt;" Usage="feedResponse.GetEnumerator " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IEnumerable`1.GetEnumerator</InterfaceMember>
        <InterfaceMember>M:Microsoft.Azure.Documents.Client.IFeedResponse`1.GetEnumerator</InterfaceMember>
      </Implements>
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
            <span data-ttu-id="23067-127">Azure Cosmos DB サービスからコレクションを反復処理する列挙子を返します。</span><span class="sxs-lookup"><span data-stu-id="23067-127">Returns an enumerator that iterates through a collection from the Azure Cosmos DB service.</span></span>
            </summary>
        <returns><span data-ttu-id="23067-128">コレクションを反復処理に使用できる IEnumerator オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="23067-128">An IEnumerator object that can be used to iterate through the collection.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsRUPerMinuteUsed">
      <MemberSignature Language="C#" Value="public bool IsRUPerMinuteUsed { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsRUPerMinuteUsed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedResponse`1.IsRUPerMinuteUsed" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsRUPerMinuteUsed As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsRUPerMinuteUsed : bool" Usage="Microsoft.Azure.Documents.Client.FeedResponse&lt;'T&gt;.IsRUPerMinuteUsed" />
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
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="23067-129">Azure Cosmos DB からの応答に関連付けられているフラグの要求単位 (Ru) からこのフィードの要求が処理されるかどうかをサービス/か、容量を分単位を取得します。</span><span class="sxs-lookup"><span data-stu-id="23067-129">Gets the flag associated with the response from the Azure Cosmos DB service whether this feed request is served from Request Units(RUs)/minute capacity or not.</span></span>
            </summary>
        <value>
            <span data-ttu-id="23067-130">この要求が 1 分あたりの RUs 容量から提供された場合は true。</span><span class="sxs-lookup"><span data-stu-id="23067-130">True if this request is served from RUs/minute capacity.</span></span> <span data-ttu-id="23067-131">それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="23067-131">Otherwise, false.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxResourceQuota">
      <MemberSignature Language="C#" Value="public string MaxResourceQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MaxResourceQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedResponse`1.MaxResourceQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxResourceQuota As String" />
      <MemberSignature Language="F#" Value="member this.MaxResourceQuota : string" Usage="Microsoft.Azure.Documents.Client.FeedResponse&lt;'T&gt;.MaxResourceQuota" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IFeedResponse`1.MaxResourceQuota</InterfaceMember>
      </Implements>
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
            <span data-ttu-id="23067-132">Azure Cosmos DB サービスからこのエンティティの最大サイズの制限を取得します。</span><span class="sxs-lookup"><span data-stu-id="23067-132">Gets the maximum size limit for this entity from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="23067-133">このエンティティの最大サイズの制限。</span><span class="sxs-lookup"><span data-stu-id="23067-133">The maximum size limit for this entity.</span></span> <span data-ttu-id="23067-134">その他のリソースのカウント ドキュメント リソースをキロバイト単位で測定されます。</span><span class="sxs-lookup"><span data-stu-id="23067-134">Measured in kilobytes for document resources and in counts for other resources.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PermissionQuota">
      <MemberSignature Language="C#" Value="public long PermissionQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 PermissionQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedResponse`1.PermissionQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PermissionQuota As Long" />
      <MemberSignature Language="F#" Value="member this.PermissionQuota : int64" Usage="Microsoft.Azure.Documents.Client.FeedResponse&lt;'T&gt;.PermissionQuota" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IFeedResponse`1.PermissionQuota</InterfaceMember>
      </Implements>
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
            <span data-ttu-id="23067-135">Azure Cosmos DB サービスから、アカウント内のアクセス許可リソースの最大クォータを取得します。</span><span class="sxs-lookup"><span data-stu-id="23067-135">Gets the maximum quota for permission resources within an account from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="23067-136">アカウントの最大クォータです。</span><span class="sxs-lookup"><span data-stu-id="23067-136">The maximum quota for the account.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PermissionUsage">
      <MemberSignature Language="C#" Value="public long PermissionUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 PermissionUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedResponse`1.PermissionUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PermissionUsage As Long" />
      <MemberSignature Language="F#" Value="member this.PermissionUsage : int64" Usage="Microsoft.Azure.Documents.Client.FeedResponse&lt;'T&gt;.PermissionUsage" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IFeedResponse`1.PermissionUsage</InterfaceMember>
      </Implements>
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
            <span data-ttu-id="23067-137">Azure Cosmos DB サービスから、アカウント内でのアクセス許可リソースの現在の数を取得します。</span><span class="sxs-lookup"><span data-stu-id="23067-137">Gets the current number of permission resources within the account from the Azure Cosmos DB service.</span></span> 
            </summary>
        <value>
            <span data-ttu-id="23067-138">アクセス許可の数。</span><span class="sxs-lookup"><span data-stu-id="23067-138">The number of permissions.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QueryMetrics">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Documents.QueryMetrics&gt; QueryMetrics { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Documents.QueryMetrics&gt; QueryMetrics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedResponse`1.QueryMetrics" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property QueryMetrics As IReadOnlyDictionary(Of String, QueryMetrics)" />
      <MemberSignature Language="F#" Value="member this.QueryMetrics : System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Documents.QueryMetrics&gt;" Usage="Microsoft.Azure.Documents.Client.FeedResponse&lt;'T&gt;.QueryMetrics" />
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
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Documents.QueryMetrics&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="23067-139">取得<see cref="T:Microsoft.Azure.Documents.QueryMetrics" />Azure Cosmos DB サービスの個別のパーティションごとに</span><span class="sxs-lookup"><span data-stu-id="23067-139">Get <see cref="T:Microsoft.Azure.Documents.QueryMetrics" /> for each individual partition in the Azure Cosmos DB service</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestCharge">
      <MemberSignature Language="C#" Value="public double RequestCharge { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 RequestCharge" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedResponse`1.RequestCharge" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestCharge As Double" />
      <MemberSignature Language="F#" Value="member this.RequestCharge : double" Usage="Microsoft.Azure.Documents.Client.FeedResponse&lt;'T&gt;.RequestCharge" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IFeedResponse`1.RequestCharge</InterfaceMember>
      </Implements>
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
            <span data-ttu-id="23067-140">Azure Cosmos DB サービスからこの要求の要求の料金を取得します。</span><span class="sxs-lookup"><span data-stu-id="23067-140">Gets the request charge for this request from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="23067-141">要求の料金は、reqest 単位で測定されます。</span><span class="sxs-lookup"><span data-stu-id="23067-141">The request charge measured in reqest units.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResponseContinuation">
      <MemberSignature Language="C#" Value="public string ResponseContinuation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResponseContinuation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedResponse`1.ResponseContinuation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResponseContinuation As String" />
      <MemberSignature Language="F#" Value="member this.ResponseContinuation : string" Usage="Microsoft.Azure.Documents.Client.FeedResponse&lt;'T&gt;.ResponseContinuation" />
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
            <span data-ttu-id="23067-142">Azure Cosmos DB サービスの列挙を継続するために使用する継続トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="23067-142">Gets the continuation token to be used for continuing enumeration of the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="23067-143">列挙体を継続するために使用する継続トークンです。</span><span class="sxs-lookup"><span data-stu-id="23067-143">The continuation token to be used for continuing enumeration.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResponseHeaders">
      <MemberSignature Language="C#" Value="public System.Collections.Specialized.NameValueCollection ResponseHeaders { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Specialized.NameValueCollection ResponseHeaders" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedResponse`1.ResponseHeaders" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResponseHeaders As NameValueCollection" />
      <MemberSignature Language="F#" Value="member this.ResponseHeaders : System.Collections.Specialized.NameValueCollection" Usage="Microsoft.Azure.Documents.Client.FeedResponse&lt;'T&gt;.ResponseHeaders" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IFeedResponse`1.ResponseHeaders</InterfaceMember>
      </Implements>
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
            <span data-ttu-id="23067-144">Azure Cosmos DB サービスからの応答ヘッダーを取得します。</span><span class="sxs-lookup"><span data-stu-id="23067-144">Gets the response headers from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="23067-145">応答ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="23067-145">The response headers.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SessionToken">
      <MemberSignature Language="C#" Value="public string SessionToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SessionToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedResponse`1.SessionToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SessionToken As String" />
      <MemberSignature Language="F#" Value="member this.SessionToken : string" Usage="Microsoft.Azure.Documents.Client.FeedResponse&lt;'T&gt;.SessionToken" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IFeedResponse`1.SessionToken</InterfaceMember>
      </Implements>
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
            <span data-ttu-id="23067-146">セッションのトークンを取得セッション整合性読み取りで使用する Azure Cosmos DB サービスからです。</span><span class="sxs-lookup"><span data-stu-id="23067-146">Gets the session token for use in sesssion consistency reads from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="23067-147">セッションで使用するためのセッション トークンです。</span><span class="sxs-lookup"><span data-stu-id="23067-147">The session token for use in session consistency.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoredProceduresQuota">
      <MemberSignature Language="C#" Value="public long StoredProceduresQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 StoredProceduresQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedResponse`1.StoredProceduresQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StoredProceduresQuota As Long" />
      <MemberSignature Language="F#" Value="member this.StoredProceduresQuota : int64" Usage="Microsoft.Azure.Documents.Client.FeedResponse&lt;'T&gt;.StoredProceduresQuota" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IFeedResponse`1.StoredProceduresQuota</InterfaceMember>
      </Implements>
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
            <span data-ttu-id="23067-148">Azure Cosmos DB サービスから一連のストアド プロシージャの最大クォータを取得します。</span><span class="sxs-lookup"><span data-stu-id="23067-148">Gets the maximum quota of stored procedures for a collection from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="23067-149">最大クォータです。</span><span class="sxs-lookup"><span data-stu-id="23067-149">The maximum quota.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoredProceduresUsage">
      <MemberSignature Language="C#" Value="public long StoredProceduresUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 StoredProceduresUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedResponse`1.StoredProceduresUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StoredProceduresUsage As Long" />
      <MemberSignature Language="F#" Value="member this.StoredProceduresUsage : int64" Usage="Microsoft.Azure.Documents.Client.FeedResponse&lt;'T&gt;.StoredProceduresUsage" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IFeedResponse`1.StoredProceduresUsage</InterfaceMember>
      </Implements>
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
            <span data-ttu-id="23067-150">Azure Cosmos DB サービスから一連のストアド プロシージャの現在の数を取得します。</span><span class="sxs-lookup"><span data-stu-id="23067-150">Gets the current number of stored procedures for a collection from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="23067-151">現在のストアド プロシージャの数。</span><span class="sxs-lookup"><span data-stu-id="23067-151">Current number of stored procedures.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IEnumerable.GetEnumerator">
      <MemberSignature Language="C#" Value="System.Collections.IEnumerator IEnumerable.GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Collections.IEnumerator System.Collections.IEnumerable.GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.FeedResponse`1.System#Collections#IEnumerable#GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Function GetEnumerator () As IEnumerator Implements IEnumerable.GetEnumerator" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.IEnumerable.GetEnumerator</InterfaceMember>
      </Implements>
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
        <ReturnType>System.Collections.IEnumerator</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Dynamic.IDynamicMetaObjectProvider.GetMetaObject">
      <MemberSignature Language="C#" Value="System.Dynamic.DynamicMetaObject IDynamicMetaObjectProvider.GetMetaObject (System.Linq.Expressions.Expression parameter);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Dynamic.DynamicMetaObject System.Dynamic.IDynamicMetaObjectProvider.GetMetaObject(class System.Linq.Expressions.Expression parameter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.FeedResponse`1.System#Dynamic#IDynamicMetaObjectProvider#GetMetaObject(System.Linq.Expressions.Expression)" />
      <MemberSignature Language="VB.NET" Value="Function GetMetaObject (parameter As Expression) As DynamicMetaObject Implements IDynamicMetaObjectProvider.GetMetaObject" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Dynamic.IDynamicMetaObjectProvider.GetMetaObject(System.Linq.Expressions.Expression)</InterfaceMember>
      </Implements>
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
        <ReturnType>System.Dynamic.DynamicMetaObject</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameter" Type="System.Linq.Expressions.Expression" />
      </Parameters>
      <Docs>
        <param name="parameter">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TriggersQuota">
      <MemberSignature Language="C#" Value="public long TriggersQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TriggersQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedResponse`1.TriggersQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TriggersQuota As Long" />
      <MemberSignature Language="F#" Value="member this.TriggersQuota : int64" Usage="Microsoft.Azure.Documents.Client.FeedResponse&lt;'T&gt;.TriggersQuota" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IFeedResponse`1.TriggersQuota</InterfaceMember>
      </Implements>
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
            <span data-ttu-id="23067-152">Azure Cosmos DB サービスからコレクションのトリガーの最大クォータを取得します。</span><span class="sxs-lookup"><span data-stu-id="23067-152">Gets the maximum quota of triggers for a collection from the Azure Cosmos DB service.</span></span> 
            </summary>
        <value>
            <span data-ttu-id="23067-153">最大クォータです。</span><span class="sxs-lookup"><span data-stu-id="23067-153">The maximum quota.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TriggersUsage">
      <MemberSignature Language="C#" Value="public long TriggersUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TriggersUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedResponse`1.TriggersUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TriggersUsage As Long" />
      <MemberSignature Language="F#" Value="member this.TriggersUsage : int64" Usage="Microsoft.Azure.Documents.Client.FeedResponse&lt;'T&gt;.TriggersUsage" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IFeedResponse`1.TriggersUsage</InterfaceMember>
      </Implements>
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
            <span data-ttu-id="23067-154">Azure Cosmos DB サービスからコレクションのトリガーの現在の数を取得します。</span><span class="sxs-lookup"><span data-stu-id="23067-154">Get the current number of triggers for a collection from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="23067-155">現在のトリガーの数。</span><span class="sxs-lookup"><span data-stu-id="23067-155">Current number of triggers.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserDefinedFunctionsQuota">
      <MemberSignature Language="C#" Value="public long UserDefinedFunctionsQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 UserDefinedFunctionsQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedResponse`1.UserDefinedFunctionsQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UserDefinedFunctionsQuota As Long" />
      <MemberSignature Language="F#" Value="member this.UserDefinedFunctionsQuota : int64" Usage="Microsoft.Azure.Documents.Client.FeedResponse&lt;'T&gt;.UserDefinedFunctionsQuota" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IFeedResponse`1.UserDefinedFunctionsQuota</InterfaceMember>
      </Implements>
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
            <span data-ttu-id="23067-156">Azure Cosmos DB サービスからコレクションのユーザー定義関数の最大クォータを取得します。</span><span class="sxs-lookup"><span data-stu-id="23067-156">Gets the maximum quota of user defined functions for a collection from the Azure Cosmos DB service.</span></span> 
            </summary>
        <value>
            <span data-ttu-id="23067-157">最大クォータです。</span><span class="sxs-lookup"><span data-stu-id="23067-157">Maximum quota.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserDefinedFunctionsUsage">
      <MemberSignature Language="C#" Value="public long UserDefinedFunctionsUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 UserDefinedFunctionsUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedResponse`1.UserDefinedFunctionsUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UserDefinedFunctionsUsage As Long" />
      <MemberSignature Language="F#" Value="member this.UserDefinedFunctionsUsage : int64" Usage="Microsoft.Azure.Documents.Client.FeedResponse&lt;'T&gt;.UserDefinedFunctionsUsage" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IFeedResponse`1.UserDefinedFunctionsUsage</InterfaceMember>
      </Implements>
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
            <span data-ttu-id="23067-158">Azure Cosmos DB サービスからコレクションの現在のユーザー定義関数の数を取得します。</span><span class="sxs-lookup"><span data-stu-id="23067-158">Gets the current number of user defined functions for a collection from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="23067-159">ユーザーの現在の数は、関数を定義します。</span><span class="sxs-lookup"><span data-stu-id="23067-159">Current number of user defined functions.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserQuota">
      <MemberSignature Language="C#" Value="public long UserQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 UserQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedResponse`1.UserQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UserQuota As Long" />
      <MemberSignature Language="F#" Value="member this.UserQuota : int64" Usage="Microsoft.Azure.Documents.Client.FeedResponse&lt;'T&gt;.UserQuota" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IFeedResponse`1.UserQuota</InterfaceMember>
      </Implements>
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
            <span data-ttu-id="23067-160">Azure Cosmos DB サービスから、アカウント内のユーザー リソースの最大クォータを取得します。</span><span class="sxs-lookup"><span data-stu-id="23067-160">Gets the maximum quota for user resources within an account from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="23067-161">アカウントの最大クォータです。</span><span class="sxs-lookup"><span data-stu-id="23067-161">The maximum quota for the account.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserUsage">
      <MemberSignature Language="C#" Value="public long UserUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 UserUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedResponse`1.UserUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UserUsage As Long" />
      <MemberSignature Language="F#" Value="member this.UserUsage : int64" Usage="Microsoft.Azure.Documents.Client.FeedResponse&lt;'T&gt;.UserUsage" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IFeedResponse`1.UserUsage</InterfaceMember>
      </Implements>
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
            <span data-ttu-id="23067-162">Azure Cosmos DB サービスから、アカウント内のユーザー リソースの現在の数を取得します。</span><span class="sxs-lookup"><span data-stu-id="23067-162">Gets the current number of user resources within the account from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="23067-163">ユーザーの数。</span><span class="sxs-lookup"><span data-stu-id="23067-163">The number of users.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>