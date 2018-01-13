<Type Name="IStoredProcedureResponse&lt;TValue&gt;" FullName="Microsoft.Azure.Documents.Client.IStoredProcedureResponse&lt;TValue&gt;">
  <TypeSignature Language="C#" Value="public interface IStoredProcedureResponse&lt;TValue&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IStoredProcedureResponse`1&lt;TValue&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Client.IStoredProcedureResponse`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IStoredProcedureResponse(Of TValue)" />
  <TypeSignature Language="F#" Value="type IStoredProcedureResponse&lt;'Value&gt; = interface" />
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
    <TypeParameter Name="TValue" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="TValue"><span data-ttu-id="093b8-101">ストアド プロシージャの戻り値の型。</span><span class="sxs-lookup"><span data-stu-id="093b8-101">The returned value type of the stored procedure.</span></span></typeparam>
    <summary>
            <span data-ttu-id="093b8-102">Azure Cosmos DB サービスの目的をモックに公開されるインターフェイス。</span><span class="sxs-lookup"><span data-stu-id="093b8-102">Interface exposed for mocking purposes for the Azure Cosmos DB service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ActivityId">
      <MemberSignature Language="C#" Value="public string ActivityId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ActivityId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IStoredProcedureResponse`1.ActivityId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActivityId As String" />
      <MemberSignature Language="F#" Value="member this.ActivityId : string" Usage="Microsoft.Azure.Documents.Client.IStoredProcedureResponse&lt;'Value&gt;.ActivityId" />
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
            <span data-ttu-id="093b8-103">要求のアクティビティ ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="093b8-103">Gets the Activity ID of the request.</span></span>
            </summary>
        <value>
            <span data-ttu-id="093b8-104">要求のアクティビティ ID。</span><span class="sxs-lookup"><span data-stu-id="093b8-104">The Activity ID of the request.</span></span>
            </value>
        <remarks><span data-ttu-id="093b8-105">グローバルに一意の ID を持つすべての要求をトレースします。</span><span class="sxs-lookup"><span data-stu-id="093b8-105">Every request is traced with a globally unique ID.</span></span> <span data-ttu-id="093b8-106">アプリケーション エラーのトレースに、および Azure Cosmos DB サポートに問い合わせて、アクティビティ ID が含まれます。</span><span class="sxs-lookup"><span data-stu-id="093b8-106">Include activity ID in tracing application failures and when contacting Azure Cosmos DB support.</span></span>
            <span data-ttu-id="093b8-107">これは、Azure Cosmos DB サービスの目的をモックに公開されます。</span><span class="sxs-lookup"><span data-stu-id="093b8-107">This is exposed for mocking purposes for the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentResourceQuotaUsage">
      <MemberSignature Language="C#" Value="public string CurrentResourceQuotaUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CurrentResourceQuotaUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IStoredProcedureResponse`1.CurrentResourceQuotaUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentResourceQuotaUsage As String" />
      <MemberSignature Language="F#" Value="member this.CurrentResourceQuotaUsage : string" Usage="Microsoft.Azure.Documents.Client.IStoredProcedureResponse&lt;'Value&gt;.CurrentResourceQuotaUsage" />
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
            <span data-ttu-id="093b8-108">コレクション内で各リソースの種類の使用法を含んでいる区切られた文字列を取得します。</span><span class="sxs-lookup"><span data-stu-id="093b8-108">Gets the delimited string containing the usage of each resource type within the collection.</span></span>
            </summary>
        <value><span data-ttu-id="093b8-109">コレクション内のリソースの種類ごとに使用される単位数を含んでいる区切られた文字列。</span><span class="sxs-lookup"><span data-stu-id="093b8-109">The delimited string containing the number of used units per resource type within the collection.</span></span></value>
        <remarks>
            <span data-ttu-id="093b8-110">これは、Azure Cosmos DB サービスの目的をモックに公開されます。</span><span class="sxs-lookup"><span data-stu-id="093b8-110">This is exposed for mocking purposes for the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxResourceQuota">
      <MemberSignature Language="C#" Value="public string MaxResourceQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MaxResourceQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IStoredProcedureResponse`1.MaxResourceQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxResourceQuota As String" />
      <MemberSignature Language="F#" Value="member this.MaxResourceQuota : string" Usage="Microsoft.Azure.Documents.Client.IStoredProcedureResponse&lt;'Value&gt;.MaxResourceQuota" />
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
            <span data-ttu-id="093b8-111">コレクション内で各リソースの種類のクォータを含んでいる区切られた文字列を取得します。</span><span class="sxs-lookup"><span data-stu-id="093b8-111">Gets the delimited string containing the quota of each resource type within the collection.</span></span>
            </summary>
        <value><span data-ttu-id="093b8-112">コレクション内のリソースの種類ごとに使用される単位数を含んでいる区切られた文字列。</span><span class="sxs-lookup"><span data-stu-id="093b8-112">The delimited string containing the number of used units per resource type within the collection.</span></span></value>
        <remarks>
            <span data-ttu-id="093b8-113">これは、Azure Cosmos DB サービスの目的をモックに公開されます。</span><span class="sxs-lookup"><span data-stu-id="093b8-113">This is exposed for mocking purposes for the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestCharge">
      <MemberSignature Language="C#" Value="public double RequestCharge { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 RequestCharge" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IStoredProcedureResponse`1.RequestCharge" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestCharge As Double" />
      <MemberSignature Language="F#" Value="member this.RequestCharge : double" Usage="Microsoft.Azure.Documents.Client.IStoredProcedureResponse&lt;'Value&gt;.RequestCharge" />
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
            <span data-ttu-id="093b8-114">課金正規化された要求ユニット (Ru) の数を取得します。</span><span class="sxs-lookup"><span data-stu-id="093b8-114">Gets the number of normalized request units (RUs) charged.</span></span>
            </summary>
        <value>
            <span data-ttu-id="093b8-115">正規化された要求ユニット (Ru) の数が課金されます。</span><span class="sxs-lookup"><span data-stu-id="093b8-115">The number of normalized request units (RUs) charged.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="093b8-116">これは、Azure Cosmos DB サービスの目的をモックに公開されます。</span><span class="sxs-lookup"><span data-stu-id="093b8-116">This is exposed for mocking purposes for the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Response">
      <MemberSignature Language="C#" Value="public TValue Response { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !TValue Response" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IStoredProcedureResponse`1.Response" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Response As TValue" />
      <MemberSignature Language="F#" Value="member this.Response : 'Value" Usage="Microsoft.Azure.Documents.Client.IStoredProcedureResponse&lt;'Value&gt;.Response" />
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
        <ReturnType>TValue</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="093b8-117">指定された型にシリアル化し、ストアド プロシージャの応答を取得します。</span><span class="sxs-lookup"><span data-stu-id="093b8-117">Gets the response of a stored procedure, serialized into the given type.</span></span>
            </summary>
        <value><span data-ttu-id="093b8-118">指定された型にシリアル化し、ストアド プロシージャの応答です。</span><span class="sxs-lookup"><span data-stu-id="093b8-118">The response of a stored procedure, serialized into the given type.</span></span></value>
        <remarks>
            <span data-ttu-id="093b8-119">これは、Azure Cosmos DB サービスの目的をモックに公開されます。</span><span class="sxs-lookup"><span data-stu-id="093b8-119">This is exposed for mocking purposes for the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResponseHeaders">
      <MemberSignature Language="C#" Value="public System.Collections.Specialized.NameValueCollection ResponseHeaders { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Specialized.NameValueCollection ResponseHeaders" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IStoredProcedureResponse`1.ResponseHeaders" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResponseHeaders As NameValueCollection" />
      <MemberSignature Language="F#" Value="member this.ResponseHeaders : System.Collections.Specialized.NameValueCollection" Usage="Microsoft.Azure.Documents.Client.IStoredProcedureResponse&lt;'Value&gt;.ResponseHeaders" />
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
            <span data-ttu-id="093b8-120">応答に関連付けられたヘッダーを取得します。</span><span class="sxs-lookup"><span data-stu-id="093b8-120">Gets the headers associated with the response.</span></span>
            </summary>
        <value>
            <span data-ttu-id="093b8-121">応答に関連付けられたヘッダー。</span><span class="sxs-lookup"><span data-stu-id="093b8-121">Headers associated with the response.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="093b8-122">Azure Cosmos DB API から返されたすべての HTTP 応答ヘッダーへのアクセスを提供します。</span><span class="sxs-lookup"><span data-stu-id="093b8-122">Provides access to all HTTP response headers returned from the Azure Cosmos DB API.</span></span>
            <span data-ttu-id="093b8-123">これは、Azure Cosmos DB サービスの目的をモックに公開されます。</span><span class="sxs-lookup"><span data-stu-id="093b8-123">This is exposed for mocking purposes for the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ScriptLog">
      <MemberSignature Language="C#" Value="public string ScriptLog { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ScriptLog" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IStoredProcedureResponse`1.ScriptLog" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ScriptLog As String" />
      <MemberSignature Language="F#" Value="member this.ScriptLog : string" Usage="Microsoft.Azure.Documents.Client.IStoredProcedureResponse&lt;'Value&gt;.ScriptLog" />
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
            <span data-ttu-id="093b8-124">ストアド プロシージャから console.log() ステートメントの出力を取得します。</span><span class="sxs-lookup"><span data-stu-id="093b8-124">Gets the output from stored procedure console.log() statements.</span></span>
            </summary>
        <value>
            <span data-ttu-id="093b8-125">ストアド プロシージャで console.log() ステートメントからの出力。</span><span class="sxs-lookup"><span data-stu-id="093b8-125">Output from console.log() statements in a stored procedure.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="093b8-126">これは、Azure Cosmos DB サービスの目的をモックに公開されます。</span><span class="sxs-lookup"><span data-stu-id="093b8-126">This is exposed for mocking purposes for the Azure Cosmos DB service.</span></span>
            </remarks>
        <altmember cref="P:Microsoft.Azure.Documents.Client.RequestOptions.EnableScriptLogging" />
      </Docs>
    </Member>
    <Member MemberName="SessionToken">
      <MemberSignature Language="C#" Value="public string SessionToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SessionToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IStoredProcedureResponse`1.SessionToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SessionToken As String" />
      <MemberSignature Language="F#" Value="member this.SessionToken : string" Usage="Microsoft.Azure.Documents.Client.IStoredProcedureResponse&lt;'Value&gt;.SessionToken" />
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
            <span data-ttu-id="093b8-127">セッションの整合性の要求で使用するためには、トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="093b8-127">Gets the token for use with session consistency requests.</span></span>
            </summary>
        <value>
            <span data-ttu-id="093b8-128">セッションの整合性の要求で使用するためのトークンです。</span><span class="sxs-lookup"><span data-stu-id="093b8-128">The token for use with session consistency requests.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="093b8-129">これは、Azure Cosmos DB サービスの目的をモックに公開されます。</span><span class="sxs-lookup"><span data-stu-id="093b8-129">This is exposed for mocking purposes for the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusCode">
      <MemberSignature Language="C#" Value="public System.Net.HttpStatusCode StatusCode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Net.HttpStatusCode StatusCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IStoredProcedureResponse`1.StatusCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StatusCode As HttpStatusCode" />
      <MemberSignature Language="F#" Value="member this.StatusCode : System.Net.HttpStatusCode" Usage="Microsoft.Azure.Documents.Client.IStoredProcedureResponse&lt;'Value&gt;.StatusCode" />
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
        <ReturnType>System.Net.HttpStatusCode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="093b8-130">要求の完了ステータス コードを取得します。</span><span class="sxs-lookup"><span data-stu-id="093b8-130">Gets the request completion status code.</span></span>
            </summary>
        <value><span data-ttu-id="093b8-131">要求の完了ステータス コード</span><span class="sxs-lookup"><span data-stu-id="093b8-131">The request completion status code</span></span></value>
        <remarks>
            <span data-ttu-id="093b8-132">これは、Azure Cosmos DB サービスの目的をモックに公開されます。</span><span class="sxs-lookup"><span data-stu-id="093b8-132">This is exposed for mocking purposes for the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>