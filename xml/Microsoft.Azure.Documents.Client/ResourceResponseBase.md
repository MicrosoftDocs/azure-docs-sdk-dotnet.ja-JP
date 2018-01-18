<Type Name="ResourceResponseBase" FullName="Microsoft.Azure.Documents.Client.ResourceResponseBase">
  <TypeSignature Language="C#" Value="public abstract class ResourceResponseBase : Microsoft.Azure.Documents.Client.IResourceResponseBase" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ResourceResponseBase extends System.Object implements class Microsoft.Azure.Documents.Client.IResourceResponseBase" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Client.ResourceResponseBase" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ResourceResponseBase&#xA;Implements IResourceResponseBase" />
  <TypeSignature Language="F#" Value="type ResourceResponseBase = class&#xA;    interface IResourceResponseBase" />
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
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Documents.Client.IResourceResponseBase</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="0a9bc-101">Azure Cosmos DB サービスのすべての要求によって返されるリソース以外の特定のサービスの応答ヘッダーを表します。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-101">Represents the non-resource specific service response headers returned by any request in the Azure Cosmos DB service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceResponseBase ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.ResourceResponseBase.#ctor" />
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
            <span data-ttu-id="0a9bc-102">Azure Cosmos DB サービスの目的をモックに公開されているコンス トラクターです。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-102">Constructor exposed for mocking purposes for the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActivityId">
      <MemberSignature Language="C#" Value="public string ActivityId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ActivityId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.ResourceResponseBase.ActivityId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActivityId As String" />
      <MemberSignature Language="F#" Value="member this.ActivityId : string" Usage="Microsoft.Azure.Documents.Client.ResourceResponseBase.ActivityId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IResourceResponseBase.ActivityId</InterfaceMember>
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
            <span data-ttu-id="0a9bc-103">Azure Cosmos DB サービスからの要求のアクティビティ ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-103">Gets the activity ID for the request from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="0a9bc-104">要求のアクティビティ ID。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-104">The activity ID for the request.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CollectionQuota">
      <MemberSignature Language="C#" Value="public long CollectionQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 CollectionQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.ResourceResponseBase.CollectionQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CollectionQuota As Long" />
      <MemberSignature Language="F#" Value="member this.CollectionQuota : int64" Usage="Microsoft.Azure.Documents.Client.ResourceResponseBase.CollectionQuota" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IResourceResponseBase.CollectionQuota</InterfaceMember>
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
            <span data-ttu-id="0a9bc-105">Azure Cosmos DB サービスから、アカウント内のコレクション リソースの最大クォータを取得します。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-105">Gets the maximum quota for collection resources within an account from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="0a9bc-106">アカウントの最大クォータです。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-106">The maximum quota for the account.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CollectionSizeQuota">
      <MemberSignature Language="C#" Value="public long CollectionSizeQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 CollectionSizeQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.ResourceResponseBase.CollectionSizeQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CollectionSizeQuota As Long" />
      <MemberSignature Language="F#" Value="member this.CollectionSizeQuota : int64" Usage="Microsoft.Azure.Documents.Client.ResourceResponseBase.CollectionSizeQuota" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IResourceResponseBase.CollectionSizeQuota</InterfaceMember>
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
            <span data-ttu-id="0a9bc-107">コレクションの最大サイズをキロバイト単位で Azure Cosmos DB サービスから取得します。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-107">Gets the maximum size of a collection in kilobytes from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="0a9bc-108">クォータ (キロバイト単位)。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-108">Quota in kilobytes.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CollectionSizeUsage">
      <MemberSignature Language="C#" Value="public long CollectionSizeUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 CollectionSizeUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.ResourceResponseBase.CollectionSizeUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CollectionSizeUsage As Long" />
      <MemberSignature Language="F#" Value="member this.CollectionSizeUsage : int64" Usage="Microsoft.Azure.Documents.Client.ResourceResponseBase.CollectionSizeUsage" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IResourceResponseBase.CollectionSizeUsage</InterfaceMember>
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
            <span data-ttu-id="0a9bc-109">コレクションの現在のサイズをキロバイト単位で Azure Cosmos DB サービスから取得します。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-109">Gets the current size of a collection in kilobytes from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="0a9bc-110">現在コレクション サイズ。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-110">Current collection size in kilobytes.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CollectionUsage">
      <MemberSignature Language="C#" Value="public long CollectionUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 CollectionUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.ResourceResponseBase.CollectionUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CollectionUsage As Long" />
      <MemberSignature Language="F#" Value="member this.CollectionUsage : int64" Usage="Microsoft.Azure.Documents.Client.ResourceResponseBase.CollectionUsage" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IResourceResponseBase.CollectionUsage</InterfaceMember>
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
            <span data-ttu-id="0a9bc-111">Azure Cosmos DB サービスから、アカウント内のコレクション リソースの現在の数を取得します。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-111">Gets the current number of collection resources within the account from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="0a9bc-112">コレクションの数。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-112">The number of collections.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentLocation">
      <MemberSignature Language="C#" Value="public string ContentLocation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.ResourceResponseBase.ContentLocation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContentLocation As String" />
      <MemberSignature Language="F#" Value="member this.ContentLocation : string" Usage="Microsoft.Azure.Documents.Client.ResourceResponseBase.ContentLocation" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IResourceResponseBase.ContentLocation</InterfaceMember>
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
            <span data-ttu-id="0a9bc-113">コンテンツの親場所、たとえば、db/foo/colls/バーで、Azure Cosmos DB サービスです。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-113">The content parent location, for example, dbs/foo/colls/bar in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentResourceQuotaUsage">
      <MemberSignature Language="C#" Value="public string CurrentResourceQuotaUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CurrentResourceQuotaUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.ResourceResponseBase.CurrentResourceQuotaUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentResourceQuotaUsage As String" />
      <MemberSignature Language="F#" Value="member this.CurrentResourceQuotaUsage : string" Usage="Microsoft.Azure.Documents.Client.ResourceResponseBase.CurrentResourceQuotaUsage" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IResourceResponseBase.CurrentResourceQuotaUsage</InterfaceMember>
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
            <span data-ttu-id="0a9bc-114">Azure Cosmos DB サービスからこのエンティティの現在のサイズを取得します。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-114">Gets the current size of this entity from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="0a9bc-115">このエンティティの現在のサイズ。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-115">The current size for this entity.</span></span> <span data-ttu-id="0a9bc-116">その他のリソースのカウント ドキュメント リソースをキロバイト単位で測定されます。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-116">Measured in kilobytes for document resources and in counts for other resources.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseQuota">
      <MemberSignature Language="C#" Value="public long DatabaseQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DatabaseQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.ResourceResponseBase.DatabaseQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseQuota As Long" />
      <MemberSignature Language="F#" Value="member this.DatabaseQuota : int64" Usage="Microsoft.Azure.Documents.Client.ResourceResponseBase.DatabaseQuota" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IResourceResponseBase.DatabaseQuota</InterfaceMember>
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
            <span data-ttu-id="0a9bc-117">Azure Cosmos DB サービスから、アカウント内のデータベース リソースの最大クォータを取得します。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-117">Gets the maximum quota for database resources within the account from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="0a9bc-118">アカウントの最大クォータです。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-118">The maximum quota for the account.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseUsage">
      <MemberSignature Language="C#" Value="public long DatabaseUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DatabaseUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.ResourceResponseBase.DatabaseUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseUsage As Long" />
      <MemberSignature Language="F#" Value="member this.DatabaseUsage : int64" Usage="Microsoft.Azure.Documents.Client.ResourceResponseBase.DatabaseUsage" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IResourceResponseBase.DatabaseUsage</InterfaceMember>
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
            <span data-ttu-id="0a9bc-119">Azure Cosmos DB サービスから、アカウント内のデータベース リソースの現在の数を取得します。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-119">Gets the current number of database resources within the account from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="0a9bc-120">データベースの数。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-120">The number of databases.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DocumentQuota">
      <MemberSignature Language="C#" Value="public long DocumentQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DocumentQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.ResourceResponseBase.DocumentQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DocumentQuota As Long" />
      <MemberSignature Language="F#" Value="member this.DocumentQuota : int64" Usage="Microsoft.Azure.Documents.Client.ResourceResponseBase.DocumentQuota" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IResourceResponseBase.DocumentQuota</InterfaceMember>
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
            <span data-ttu-id="0a9bc-121">コレクション内のドキュメントの最大サイズをキロバイト単位で Azure Cosmos DB サービスから取得します。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-121">Gets the maximum size of a documents within a collection in kilobytes from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="0a9bc-122">クォータ (キロバイト単位)。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-122">Quota in kilobytes.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DocumentUsage">
      <MemberSignature Language="C#" Value="public long DocumentUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DocumentUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.ResourceResponseBase.DocumentUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DocumentUsage As Long" />
      <MemberSignature Language="F#" Value="member this.DocumentUsage : int64" Usage="Microsoft.Azure.Documents.Client.ResourceResponseBase.DocumentUsage" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IResourceResponseBase.DocumentUsage</InterfaceMember>
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
            <span data-ttu-id="0a9bc-123">コレクション内のドキュメントの現在のサイズをキロバイト単位で Azure Cosmos DB サービスから取得します。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-123">Gets the current size of documents within a collection in kilobytes from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="0a9bc-124">現在のドキュメント サイズ。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-124">Current documents size in kilobytes.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexTransformationProgress">
      <MemberSignature Language="C#" Value="public long IndexTransformationProgress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 IndexTransformationProgress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.ResourceResponseBase.IndexTransformationProgress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IndexTransformationProgress As Long" />
      <MemberSignature Language="F#" Value="member this.IndexTransformationProgress : int64" Usage="Microsoft.Azure.Documents.Client.ResourceResponseBase.IndexTransformationProgress" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IResourceResponseBase.IndexTransformationProgress</InterfaceMember>
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
            <span data-ttu-id="0a9bc-125">Azure Cosmos DB サービスから 1 つが進行中の場合、インデックスの変換の進行状況を取得します。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-125">Gets the progress of an index transformation, if one is underway from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="0a9bc-126">0 ~ 100 の整数インデックスの変換処理の完了率を表すです。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-126">An integer from 0 to 100 representing percentage completion of the index transformation process.</span></span>
            <span data-ttu-id="0a9bc-127">インデックスの変換にはヘッダーが進行状況の場合は-1 を返しますが見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-127">Returns -1 if the index transformation progress header could not be found.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="0a9bc-128">コレクションの IndexPolicy が更新されたときに、インデックスを再構築されます。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-128">An index will be rebuilt when the IndexPolicy of a collection is updated.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="IsRUPerMinuteUsed">
      <MemberSignature Language="C#" Value="public bool IsRUPerMinuteUsed { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsRUPerMinuteUsed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.ResourceResponseBase.IsRUPerMinuteUsed" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsRUPerMinuteUsed As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsRUPerMinuteUsed : bool" Usage="Microsoft.Azure.Documents.Client.ResourceResponseBase.IsRUPerMinuteUsed" />
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
            <span data-ttu-id="0a9bc-129">Azure Cosmos DB からの応答に関連付けられているフラグの要求単位 (Ru) からこの要求が処理されるかどうかをサービス/か、容量を分単位を取得します。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-129">Gets the flag associated with the response from the Azure Cosmos DB service whether this request is served from Request Units(RUs)/minute capacity or not.</span></span>
            </summary>
        <value>
            <span data-ttu-id="0a9bc-130">この要求が 1 分あたりの RUs 容量から提供された場合は true。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-130">True if this request is served from RUs/minute capacity.</span></span> <span data-ttu-id="0a9bc-131">それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-131">Otherwise, false.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LazyIndexingProgress">
      <MemberSignature Language="C#" Value="public long LazyIndexingProgress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 LazyIndexingProgress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.ResourceResponseBase.LazyIndexingProgress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LazyIndexingProgress As Long" />
      <MemberSignature Language="F#" Value="member this.LazyIndexingProgress : int64" Usage="Microsoft.Azure.Documents.Client.ResourceResponseBase.LazyIndexingProgress" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IResourceResponseBase.LazyIndexingProgress</InterfaceMember>
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
            <span data-ttu-id="0a9bc-132">Azure Cosmos DB サービスから遅延インデックス作成の進行状況を取得します。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-132">Gets the progress of lazy indexing from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="0a9bc-133">100、限定的なインデックス作成プロセスの完了率を表す 0 から整数。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-133">An integer from 0 to 100 representing percentage completion of the lazy indexing process.</span></span>
            <span data-ttu-id="0a9bc-134">限定的なインデックス作成の進行状況ヘッダーが見つからなかった場合は、-1 を返します。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-134">Returns -1 if the lazy indexing progress header could not be found.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="0a9bc-135">遅延インデックス作成の進行状況は、インデックス作成モード Lazy を持つコレクションにのみ適用されます。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-135">Lazy indexing progress only applies to the collection with indexing mode Lazy.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxResourceQuota">
      <MemberSignature Language="C#" Value="public string MaxResourceQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MaxResourceQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.ResourceResponseBase.MaxResourceQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxResourceQuota As String" />
      <MemberSignature Language="F#" Value="member this.MaxResourceQuota : string" Usage="Microsoft.Azure.Documents.Client.ResourceResponseBase.MaxResourceQuota" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IResourceResponseBase.MaxResourceQuota</InterfaceMember>
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
            <span data-ttu-id="0a9bc-136">Azure Cosmos DB サービスからこのエンティティの最大サイズの制限を取得します。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-136">Gets the maximum size limit for this entity from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="0a9bc-137">このエンティティの最大サイズの制限。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-137">The maximum size limit for this entity.</span></span> <span data-ttu-id="0a9bc-138">その他のリソースのカウント ドキュメント リソースをキロバイト単位で測定されます。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-138">Measured in kilobytes for document resources and in counts for other resources.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PermissionQuota">
      <MemberSignature Language="C#" Value="public long PermissionQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 PermissionQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.ResourceResponseBase.PermissionQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PermissionQuota As Long" />
      <MemberSignature Language="F#" Value="member this.PermissionQuota : int64" Usage="Microsoft.Azure.Documents.Client.ResourceResponseBase.PermissionQuota" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IResourceResponseBase.PermissionQuota</InterfaceMember>
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
            <span data-ttu-id="0a9bc-139">Azure Cosmos DB サービスから、アカウント内のアクセス許可リソースの最大クォータを取得します。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-139">Gets the maximum quota for permission resources within an account from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="0a9bc-140">アカウントの最大クォータです。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-140">The maximum quota for the account.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PermissionUsage">
      <MemberSignature Language="C#" Value="public long PermissionUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 PermissionUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.ResourceResponseBase.PermissionUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PermissionUsage As Long" />
      <MemberSignature Language="F#" Value="member this.PermissionUsage : int64" Usage="Microsoft.Azure.Documents.Client.ResourceResponseBase.PermissionUsage" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IResourceResponseBase.PermissionUsage</InterfaceMember>
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
            <span data-ttu-id="0a9bc-141">Azure Cosmos DB サービスから、アカウント内でのアクセス許可リソースの現在の数を取得します。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-141">Gets the current number of permission resources within the account from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="0a9bc-142">アクセス許可の数。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-142">The number of permissions.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestCharge">
      <MemberSignature Language="C#" Value="public double RequestCharge { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 RequestCharge" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.ResourceResponseBase.RequestCharge" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestCharge As Double" />
      <MemberSignature Language="F#" Value="member this.RequestCharge : double" Usage="Microsoft.Azure.Documents.Client.ResourceResponseBase.RequestCharge" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IResourceResponseBase.RequestCharge</InterfaceMember>
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
            <span data-ttu-id="0a9bc-143">Azure Cosmos DB サービスからこの要求の要求の料金を取得します。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-143">Gets the request charge for this request from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="0a9bc-144">要求の料金は、reqest 単位で測定されます。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-144">The request charge measured in reqest units.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestDiagnosticsString">
      <MemberSignature Language="C#" Value="public string RequestDiagnosticsString { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequestDiagnosticsString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.ResourceResponseBase.RequestDiagnosticsString" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestDiagnosticsString As String" />
      <MemberSignature Language="F#" Value="member this.RequestDiagnosticsString : string" Usage="Microsoft.Azure.Documents.Client.ResourceResponseBase.RequestDiagnosticsString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0a9bc-145">Azure Cosmos DB サービスの現在の要求の診断情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-145">Gets the diagnostics information for the current request to Azure Cosmos DB service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="0a9bc-146">このフィールドは、要求は、直接接続を使用する場合にのみ有効です。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-146">This field is only valid when the request uses direct connectivity.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestLatency">
      <MemberSignature Language="C#" Value="public TimeSpan RequestLatency { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan RequestLatency" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.ResourceResponseBase.RequestLatency" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestLatency As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.RequestLatency : TimeSpan" Usage="Microsoft.Azure.Documents.Client.ResourceResponseBase.RequestLatency" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0a9bc-147">Azure Cosmos DB サービスの現在の要求のエンド ツー エンドの要求の待機時間を取得します。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-147">Gets the end-to-end request latency for the current request to Azure Cosmos DB service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="0a9bc-148">このフィールドは、要求は、直接接続を使用する場合にのみ有効です。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-148">This field is only valid when the request uses direct connectivity.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResponseHeaders">
      <MemberSignature Language="C#" Value="public System.Collections.Specialized.NameValueCollection ResponseHeaders { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Specialized.NameValueCollection ResponseHeaders" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.ResourceResponseBase.ResponseHeaders" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResponseHeaders As NameValueCollection" />
      <MemberSignature Language="F#" Value="member this.ResponseHeaders : System.Collections.Specialized.NameValueCollection" Usage="Microsoft.Azure.Documents.Client.ResourceResponseBase.ResponseHeaders" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IResourceResponseBase.ResponseHeaders</InterfaceMember>
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
            <span data-ttu-id="0a9bc-149">Azure Cosmos DB サービスからの応答ヘッダーを取得します。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-149">Gets the response headers from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="0a9bc-150">応答ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-150">The response headers.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResponseStream">
      <MemberSignature Language="C#" Value="public System.IO.Stream ResponseStream { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.IO.Stream ResponseStream" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.ResourceResponseBase.ResponseStream" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResponseStream As Stream" />
      <MemberSignature Language="F#" Value="member this.ResponseStream : System.IO.Stream" Usage="Microsoft.Azure.Documents.Client.ResourceResponseBase.ResponseStream" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IResourceResponseBase.ResponseStream</InterfaceMember>
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
        <ReturnType>System.IO.Stream</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0a9bc-151">Azure Cosmos DB サービスからの応答の基になるストリームを取得します。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-151">Gets the underlying stream of the response from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SessionToken">
      <MemberSignature Language="C#" Value="public string SessionToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SessionToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.ResourceResponseBase.SessionToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SessionToken As String" />
      <MemberSignature Language="F#" Value="member this.SessionToken : string" Usage="Microsoft.Azure.Documents.Client.ResourceResponseBase.SessionToken" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IResourceResponseBase.SessionToken</InterfaceMember>
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
            <span data-ttu-id="0a9bc-152">セッションのトークンを取得セッション整合性読み取りで使用する Azure Cosmos DB サービスからです。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-152">Gets the session token for use in sesssion consistency reads from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="0a9bc-153">セッションで使用するためのセッション トークンです。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-153">The session token for use in session consistency.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusCode">
      <MemberSignature Language="C#" Value="public System.Net.HttpStatusCode StatusCode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Net.HttpStatusCode StatusCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.ResourceResponseBase.StatusCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StatusCode As HttpStatusCode" />
      <MemberSignature Language="F#" Value="member this.StatusCode : System.Net.HttpStatusCode" Usage="Microsoft.Azure.Documents.Client.ResourceResponseBase.StatusCode" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IResourceResponseBase.StatusCode</InterfaceMember>
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
        <ReturnType>System.Net.HttpStatusCode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0a9bc-154">Azure Cosmos DB サービスからの応答に関連付けられている HTTP ステータス コードを取得します。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-154">Gets the HTTP status code associated with the response from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="0a9bc-155">応答に関連付けられている HTTP ステータス コード。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-155">The HTTP status code associated with the response.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoredProceduresQuota">
      <MemberSignature Language="C#" Value="public long StoredProceduresQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 StoredProceduresQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.ResourceResponseBase.StoredProceduresQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StoredProceduresQuota As Long" />
      <MemberSignature Language="F#" Value="member this.StoredProceduresQuota : int64" Usage="Microsoft.Azure.Documents.Client.ResourceResponseBase.StoredProceduresQuota" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IResourceResponseBase.StoredProceduresQuota</InterfaceMember>
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
            <span data-ttu-id="0a9bc-156">Azure Cosmos DB サービスから一連のストアド プロシージャの最大クォータを取得します。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-156">Gets the maximum quota of stored procedures for a collection from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="0a9bc-157">最大クォータです。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-157">The maximum quota.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoredProceduresUsage">
      <MemberSignature Language="C#" Value="public long StoredProceduresUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 StoredProceduresUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.ResourceResponseBase.StoredProceduresUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StoredProceduresUsage As Long" />
      <MemberSignature Language="F#" Value="member this.StoredProceduresUsage : int64" Usage="Microsoft.Azure.Documents.Client.ResourceResponseBase.StoredProceduresUsage" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IResourceResponseBase.StoredProceduresUsage</InterfaceMember>
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
            <span data-ttu-id="0a9bc-158">Azure Cosmos DB サービスから一連のストアド プロシージャの現在の数を取得します。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-158">Gets the current number of stored procedures for a collection from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="0a9bc-159">現在のストアド プロシージャの数。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-159">Current number of stored procedures.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TriggersQuota">
      <MemberSignature Language="C#" Value="public long TriggersQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TriggersQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.ResourceResponseBase.TriggersQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TriggersQuota As Long" />
      <MemberSignature Language="F#" Value="member this.TriggersQuota : int64" Usage="Microsoft.Azure.Documents.Client.ResourceResponseBase.TriggersQuota" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IResourceResponseBase.TriggersQuota</InterfaceMember>
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
            <span data-ttu-id="0a9bc-160">Azure Cosmos DB サービスからコレクションのトリガーの最大クォータを取得します。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-160">Gets the maximum quota of triggers for a collection from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="0a9bc-161">最大クォータです。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-161">The maximum quota.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TriggersUsage">
      <MemberSignature Language="C#" Value="public long TriggersUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TriggersUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.ResourceResponseBase.TriggersUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TriggersUsage As Long" />
      <MemberSignature Language="F#" Value="member this.TriggersUsage : int64" Usage="Microsoft.Azure.Documents.Client.ResourceResponseBase.TriggersUsage" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IResourceResponseBase.TriggersUsage</InterfaceMember>
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
            <span data-ttu-id="0a9bc-162">Azure Cosmos DB サービスからコレクションの現在のトリガーの数を取得します。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-162">Gets the current number of triggers for a collection from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="0a9bc-163">現在のトリガーの数。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-163">Current number of triggers.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserDefinedFunctionsQuota">
      <MemberSignature Language="C#" Value="public long UserDefinedFunctionsQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 UserDefinedFunctionsQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.ResourceResponseBase.UserDefinedFunctionsQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UserDefinedFunctionsQuota As Long" />
      <MemberSignature Language="F#" Value="member this.UserDefinedFunctionsQuota : int64" Usage="Microsoft.Azure.Documents.Client.ResourceResponseBase.UserDefinedFunctionsQuota" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IResourceResponseBase.UserDefinedFunctionsQuota</InterfaceMember>
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
            <span data-ttu-id="0a9bc-164">Azure Cosmos DB サービスからコレクションのユーザー定義関数の最大クォータを取得します。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-164">Gets the maximum quota of user defined functions for a collection from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="0a9bc-165">最大クォータです。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-165">The maximum quota.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserDefinedFunctionsUsage">
      <MemberSignature Language="C#" Value="public long UserDefinedFunctionsUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 UserDefinedFunctionsUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.ResourceResponseBase.UserDefinedFunctionsUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UserDefinedFunctionsUsage As Long" />
      <MemberSignature Language="F#" Value="member this.UserDefinedFunctionsUsage : int64" Usage="Microsoft.Azure.Documents.Client.ResourceResponseBase.UserDefinedFunctionsUsage" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IResourceResponseBase.UserDefinedFunctionsUsage</InterfaceMember>
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
            <span data-ttu-id="0a9bc-166">Azure Cosmos DB サービスからコレクションの現在のユーザー定義関数の数を取得します。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-166">Gets the current number of user defined functions for a collection from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="0a9bc-167">ユーザーの現在の数は、関数を定義します。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-167">Current number of user defined functions.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserQuota">
      <MemberSignature Language="C#" Value="public long UserQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 UserQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.ResourceResponseBase.UserQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UserQuota As Long" />
      <MemberSignature Language="F#" Value="member this.UserQuota : int64" Usage="Microsoft.Azure.Documents.Client.ResourceResponseBase.UserQuota" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IResourceResponseBase.UserQuota</InterfaceMember>
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
            <span data-ttu-id="0a9bc-168">Azure Cosmos DB サービスから、アカウント内のユーザー リソースの最大クォータを取得します。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-168">Gets the maximum quota for user resources within an account from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="0a9bc-169">アカウントの最大クォータです。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-169">The maximum quota for the account.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserUsage">
      <MemberSignature Language="C#" Value="public long UserUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 UserUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.ResourceResponseBase.UserUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UserUsage As Long" />
      <MemberSignature Language="F#" Value="member this.UserUsage : int64" Usage="Microsoft.Azure.Documents.Client.ResourceResponseBase.UserUsage" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IResourceResponseBase.UserUsage</InterfaceMember>
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
            <span data-ttu-id="0a9bc-170">Azure Cosmos DB サービスから、アカウント内のユーザー リソースの現在の数を取得します。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-170">Gets the current number of user resources within the account from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="0a9bc-171">ユーザーの数。</span><span class="sxs-lookup"><span data-stu-id="0a9bc-171">The number of users.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>