<Type Name="ISearchIndexClient" FullName="Microsoft.Azure.Search.ISearchIndexClient">
  <TypeSignature Language="C#" Value="public interface ISearchIndexClient : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ISearchIndexClient implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.ISearchIndexClient" />
  <TypeSignature Language="VB.NET" Value="Public Interface ISearchIndexClient&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type ISearchIndexClient = interface&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="132a2-101">Azure Search インデックスとアップロード、クエリに使用できるクライアントは、merge、またはドキュメントを削除します。</span><span class="sxs-lookup"><span data-stu-id="132a2-101">Client that can be used to query an Azure Search index and upload, merge, or delete documents.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AcceptLanguage">
      <MemberSignature Language="C#" Value="public string AcceptLanguage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AcceptLanguage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.ISearchIndexClient.AcceptLanguage" />
      <MemberSignature Language="VB.NET" Value="Public Property AcceptLanguage As String" />
      <MemberSignature Language="F#" Value="member this.AcceptLanguage : string with get, set" Usage="Microsoft.Azure.Search.ISearchIndexClient.AcceptLanguage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="132a2-102">取得または応答の優先言語を設定します。</span><span class="sxs-lookup"><span data-stu-id="132a2-102">Gets or sets the preferred language for the response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApiVersion">
      <MemberSignature Language="C#" Value="public string ApiVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApiVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.ISearchIndexClient.ApiVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApiVersion As String" />
      <MemberSignature Language="F#" Value="member this.ApiVersion : string" Usage="Microsoft.Azure.Search.ISearchIndexClient.ApiVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="132a2-103">クライアント Api のバージョン。</span><span class="sxs-lookup"><span data-stu-id="132a2-103">Client Api Version.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.ServiceClientCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.ServiceClientCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.ISearchIndexClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As ServiceClientCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Rest.ServiceClientCredentials" Usage="Microsoft.Azure.Search.ISearchIndexClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.ServiceClientCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="132a2-104">Azure に接続するクライアントに必要な資格情報です。</span><span class="sxs-lookup"><span data-stu-id="132a2-104">Credentials needed for the client to connect to Azure.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeserializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings DeserializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings DeserializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.ISearchIndexClient.DeserializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeserializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.DeserializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Search.ISearchIndexClient.DeserializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="132a2-105">取得または json に逆シリアル化の設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="132a2-105">Gets or sets json deserialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Documents">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.IDocumentsOperations Documents { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.IDocumentsOperations Documents" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.ISearchIndexClient.Documents" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Documents As IDocumentsOperations" />
      <MemberSignature Language="F#" Value="member this.Documents : Microsoft.Azure.Search.IDocumentsOperations" Usage="Microsoft.Azure.Search.ISearchIndexClient.Documents" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.IDocumentsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="132a2-106">IDocumentsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="132a2-106">Gets the IDocumentsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; GenerateClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; GenerateClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.ISearchIndexClient.GenerateClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property GenerateClientRequestId As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.GenerateClientRequestId : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.ISearchIndexClient.GenerateClientRequestId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="132a2-107">設定すると、一意の x ms-クライアントの要求 id 値を true に生成され、各要求に含まれます。</span><span class="sxs-lookup"><span data-stu-id="132a2-107">When set to true a unique x-ms-client-request-id value is generated and included in each request.</span></span> <span data-ttu-id="132a2-108">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="132a2-108">Default is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexName">
      <MemberSignature Language="C#" Value="public string IndexName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IndexName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.ISearchIndexClient.IndexName" />
      <MemberSignature Language="VB.NET" Value="Public Property IndexName As String" />
      <MemberSignature Language="F#" Value="member this.IndexName : string with get, set" Usage="Microsoft.Azure.Search.ISearchIndexClient.IndexName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="132a2-109">Azure Search インデックスの名前。</span><span class="sxs-lookup"><span data-stu-id="132a2-109">The name of the Azure Search index.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationRetryTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; LongRunningOperationRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; LongRunningOperationRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.ISearchIndexClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.ISearchIndexClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="132a2-110">取得または長時間実行される操作の秒単位の再試行タイムアウトを設定します。</span><span class="sxs-lookup"><span data-stu-id="132a2-110">Gets or sets the retry timeout in seconds for Long Running Operations.</span></span> <span data-ttu-id="132a2-111">既定値は 30 です。</span><span class="sxs-lookup"><span data-stu-id="132a2-111">Default value is 30.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SearchCredentials">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.SearchCredentials SearchCredentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.SearchCredentials SearchCredentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.ISearchIndexClient.SearchCredentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SearchCredentials As SearchCredentials" />
      <MemberSignature Language="F#" Value="member this.SearchCredentials : Microsoft.Azure.Search.SearchCredentials" Usage="Microsoft.Azure.Search.ISearchIndexClient.SearchCredentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.SearchCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="132a2-112">Azure Search サービスへの認証に使用する資格情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="132a2-112">Gets the credentials used to authenticate to an Azure Search service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SearchDnsSuffix">
      <MemberSignature Language="C#" Value="public string SearchDnsSuffix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SearchDnsSuffix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.ISearchIndexClient.SearchDnsSuffix" />
      <MemberSignature Language="VB.NET" Value="Public Property SearchDnsSuffix As String" />
      <MemberSignature Language="F#" Value="member this.SearchDnsSuffix : string with get, set" Usage="Microsoft.Azure.Search.ISearchIndexClient.SearchDnsSuffix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="132a2-113">Azure Search サービスの DNS サフィックス。</span><span class="sxs-lookup"><span data-stu-id="132a2-113">The DNS suffix of the Azure Search service.</span></span> <span data-ttu-id="132a2-114">既定値は、&lt;name&gt;.search.windows.net です。</span><span class="sxs-lookup"><span data-stu-id="132a2-114">The default is search.windows.net.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SearchServiceName">
      <MemberSignature Language="C#" Value="public string SearchServiceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SearchServiceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.ISearchIndexClient.SearchServiceName" />
      <MemberSignature Language="VB.NET" Value="Public Property SearchServiceName As String" />
      <MemberSignature Language="F#" Value="member this.SearchServiceName : string with get, set" Usage="Microsoft.Azure.Search.ISearchIndexClient.SearchServiceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="132a2-115">Azure Search サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="132a2-115">The name of the Azure Search service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings SerializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings SerializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.ISearchIndexClient.SerializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.SerializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Search.ISearchIndexClient.SerializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="132a2-116">サービスのベース URI。</span><span class="sxs-lookup"><span data-stu-id="132a2-116">The base URI of the service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetDifferentIndex">
      <MemberSignature Language="C#" Value="public void TargetDifferentIndex (string newIndexName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void TargetDifferentIndex(string newIndexName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.ISearchIndexClient.TargetDifferentIndex(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub TargetDifferentIndex (newIndexName As String)" />
      <MemberSignature Language="F#" Value="abstract member TargetDifferentIndex : string -&gt; unit" Usage="iSearchIndexClient.TargetDifferentIndex newIndexName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="newIndexName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="newIndexName"><span data-ttu-id="132a2-117">すべての後続の要求の送信先となるインデックスの名前。</span><span class="sxs-lookup"><span data-stu-id="132a2-117">The name of the index to which all subsequent requests should be sent.</span></span></param>
        <summary>
            <span data-ttu-id="132a2-118">このクライアントを同じ Azure Search サービスで別のインデックスを対象の BaseUri を変更します。</span><span class="sxs-lookup"><span data-stu-id="132a2-118">Changes the BaseUri of this client to target a different index in the same Azure Search service.</span></span> <span data-ttu-id="132a2-119">このメソッドは、スレッド セーフです。他のスレッドが使用していないこと、クライアントを呼び出す前に保証する必要があります。</span><span class="sxs-lookup"><span data-stu-id="132a2-119">This method is NOT thread-safe; You must guarantee that no other threads are using the client before calling it.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseHttpGetForQueries">
      <MemberSignature Language="C#" Value="public bool UseHttpGetForQueries { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool UseHttpGetForQueries" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.ISearchIndexClient.UseHttpGetForQueries" />
      <MemberSignature Language="VB.NET" Value="Public Property UseHttpGetForQueries As Boolean" />
      <MemberSignature Language="F#" Value="member this.UseHttpGetForQueries : bool with get, set" Usage="Microsoft.Azure.Search.ISearchIndexClient.UseHttpGetForQueries" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="132a2-120">インデックス クライアントが検索を行うための HTTP GET を使用し、Azure Search REST API への要求を提示するかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="132a2-120">Indicates whether the index client should use HTTP GET for making Search and Suggest requests to the Azure Search REST API.</span></span> <span data-ttu-id="132a2-121">既定値は<c>false</c>、HTTP POST を使用することを示します。</span><span class="sxs-lookup"><span data-stu-id="132a2-121">The default is <c>false</c>, which indicates that HTTP POST will be used.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>