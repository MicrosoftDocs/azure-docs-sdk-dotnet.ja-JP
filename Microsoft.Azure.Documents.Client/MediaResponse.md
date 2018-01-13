<Type Name="MediaResponse" FullName="Microsoft.Azure.Documents.Client.MediaResponse">
  <TypeSignature Language="C#" Value="public sealed class MediaResponse : Microsoft.Azure.Documents.Client.IMediaResponse" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit MediaResponse extends System.Object implements class Microsoft.Azure.Documents.Client.IMediaResponse" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Client.MediaResponse" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class MediaResponse&#xA;Implements IMediaResponse" />
  <TypeSignature Language="F#" Value="type MediaResponse = class&#xA;    interface IMediaResponse" />
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
      <InterfaceName>Microsoft.Azure.Documents.Client.IMediaResponse</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="7d352-101">Azure Cosmos DB サービスから添付ファイルのコンテンツを取得中に関連付けられた応答を表します。</span><span class="sxs-lookup"><span data-stu-id="7d352-101">Represents the response associated with retrieving attachment content from the Azure Cosmos DB service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MediaResponse ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.MediaResponse.#ctor" />
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
            <span data-ttu-id="7d352-102">Azure Cosmos DB サービスの目的をモックに公開されているコンス トラクターです。</span><span class="sxs-lookup"><span data-stu-id="7d352-102">Constructor exposed for mocking purposes for the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActivityId">
      <MemberSignature Language="C#" Value="public string ActivityId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ActivityId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.MediaResponse.ActivityId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActivityId As String" />
      <MemberSignature Language="F#" Value="member this.ActivityId : string" Usage="Microsoft.Azure.Documents.Client.MediaResponse.ActivityId" />
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
            <span data-ttu-id="7d352-103">取得または Azure Cosmos DB サービスの要求のアクティビティ ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="7d352-103">Gets or sets the Activity ID for the request in the Azure Cosmos DB service.</span></span>
            </summary>
        <value><span data-ttu-id="7d352-104">要求のアクティビティ ID。</span><span class="sxs-lookup"><span data-stu-id="7d352-104">The Activity ID for the request.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentLength">
      <MemberSignature Language="C#" Value="public long ContentLength { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ContentLength" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.MediaResponse.ContentLength" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContentLength As Long" />
      <MemberSignature Language="F#" Value="member this.ContentLength : int64" Usage="Microsoft.Azure.Documents.Client.MediaResponse.ContentLength" />
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
            <span data-ttu-id="7d352-105">取得または Azure Cosmos DB サービスの HTTP ContentLength ヘッダーの値を設定します。</span><span class="sxs-lookup"><span data-stu-id="7d352-105">Gets or sets the HTTP ContentLength header value in the Azure Cosmos DB service.</span></span>
            </summary>
        <value><span data-ttu-id="7d352-106">HTTP ContentLength ヘッダーの値。</span><span class="sxs-lookup"><span data-stu-id="7d352-106">The HTTP ContentLength header value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentType">
      <MemberSignature Language="C#" Value="public string ContentType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.MediaResponse.ContentType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContentType As String" />
      <MemberSignature Language="F#" Value="member this.ContentType : string" Usage="Microsoft.Azure.Documents.Client.MediaResponse.ContentType" />
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
            <span data-ttu-id="7d352-107">取得または Azure Cosmos DB サービスの HTTP ContentType ヘッダーの値を設定します。</span><span class="sxs-lookup"><span data-stu-id="7d352-107">Gets or sets the HTTP ContentType header value in the Azure Cosmos DB service.</span></span>
            </summary>
        <value><span data-ttu-id="7d352-108">HTTP コンテンツ タイプ ヘッダーの値。</span><span class="sxs-lookup"><span data-stu-id="7d352-108">The HTTP ContentType header value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentMediaStorageUsageInMB">
      <MemberSignature Language="C#" Value="public long CurrentMediaStorageUsageInMB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 CurrentMediaStorageUsageInMB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.MediaResponse.CurrentMediaStorageUsageInMB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentMediaStorageUsageInMB As Long" />
      <MemberSignature Language="F#" Value="member this.CurrentMediaStorageUsageInMB : int64" Usage="Microsoft.Azure.Documents.Client.MediaResponse.CurrentMediaStorageUsageInMB" />
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
            <span data-ttu-id="7d352-109">添付ファイル コンテンツ (メディア) の現在の使用量をメガバイト単位で Azure Cosmos DB サービスから取得します。</span><span class="sxs-lookup"><span data-stu-id="7d352-109">Gets the current attachment content (media) usage in megabytes from the Azure Cosmos DB service.</span></span>
            </summary>
        <value><span data-ttu-id="7d352-110">現在の添付ファイル コンテンツ (メディア) 使用量 (メガバイト単位)。</span><span class="sxs-lookup"><span data-stu-id="7d352-110">The current attachment content (media) usage in megabytes.</span></span></value>
        <remarks><span data-ttu-id="7d352-111">この値は、ゲートウェイから取得されます。</span><span class="sxs-lookup"><span data-stu-id="7d352-111">This value is retrieved from the gateway.</span></span>
            <span data-ttu-id="7d352-112">値は、定期的に更新情報をキャッシュから返され、リアルタイムであるとは限りません。</span><span class="sxs-lookup"><span data-stu-id="7d352-112">The value is returned from cached information updated periodically and is not guaranteed to be real time.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxMediaStorageUsageInMB">
      <MemberSignature Language="C#" Value="public long MaxMediaStorageUsageInMB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxMediaStorageUsageInMB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.MediaResponse.MaxMediaStorageUsageInMB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxMediaStorageUsageInMB As Long" />
      <MemberSignature Language="F#" Value="member this.MaxMediaStorageUsageInMB : int64" Usage="Microsoft.Azure.Documents.Client.MediaResponse.MaxMediaStorageUsageInMB" />
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
            <span data-ttu-id="7d352-113">添付ファイルのコンテンツ (メディア) を取得する Azure Cosmos DB サービスから、メガバイト単位での記憶域のクォータ。</span><span class="sxs-lookup"><span data-stu-id="7d352-113">Gets the attachment content (media) storage quota in megabytes from the Azure Cosmos DB service.</span></span>
            <span data-ttu-id="7d352-114">ゲートウェイから取得されます。</span><span class="sxs-lookup"><span data-stu-id="7d352-114">Retrieved from gateway.</span></span>
            </summary>
        <value><span data-ttu-id="7d352-115">添付ファイルのコンテンツ (メディア) 記憶域のクォータ (メガバイト単位)。</span><span class="sxs-lookup"><span data-stu-id="7d352-115">The attachment content (media) storage quota in megabytes.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Media">
      <MemberSignature Language="C#" Value="public System.IO.Stream Media { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.IO.Stream Media" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.MediaResponse.Media" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Media As Stream" />
      <MemberSignature Language="F#" Value="member this.Media : System.IO.Stream" Usage="Microsoft.Azure.Documents.Client.MediaResponse.Media" />
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
        <ReturnType>System.IO.Stream</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7d352-116">取得または Azure Cosmos DB サービスの添付ファイルのコンテンツ ストリームを設定します。</span><span class="sxs-lookup"><span data-stu-id="7d352-116">Gets or sets the attachment content stream in the Azure Cosmos DB service.</span></span>
            </summary>
        <value><span data-ttu-id="7d352-117">添付ファイルのコンテンツ ストリーム。</span><span class="sxs-lookup"><span data-stu-id="7d352-117">The attachment content stream.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResponseHeaders">
      <MemberSignature Language="C#" Value="public System.Collections.Specialized.NameValueCollection ResponseHeaders { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Specialized.NameValueCollection ResponseHeaders" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.MediaResponse.ResponseHeaders" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResponseHeaders As NameValueCollection" />
      <MemberSignature Language="F#" Value="member this.ResponseHeaders : System.Collections.Specialized.NameValueCollection" Usage="Microsoft.Azure.Documents.Client.MediaResponse.ResponseHeaders" />
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
            <span data-ttu-id="7d352-118">Azure Cosmos DB サービスからの応答に関連付けられたヘッダーを取得します。</span><span class="sxs-lookup"><span data-stu-id="7d352-118">Gets the headers associated with the response from the Azure Cosmos DB service.</span></span>
            </summary>
        <value><span data-ttu-id="7d352-119">応答に関連付けられたヘッダー。</span><span class="sxs-lookup"><span data-stu-id="7d352-119">The headers associated with the response.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Slug">
      <MemberSignature Language="C#" Value="public string Slug { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Slug" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.MediaResponse.Slug" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Slug As String" />
      <MemberSignature Language="F#" Value="member this.Slug : string" Usage="Microsoft.Azure.Documents.Client.MediaResponse.Slug" />
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
            <span data-ttu-id="7d352-120">取得または Azure Cosmos DB サービスの HTTP slug ヘッダーの値を設定します。</span><span class="sxs-lookup"><span data-stu-id="7d352-120">Gets or sets the HTTP slug header value in the Azure Cosmos DB service.</span></span>
            </summary>
        <value><span data-ttu-id="7d352-121">HTTP slug ヘッダーの値。</span><span class="sxs-lookup"><span data-stu-id="7d352-121">The HTTP slug header value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>