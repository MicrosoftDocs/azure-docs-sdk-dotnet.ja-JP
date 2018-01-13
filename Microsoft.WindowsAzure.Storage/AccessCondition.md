<Type Name="AccessCondition" FullName="Microsoft.WindowsAzure.Storage.AccessCondition">
  <TypeSignature Language="C#" Value="public sealed class AccessCondition" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit AccessCondition extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.AccessCondition" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class AccessCondition" />
  <TypeSignature Language="F#" Value="type AccessCondition = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="136cb-101">ストレージ サービスに対して操作をするためのアクセス条件のセットを表します。</span><span class="sxs-lookup"><span data-stu-id="136cb-101">Represents a set of access conditions to be used for operations against the storage services.</span></span> 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AccessCondition ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.AccessCondition.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.AccessCondition Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.AccessCondition Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.AccessCondition.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Function Clone () As AccessCondition" />
      <MemberSignature Language="F#" Value="member this.Clone : unit -&gt; Microsoft.WindowsAzure.Storage.AccessCondition" Usage="accessCondition.Clone " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="136cb-102">現在のアクセス条件の簡易コピーを提供します。</span><span class="sxs-lookup"><span data-stu-id="136cb-102">Provide a shallow copy of the current access condition</span></span>
            </summary>
        <returns><span data-ttu-id="136cb-103">簡易コピー、<see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />オブジェクト</span><span class="sxs-lookup"><span data-stu-id="136cb-103">A shallow copy of the <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateEmptyCondition">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.AccessCondition GenerateEmptyCondition ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.AccessCondition GenerateEmptyCondition() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateEmptyCondition" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateEmptyCondition () As AccessCondition" />
      <MemberSignature Language="F#" Value="static member GenerateEmptyCondition : unit -&gt; Microsoft.WindowsAzure.Storage.AccessCondition" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.GenerateEmptyCondition " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="136cb-104">空のアクセス条件を構築します。</span><span class="sxs-lookup"><span data-stu-id="136cb-104">Constructs an empty access condition.</span></span>
            </summary>
        <returns><span data-ttu-id="136cb-105">空の <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="136cb-105">An empty <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateIfAppendPositionEqualCondition">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfAppendPositionEqualCondition (long appendPosition);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfAppendPositionEqualCondition(int64 appendPosition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfAppendPositionEqualCondition(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateIfAppendPositionEqualCondition (appendPosition As Long) As AccessCondition" />
      <MemberSignature Language="F#" Value="static member GenerateIfAppendPositionEqualCondition : int64 -&gt; Microsoft.WindowsAzure.Storage.AccessCondition" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfAppendPositionEqualCondition appendPosition" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appendPosition" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="appendPosition"><span data-ttu-id="136cb-106">Blob の現在の終了位置と比較するオフセットを指定する整数。</span><span class="sxs-lookup"><span data-stu-id="136cb-106">An integer specifying the offset to compare to the current end position of the blob.</span></span></param>
        <summary>
            <span data-ttu-id="136cb-107">追加 blob の末尾の位置が指定した値に等しい場合にのみ操作が実行されるように、アクセス条件を構築します。</span><span class="sxs-lookup"><span data-stu-id="136cb-107">Constructs an access condition such that an operation will be performed only if the end position of the append blob is equal to the specified value.</span></span>
            </summary>
        <returns><span data-ttu-id="136cb-108"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />を比較するオフセットを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="136cb-108">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the offset to compare.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateIfExistsCondition">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfExistsCondition ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfExistsCondition() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfExistsCondition" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateIfExistsCondition () As AccessCondition" />
      <MemberSignature Language="F#" Value="static member GenerateIfExistsCondition : unit -&gt; Microsoft.WindowsAzure.Storage.AccessCondition" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfExistsCondition " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="136cb-109">リソースが存在する場合にのみ操作が実行されるように、アクセス条件を構築します。</span><span class="sxs-lookup"><span data-stu-id="136cb-109">Constructs an access condition such that an operation will be performed only if the resource exists.</span></span>
            </summary>
        <returns><span data-ttu-id="136cb-110"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />リソースが存在する条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="136cb-110">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents a condition where a resource exists.</span></span></returns>
        <remarks><span data-ttu-id="136cb-111">このアクセス条件を設定を含める HTTP 要求を変更<i>If-match</i>条件ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="136cb-111">Setting this access condition modifies the request to include the HTTP <i>If-Match</i> conditional header.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateIfMatchCondition">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfMatchCondition (string etag);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfMatchCondition(string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfMatchCondition(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateIfMatchCondition (etag As String) As AccessCondition" />
      <MemberSignature Language="F#" Value="static member GenerateIfMatchCondition : string -&gt; Microsoft.WindowsAzure.Storage.AccessCondition" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfMatchCondition etag" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="etag"><span data-ttu-id="136cb-112">リソースの ETag と照合する ETag 値です。</span><span class="sxs-lookup"><span data-stu-id="136cb-112">The ETag value to check against the resource's ETag.</span></span></param>
        <summary>
            <span data-ttu-id="136cb-113">リソースの ETag 値が指定された ETag 値と一致する場合にのみ操作が実行されるように、アクセス条件を構築します。</span><span class="sxs-lookup"><span data-stu-id="136cb-113">Constructs an access condition such that an operation will be performed only if the resource's ETag value matches the specified ETag value.</span></span>
            </summary>
        <returns><span data-ttu-id="136cb-114"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> If-match 条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="136cb-114">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the If-Match condition.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateIfMaxSizeLessThanOrEqualCondition">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfMaxSizeLessThanOrEqualCondition (long maxSize);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfMaxSizeLessThanOrEqualCondition(int64 maxSize) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfMaxSizeLessThanOrEqualCondition(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateIfMaxSizeLessThanOrEqualCondition (maxSize As Long) As AccessCondition" />
      <MemberSignature Language="F#" Value="static member GenerateIfMaxSizeLessThanOrEqualCondition : int64 -&gt; Microsoft.WindowsAzure.Storage.AccessCondition" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfMaxSizeLessThanOrEqualCondition maxSize" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxSize" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="maxSize"><span data-ttu-id="136cb-115">新しいブロックをコミットするときは、(バイト単位)、blob の最大許容サイズを指定する整数。</span><span class="sxs-lookup"><span data-stu-id="136cb-115">An integer specifying the maximum allowed size of the blob, in bytes, when committing a new block.</span></span></param>
        <summary>
            <span data-ttu-id="136cb-116">ブロックをコミットした後に、追加 blob のサイズは、指定した値に等しいまたはそれよりも小さい場合にのみ操作が実行されるように、アクセス条件を構築します。</span><span class="sxs-lookup"><span data-stu-id="136cb-116">Constructs an access condition such that an operation will be performed only if the size of the append blob after committing the block is less than or equal to the specified value.</span></span>
            </summary>
        <returns><span data-ttu-id="136cb-117"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />最大許容サイズを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="136cb-117">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the maximum allowed size.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateIfModifiedSinceCondition">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfModifiedSinceCondition (DateTimeOffset modifiedTime);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfModifiedSinceCondition(valuetype System.DateTimeOffset modifiedTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfModifiedSinceCondition(System.DateTimeOffset)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateIfModifiedSinceCondition (modifiedTime As DateTimeOffset) As AccessCondition" />
      <MemberSignature Language="F#" Value="static member GenerateIfModifiedSinceCondition : DateTimeOffset -&gt; Microsoft.WindowsAzure.Storage.AccessCondition" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfModifiedSinceCondition modifiedTime" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="modifiedTime" Type="System.DateTimeOffset" />
      </Parameters>
      <Docs>
        <param name="modifiedTime"><span data-ttu-id="136cb-118">A<see cref="T:System.DateTimeOffset" />以降、リソース変更された時間を指定する値。</span><span class="sxs-lookup"><span data-stu-id="136cb-118">A <see cref="T:System.DateTimeOffset" /> value specifying the time since which the resource must have been modified.</span></span></param>
        <summary>
            <span data-ttu-id="136cb-119">指定した時刻以降にリソースが変更された場合にのみ操作が実行されるように、アクセス条件を構築します。</span><span class="sxs-lookup"><span data-stu-id="136cb-119">Constructs an access condition such that an operation will be performed only if the resource has been modified since the specified time.</span></span>
            </summary>
        <returns><span data-ttu-id="136cb-120"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />場合-変更のための条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="136cb-120">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the If-Modified-Since condition.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateIfNoneMatchCondition">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfNoneMatchCondition (string etag);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfNoneMatchCondition(string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNoneMatchCondition(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateIfNoneMatchCondition (etag As String) As AccessCondition" />
      <MemberSignature Language="F#" Value="static member GenerateIfNoneMatchCondition : string -&gt; Microsoft.WindowsAzure.Storage.AccessCondition" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNoneMatchCondition etag" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="etag"><span data-ttu-id="136cb-121">リソースの ETag と照合する ETag 値または<c>"\*"</c>リソースが存在しないことを要求します。</span><span class="sxs-lookup"><span data-stu-id="136cb-121">The ETag value to check against the resource's ETag, or <c>"\*"</c> to require that the resource does not exist.</span></span></param>
        <summary>
            <span data-ttu-id="136cb-122">リソースの ETag 値が指定された ETag 値に一致しない場合にのみ操作が実行されるように、アクセス条件を構築します。</span><span class="sxs-lookup"><span data-stu-id="136cb-122">Constructs an access condition such that an operation will be performed only if the resource's ETag value does not match the specified ETag value.</span></span>
            </summary>
        <returns><span data-ttu-id="136cb-123"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />なし-If-match 条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="136cb-123">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the If-None-Match condition.</span></span></returns>
        <remarks>
            <span data-ttu-id="136cb-124">場合<c>"\*"</c>が指定されて、<paramref name="etag" />パラメーターをこの条件は、リソースが存在しないことが必要です。</span><span class="sxs-lookup"><span data-stu-id="136cb-124">If <c>"\*"</c> is specified for the <paramref name="etag" /> parameter, then this condition requires that the resource does not exist.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateIfNotExistsCondition">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfNotExistsCondition ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfNotExistsCondition() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateIfNotExistsCondition () As AccessCondition" />
      <MemberSignature Language="F#" Value="static member GenerateIfNotExistsCondition : unit -&gt; Microsoft.WindowsAzure.Storage.AccessCondition" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="136cb-125">リソースが存在しない場合にのみ操作が実行されるように、アクセス条件を構築します。</span><span class="sxs-lookup"><span data-stu-id="136cb-125">Constructs an access condition such that an operation will be performed only if the resource does not exist.</span></span>
            </summary>
        <returns><span data-ttu-id="136cb-126"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />リソースが存在しない場合、条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="136cb-126">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents a condition where a resource does not exist.</span></span></returns>
        <remarks><span data-ttu-id="136cb-127">このアクセス条件を設定を含める HTTP 要求を変更<i>なし-If-match</i>条件ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="136cb-127">Setting this access condition modifies the request to include the HTTP <i>If-None-Match</i> conditional header.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateIfNotModifiedSinceCondition">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfNotModifiedSinceCondition (DateTimeOffset modifiedTime);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfNotModifiedSinceCondition(valuetype System.DateTimeOffset modifiedTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotModifiedSinceCondition(System.DateTimeOffset)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateIfNotModifiedSinceCondition (modifiedTime As DateTimeOffset) As AccessCondition" />
      <MemberSignature Language="F#" Value="static member GenerateIfNotModifiedSinceCondition : DateTimeOffset -&gt; Microsoft.WindowsAzure.Storage.AccessCondition" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotModifiedSinceCondition modifiedTime" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="modifiedTime" Type="System.DateTimeOffset" />
      </Parameters>
      <Docs>
        <param name="modifiedTime"><span data-ttu-id="136cb-128">A<see cref="T:System.DateTimeOffset" />以降、リソース必要がありますが変更されていない時刻を指定する値。</span><span class="sxs-lookup"><span data-stu-id="136cb-128">A <see cref="T:System.DateTimeOffset" /> value specifying the time since which the resource must not have been modified.</span></span></param>
        <summary>
            <span data-ttu-id="136cb-129">指定した時刻以降、リソースが変更されていない場合にのみ操作が実行されるように、アクセス条件を構築します。</span><span class="sxs-lookup"><span data-stu-id="136cb-129">Constructs an access condition such that an operation will be performed only if the resource has not been modified since the specified time.</span></span>
            </summary>
        <returns><span data-ttu-id="136cb-130"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />場合は、未変更の状態-以降条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="136cb-130">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the If-Unmodified-Since condition.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateIfSequenceNumberEqualCondition">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfSequenceNumberEqualCondition (long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfSequenceNumberEqualCondition(int64 sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfSequenceNumberEqualCondition(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateIfSequenceNumberEqualCondition (sequenceNumber As Long) As AccessCondition" />
      <MemberSignature Language="F#" Value="static member GenerateIfSequenceNumberEqualCondition : int64 -&gt; Microsoft.WindowsAzure.Storage.AccessCondition" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfSequenceNumberEqualCondition sequenceNumber" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="sequenceNumber"><span data-ttu-id="136cb-131">現在のシーケンス番号と比較する値。</span><span class="sxs-lookup"><span data-stu-id="136cb-131">The value to compare to the current sequence number.</span></span></param>
        <summary>
            <span data-ttu-id="136cb-132">リソースの現在のシーケンス番号が指定した値に等しい場合にのみ操作が実行されるように、アクセス条件を構築します。</span><span class="sxs-lookup"><span data-stu-id="136cb-132">Constructs an access condition such that an operation will be performed only if resource's current sequence number is equal to the specified value.</span></span>
            </summary>
        <returns><span data-ttu-id="136cb-133"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />場合にシーケンス番号 EQ 条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="136cb-133">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the If-Sequence-Number-EQ condition.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateIfSequenceNumberLessThanCondition">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfSequenceNumberLessThanCondition (long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfSequenceNumberLessThanCondition(int64 sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfSequenceNumberLessThanCondition(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateIfSequenceNumberLessThanCondition (sequenceNumber As Long) As AccessCondition" />
      <MemberSignature Language="F#" Value="static member GenerateIfSequenceNumberLessThanCondition : int64 -&gt; Microsoft.WindowsAzure.Storage.AccessCondition" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfSequenceNumberLessThanCondition sequenceNumber" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="sequenceNumber"><span data-ttu-id="136cb-134">現在のシーケンス番号と比較する値。</span><span class="sxs-lookup"><span data-stu-id="136cb-134">The value to compare to the current sequence number.</span></span></param>
        <summary>
            <span data-ttu-id="136cb-135">リソースの現在のシーケンス番号が指定された値より小さい場合にのみ操作が実行されるように、アクセス条件を構築します。</span><span class="sxs-lookup"><span data-stu-id="136cb-135">Constructs an access condition such that an operation will be performed only if resource's current sequence number is less than the specified value.</span></span>
            </summary>
        <returns><span data-ttu-id="136cb-136"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />場合にシーケンス番号 LT 条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="136cb-136">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the If-Sequence-Number-LT condition.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateIfSequenceNumberLessThanOrEqualCondition">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfSequenceNumberLessThanOrEqualCondition (long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfSequenceNumberLessThanOrEqualCondition(int64 sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfSequenceNumberLessThanOrEqualCondition(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateIfSequenceNumberLessThanOrEqualCondition (sequenceNumber As Long) As AccessCondition" />
      <MemberSignature Language="F#" Value="static member GenerateIfSequenceNumberLessThanOrEqualCondition : int64 -&gt; Microsoft.WindowsAzure.Storage.AccessCondition" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfSequenceNumberLessThanOrEqualCondition sequenceNumber" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="sequenceNumber"><span data-ttu-id="136cb-137">現在のシーケンス番号と比較する値。</span><span class="sxs-lookup"><span data-stu-id="136cb-137">The value to compare to the current sequence number.</span></span></param>
        <summary>
            <span data-ttu-id="136cb-138">リソースの現在のシーケンス番号が指定した値に等しいまたはそれよりも小さい場合にのみ操作が実行されるように、アクセス条件を構築します。</span><span class="sxs-lookup"><span data-stu-id="136cb-138">Constructs an access condition such that an operation will be performed only if resource's current sequence number is less than or equal to the specified value.</span></span>
            </summary>
        <returns><span data-ttu-id="136cb-139"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />場合にシーケンス番号 LE 条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="136cb-139">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the If-Sequence-Number-LE condition.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateLeaseCondition">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.AccessCondition GenerateLeaseCondition (string leaseId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.AccessCondition GenerateLeaseCondition(string leaseId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateLeaseCondition(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateLeaseCondition (leaseId As String) As AccessCondition" />
      <MemberSignature Language="F#" Value="static member GenerateLeaseCondition : string -&gt; Microsoft.WindowsAzure.Storage.AccessCondition" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.GenerateLeaseCondition leaseId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="leaseId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="leaseId"><span data-ttu-id="136cb-140">リソースのリース ID と比較するリース ID です。</span><span class="sxs-lookup"><span data-stu-id="136cb-140">The lease ID to compare to the lease ID of the resource.</span></span></param>
        <summary>
            <span data-ttu-id="136cb-141">リソースのリース ID が指定されたリース ID と一致する場合にのみ操作が実行されるように、アクセス条件を作成します。</span><span class="sxs-lookup"><span data-stu-id="136cb-141">Constructs an access condition such that an operation will be performed only if the lease ID on the resource matches the specified lease ID.</span></span>
            </summary>
        <returns><span data-ttu-id="136cb-142"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />リース条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="136cb-142">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the lease condition.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IfAppendPositionEqual">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; IfAppendPositionEqual { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; IfAppendPositionEqual" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.AccessCondition.IfAppendPositionEqual" />
      <MemberSignature Language="VB.NET" Value="Public Property IfAppendPositionEqual As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.IfAppendPositionEqual : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.IfAppendPositionEqual" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="136cb-143">取得または追加 blob にブロックをコミットするときにチェックするバイト オフセットを指定する条件の値を設定します。</span><span class="sxs-lookup"><span data-stu-id="136cb-143">Gets or sets a value for a condition specifying the byte offset to check for when committing a block to an append blob.</span></span>
            <span data-ttu-id="136cb-144">この追加は、終了位置がこの値に等しい場合にのみ成功します。</span><span class="sxs-lookup"><span data-stu-id="136cb-144">The append will succeed only if the end position is equal to this number.</span></span> 
            </summary>
        <value><span data-ttu-id="136cb-145">追加の位置の番号の場合、または<c>null</c>値が設定されていない場合。</span><span class="sxs-lookup"><span data-stu-id="136cb-145">An append position number, or <c>null</c> if no value is set.</span></span></value>
        <remarks><span data-ttu-id="136cb-146">この条件は、追加 blob にのみ適用されます。</span><span class="sxs-lookup"><span data-stu-id="136cb-146">This condition only applies to append blobs.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="IfMatchETag">
      <MemberSignature Language="C#" Value="public string IfMatchETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IfMatchETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.AccessCondition.IfMatchETag" />
      <MemberSignature Language="VB.NET" Value="Public Property IfMatchETag As String" />
      <MemberSignature Language="F#" Value="member this.IfMatchETag : string with get, set" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.IfMatchETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="136cb-147">取得または指定した ETag と一致するが、指定されたリソースの ETag を指定する条件の ETag 値を設定します。</span><span class="sxs-lookup"><span data-stu-id="136cb-147">Gets or sets an ETag value for a condition specifying that the given ETag must match the ETag of the specified resource.</span></span>
            </summary>
        <value><span data-ttu-id="136cb-148">ETag 値を含む文字列または<c>"\*"</c>任意の ETag が一致するようにします。</span><span class="sxs-lookup"><span data-stu-id="136cb-148">A string containing an ETag value, or <c>"\*"</c> to match any ETag.</span></span> <span data-ttu-id="136cb-149">場合<c>null</c>条件が存在しません。</span><span class="sxs-lookup"><span data-stu-id="136cb-149">If <c>null</c>, no condition exists.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IfMaxSizeLessThanOrEqual">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; IfMaxSizeLessThanOrEqual { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; IfMaxSizeLessThanOrEqual" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.AccessCondition.IfMaxSizeLessThanOrEqual" />
      <MemberSignature Language="VB.NET" Value="Public Property IfMaxSizeLessThanOrEqual As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.IfMaxSizeLessThanOrEqual : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.IfMaxSizeLessThanOrEqual" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="136cb-150">取得または新しいブロックがコミットされるときに、追加 blob の許容される最大サイズを指定する条件の値を設定します。</span><span class="sxs-lookup"><span data-stu-id="136cb-150">Gets or sets a value for a condition that specifies the maximum size allowed for an append blob when a new block is committed.</span></span> <span data-ttu-id="136cb-151">この追加は、追加操作の後に blob のサイズが指定されたサイズに等しいまたはそれよりも小さい場合にのみ成功します。</span><span class="sxs-lookup"><span data-stu-id="136cb-151">The append will succeed only if the size of the blob after the append operation is less than or equal to the specified size.</span></span>
            </summary>
        <value><span data-ttu-id="136cb-152">最大サイズ (バイト単位) または<c>null</c>値が設定されていない場合。</span><span class="sxs-lookup"><span data-stu-id="136cb-152">The maximum size in bytes, or <c>null</c> if no value is set.</span></span></value>
        <remarks><span data-ttu-id="136cb-153">この条件は、追加 blob にのみ適用されます。</span><span class="sxs-lookup"><span data-stu-id="136cb-153">This condition only applies to append blobs.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="IfModifiedSinceTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; IfModifiedSinceTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; IfModifiedSinceTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.AccessCondition.IfModifiedSinceTime" />
      <MemberSignature Language="VB.NET" Value="Public Property IfModifiedSinceTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.IfModifiedSinceTime : Nullable&lt;DateTimeOffset&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.IfModifiedSinceTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="136cb-154">取得または設定、<see cref="T:System.DateTimeOffset" />以降、リソースが変更された時刻を指定する条件の値。</span><span class="sxs-lookup"><span data-stu-id="136cb-154">Gets or sets a <see cref="T:System.DateTimeOffset" /> value for a condition specifying a time since which a resource has been modified.</span></span>
            </summary>
        <value><span data-ttu-id="136cb-155">A <see cref="T:System.DateTimeOffset" /> (UTC) で指定された値または<c>null</c>条件が存在しない場合。</span><span class="sxs-lookup"><span data-stu-id="136cb-155">A <see cref="T:System.DateTimeOffset" /> value specified in UTC, or <c>null</c> if no condition exists.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IfNoneMatchETag">
      <MemberSignature Language="C#" Value="public string IfNoneMatchETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IfNoneMatchETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.AccessCondition.IfNoneMatchETag" />
      <MemberSignature Language="VB.NET" Value="Public Property IfNoneMatchETag As String" />
      <MemberSignature Language="F#" Value="member this.IfNoneMatchETag : string with get, set" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.IfNoneMatchETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="136cb-156">取得または指定した ETag が、指定したリソースの ETag と一致する必要がありますを指定する条件の ETag 値を設定します。</span><span class="sxs-lookup"><span data-stu-id="136cb-156">Gets or sets an ETag value for a condition specifying that the given ETag must not match the ETag of the specified resource.</span></span>
            </summary>
        <value><span data-ttu-id="136cb-157">ETag 値を含む文字列または<c>"\*"</c>任意の ETag が一致するようにします。</span><span class="sxs-lookup"><span data-stu-id="136cb-157">A string containing an ETag value, or <c>"\*"</c> to match any ETag.</span></span> <span data-ttu-id="136cb-158">場合<c>null</c>条件が存在しません。</span><span class="sxs-lookup"><span data-stu-id="136cb-158">If <c>null</c>, no condition exists.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IfNotModifiedSinceTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; IfNotModifiedSinceTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; IfNotModifiedSinceTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.AccessCondition.IfNotModifiedSinceTime" />
      <MemberSignature Language="VB.NET" Value="Public Property IfNotModifiedSinceTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.IfNotModifiedSinceTime : Nullable&lt;DateTimeOffset&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.IfNotModifiedSinceTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="136cb-159">取得または設定、<see cref="T:System.DateTimeOffset" />以降、リソースが変更されていない時間を指定する条件の値。</span><span class="sxs-lookup"><span data-stu-id="136cb-159">Gets or sets a <see cref="T:System.DateTimeOffset" /> value for a condition specifying a time since which a resource has not been modified.</span></span>
            </summary>
        <value><span data-ttu-id="136cb-160">A <see cref="T:System.DateTimeOffset" /> (UTC) で指定された値または<c>null</c>条件が存在しない場合。</span><span class="sxs-lookup"><span data-stu-id="136cb-160">A <see cref="T:System.DateTimeOffset" /> value specified in UTC, or <c>null</c> if no condition exists.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IfSequenceNumberEqual">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; IfSequenceNumberEqual { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; IfSequenceNumberEqual" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.AccessCondition.IfSequenceNumberEqual" />
      <MemberSignature Language="VB.NET" Value="Public Property IfSequenceNumberEqual As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.IfSequenceNumberEqual : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.IfSequenceNumberEqual" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="136cb-161">取得または現在のシーケンス番号が指定された値と同じにする必要がありますを指定する条件の値を設定します。</span><span class="sxs-lookup"><span data-stu-id="136cb-161">Gets or sets a value for a condition specifying that the current sequence number must be equal to the specified value.</span></span>
            </summary>
        <value><span data-ttu-id="136cb-162">シーケンス番号、または<c>null</c>条件が存在しない場合。</span><span class="sxs-lookup"><span data-stu-id="136cb-162">A sequence number, or <c>null</c> if no condition exists.</span></span></value>
        <remarks><span data-ttu-id="136cb-163">この条件は、ページ blob にのみ適用されます。</span><span class="sxs-lookup"><span data-stu-id="136cb-163">This condition only applies to page blobs.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="IfSequenceNumberLessThan">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; IfSequenceNumberLessThan { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; IfSequenceNumberLessThan" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.AccessCondition.IfSequenceNumberLessThan" />
      <MemberSignature Language="VB.NET" Value="Public Property IfSequenceNumberLessThan As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.IfSequenceNumberLessThan : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.IfSequenceNumberLessThan" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="136cb-164">取得または現在のシーケンス番号が指定した値より小さくなければならないことを指定する条件の値を設定します。</span><span class="sxs-lookup"><span data-stu-id="136cb-164">Gets or sets a value for a condition specifying that the current sequence number must be less than the specified value.</span></span>
            </summary>
        <value><span data-ttu-id="136cb-165">シーケンス番号、または<c>null</c>条件が存在しない場合。</span><span class="sxs-lookup"><span data-stu-id="136cb-165">A sequence number, or <c>null</c> if no condition exists.</span></span></value>
        <remarks><span data-ttu-id="136cb-166">この条件は、ページ blob にのみ適用されます。</span><span class="sxs-lookup"><span data-stu-id="136cb-166">This condition only applies to page blobs.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="IfSequenceNumberLessThanOrEqual">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; IfSequenceNumberLessThanOrEqual { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; IfSequenceNumberLessThanOrEqual" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.AccessCondition.IfSequenceNumberLessThanOrEqual" />
      <MemberSignature Language="VB.NET" Value="Public Property IfSequenceNumberLessThanOrEqual As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.IfSequenceNumberLessThanOrEqual : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.IfSequenceNumberLessThanOrEqual" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="136cb-167">取得または設定を指定する条件の値であり、現在のシーケンス番号は、指定された値以下である必要があります。</span><span class="sxs-lookup"><span data-stu-id="136cb-167">Gets or sets a value for a condition specifying that the current sequence number must be less than or equal to the specified value.</span></span>
            </summary>
        <value><span data-ttu-id="136cb-168">シーケンス番号、または<c>null</c>条件が存在しない場合。</span><span class="sxs-lookup"><span data-stu-id="136cb-168">A sequence number, or <c>null</c> if no condition exists.</span></span></value>
        <remarks><span data-ttu-id="136cb-169">この条件は、ページ blob にのみ適用されます。</span><span class="sxs-lookup"><span data-stu-id="136cb-169">This condition only applies to page blobs.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="LeaseId">
      <MemberSignature Language="C#" Value="public string LeaseId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LeaseId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.AccessCondition.LeaseId" />
      <MemberSignature Language="VB.NET" Value="Public Property LeaseId As String" />
      <MemberSignature Language="F#" Value="member this.LeaseId : string with get, set" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.LeaseId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="136cb-170">取得またはリソースのリースと一致するリース ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="136cb-170">Gets or sets a lease ID that must match the lease on a resource.</span></span>
            </summary>
        <value><span data-ttu-id="136cb-171">リース ID を表す文字列または<c>null</c>条件が存在しない場合。</span><span class="sxs-lookup"><span data-stu-id="136cb-171">A string containing a lease ID, or <c>null</c> if no condition exists.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>