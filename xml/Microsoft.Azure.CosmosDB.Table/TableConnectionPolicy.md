<Type Name="TableConnectionPolicy" FullName="Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy">
  <TypeSignature Language="C#" Value="public sealed class TableConnectionPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit TableConnectionPolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class TableConnectionPolicy" />
  <TypeSignature Language="F#" Value="type TableConnectionPolicy = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
    <AssemblyVersion>0.9.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="fc7ea-101">関連付けられている接続ポリシーを表す<see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTable" />Azure CosmosDB テーブル サービスに接続します。</span><span class="sxs-lookup"><span data-stu-id="fc7ea-101">Represents the connection policy associated with <see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTable" /> to connect to the Azure CosmosDB table service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableConnectionPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="fc7ea-102">新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy" /> Cosmos DB の Azure サービスに接続するクラス。</span><span class="sxs-lookup"><span data-stu-id="fc7ea-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy" /> class to connect to the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableEndpointDiscovery">
      <MemberSignature Language="C#" Value="public bool EnableEndpointDiscovery { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableEndpointDiscovery" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.EnableEndpointDiscovery" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableEndpointDiscovery As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableEndpointDiscovery : bool with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.EnableEndpointDiscovery" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fc7ea-103">取得または Azure Cosmos DB サービスの geo レプリケーションのデータベース アカウントのエンドポイントの探索を有効にするフラグを設定します。</span><span class="sxs-lookup"><span data-stu-id="fc7ea-103">Gets or sets the flag to enable endpoint discovery for geo-replicated database accounts in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="fc7ea-104">このプロパティの値は true、SDK には、現在の書き込みは自動的に検出および要求を確認するために読み取り領域がで指定されている領域に基づく正しい地域に送信されるときに、<see cref="P:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.PreferredLocations" />プロパティです。</span><span class="sxs-lookup"><span data-stu-id="fc7ea-104">When the value of this property is true, the SDK will automatically discover the current write and read regions to ensure requests are sent to the correct region based on the regions specified in the <see cref="P:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.PreferredLocations" /> property.</span></span>
            <span data-ttu-id="fc7ea-105"><value>既定値は true を示すエンドポイントの検出を有効にします。</value></span><span class="sxs-lookup"><span data-stu-id="fc7ea-105"><value>Default value is true indicating endpoint discovery is enabled.</value></span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxConnectionLimit">
      <MemberSignature Language="C#" Value="public int MaxConnectionLimit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxConnectionLimit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.MaxConnectionLimit" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxConnectionLimit As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxConnectionLimit : int with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.MaxConnectionLimit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fc7ea-106">取得または Azure Cosmos DB サービスの対象サービスのエンドポイントに対して許可される同時接続の最大数を設定します。</span><span class="sxs-lookup"><span data-stu-id="fc7ea-106">Gets or sets the maximum number of concurrent connections allowed for the target service endpoint in the Azure Cosmos DB service.</span></span>
            </summary>
        <value><span data-ttu-id="fc7ea-107">既定値は 50 です。</span><span class="sxs-lookup"><span data-stu-id="fc7ea-107">Default value is 50.</span></span></value>
        <remarks>
            <span data-ttu-id="fc7ea-108">この設定では、ゲートウェイのモードで適用のみです。</span><span class="sxs-lookup"><span data-stu-id="fc7ea-108">This setting is only applicable in Gateway mode.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxRetryAttemptsOnThrottledRequests">
      <MemberSignature Language="C#" Value="public int MaxRetryAttemptsOnThrottledRequests { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxRetryAttemptsOnThrottledRequests" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.MaxRetryAttemptsOnThrottledRequests" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxRetryAttemptsOnThrottledRequests As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxRetryAttemptsOnThrottledRequests : int with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.MaxRetryAttemptsOnThrottledRequests" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fc7ea-109">取得または Cosmos DB の Azure サービスには、クライアントに頻度の制限が適用されるので、要求が失敗した場合の再試行の最大数を設定します。</span><span class="sxs-lookup"><span data-stu-id="fc7ea-109">Gets or sets the maximum number of retries in the case where the request fails because the Azure Cosmos DB service has applied rate limiting on the client.</span></span>
            </summary>
        <value>
            <span data-ttu-id="fc7ea-110">既定値は 9 です。</span><span class="sxs-lookup"><span data-stu-id="fc7ea-110">The default value is 9.</span></span> <span data-ttu-id="fc7ea-111">つまり、要求の率が制限されている場合に、同じ要求の送信は最大 10 倍の時間のサーバーにアプリケーションにエラーが返される前にします。</span><span class="sxs-lookup"><span data-stu-id="fc7ea-111">This means in the case where the request is rate limited, the same request will be issued for a maximum of 10 times to the server before an error is returned to the application.</span></span> <span data-ttu-id="fc7ea-112">このプロパティの値が 0 に設定されている場合は行われません頻度のクライアントからの要求の制限で自動再試行および例外は、アプリケーション レベルで処理する必要があります。</span><span class="sxs-lookup"><span data-stu-id="fc7ea-112">If the value of this property is set to 0, there will be no automatic retry on rate limiting requests from the client and the exception needs to handled at the application level.</span></span> 
            </value>
        <remarks>
          <para>
            <span data-ttu-id="fc7ea-113">送信している場合、クライアント要求、許可されているレートよりも高速、サービスはクライアント使用率の上限を HttpStatusCode 429 (要求が多すぎます) を返します。</span><span class="sxs-lookup"><span data-stu-id="fc7ea-113">When a client is sending requests faster than the allowed rate, the service will return HttpStatusCode 429 (Too Many Request) to rate limit the client.</span></span> <span data-ttu-id="fc7ea-114">SDK の現在の実装は、時間、サービス、時間が経過後の処理を再試行するように指示し、待機します。</span><span class="sxs-lookup"><span data-stu-id="fc7ea-114">The current implementation in the SDK will then wait for the amount of time the service tells it to wait and retry after the time has elapsed.</span></span>  
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxRetryWaitTimeInSeconds">
      <MemberSignature Language="C#" Value="public int MaxRetryWaitTimeInSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxRetryWaitTimeInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.MaxRetryWaitTimeInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxRetryWaitTimeInSeconds As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxRetryWaitTimeInSeconds : int with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.MaxRetryWaitTimeInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fc7ea-115">取得または Azure Cosmos DB サービスの秒単位の最大再試行時間を設定します。</span><span class="sxs-lookup"><span data-stu-id="fc7ea-115">Gets or sets the maximum retry time in seconds for the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="fc7ea-116">既定値は 30 秒です。</span><span class="sxs-lookup"><span data-stu-id="fc7ea-116">The default value is 30 seconds.</span></span> 
            </value>
        <remarks>
          <para>
            <span data-ttu-id="fc7ea-117">エラーを制限する速度のため、要求に失敗したときに、サービス応答を返信までの時間が経過する前にクライアントが再試行する必要がありますを示す値を含むです。</span><span class="sxs-lookup"><span data-stu-id="fc7ea-117">When a request fails due to a rate limiting error, the service sends back a response that contains a value indicating the client should not retry before the time period has elapsed.</span></span> <span data-ttu-id="fc7ea-118">このプロパティは、すべての再試行回数の最大待機時間を設定するアプリケーションを使用します。</span><span class="sxs-lookup"><span data-stu-id="fc7ea-118">This property allows the application to set a maximum wait time for all retry attempts.</span></span>
            <span data-ttu-id="fc7ea-119">累積待機時間が、これを超えると、値と、クライアントは再試行を停止、アプリケーションに、エラーが返されます。</span><span class="sxs-lookup"><span data-stu-id="fc7ea-119">If the cumulative wait time exceeds the this value, the client will stop retrying and return the error to the application.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="PreferredLocations">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.Collection&lt;string&gt; PreferredLocations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.ObjectModel.Collection`1&lt;string&gt; PreferredLocations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.PreferredLocations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PreferredLocations As Collection(Of String)" />
      <MemberSignature Language="F#" Value="member this.PreferredLocations : System.Collections.ObjectModel.Collection&lt;string&gt;" Usage="Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.PreferredLocations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.Collection&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fc7ea-120">取得し、Azure Cosmos DB サービスの geo レプリケーションのデータベース アカウントの推奨される場所 (地域) を設定します。</span><span class="sxs-lookup"><span data-stu-id="fc7ea-120">Gets and sets the preferred locations (regions) for geo-replicated database accounts in the Azure Cosmos DB service.</span></span> <span data-ttu-id="fc7ea-121">たとえば、適切な場所として「東部米国」です。</span><span class="sxs-lookup"><span data-stu-id="fc7ea-121">For example, "East US" as the preferred location.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>
            <span data-ttu-id="fc7ea-122">ときに<see cref="P:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.EnableEndpointDiscovery" />が true であり、値のこのプロパティは空でない、SDK が、このプロパティの値が指定されていない場合それ以外の場合、操作を実行する指定された順序でコレクション内の場所を使用して、SDK と書き込みのリージョンを使用して、すべての操作の推奨される場所です。</span><span class="sxs-lookup"><span data-stu-id="fc7ea-122">When <see cref="P:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.EnableEndpointDiscovery" /> is true and the value of this property is non-empty, the SDK uses the locations in the collection in the order they are specified to perform operations, otherwise if the value of this property is not specified, the SDK uses the write region as the preferred location for all operations.</span></span>
            </para>
          <para>
            <span data-ttu-id="fc7ea-123">場合<see cref="P:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.EnableEndpointDiscovery" />が設定されているを false に、このプロパティの値は無視されます。</span><span class="sxs-lookup"><span data-stu-id="fc7ea-123">If <see cref="P:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.EnableEndpointDiscovery" /> is set to false, the value of this property is ignored.</span></span> 
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="UseDirectMode">
      <MemberSignature Language="C#" Value="public bool UseDirectMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool UseDirectMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.UseDirectMode" />
      <MemberSignature Language="VB.NET" Value="Public Property UseDirectMode As Boolean" />
      <MemberSignature Language="F#" Value="member this.UseDirectMode : bool with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.UseDirectMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fc7ea-124">ダイレクト モードを使用して Azure Cosmos DB サービス flase への接続時に、テーブル REST API を使用して接続されます</span><span class="sxs-lookup"><span data-stu-id="fc7ea-124">Use direct mode when connecting to Azure Cosmos DB service flase, will connect through table REST API</span></span> 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserAgentSuffix">
      <MemberSignature Language="C#" Value="public string UserAgentSuffix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserAgentSuffix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.UserAgentSuffix" />
      <MemberSignature Language="VB.NET" Value="Public Property UserAgentSuffix As String" />
      <MemberSignature Language="F#" Value="member this.UserAgentSuffix : string with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.UserAgentSuffix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fc7ea-125">Azure Cosmos DB サービスの既定のユーザー エージェントに追加するサフィックスです。</span><span class="sxs-lookup"><span data-stu-id="fc7ea-125">A suffix to be added to the default user-agent for the Azure Cosmos DB service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="fc7ea-126">すべての要求の送信後にこのプロパティの設定の効果はありません。</span><span class="sxs-lookup"><span data-stu-id="fc7ea-126">Setting this property after sending any request won't have any effect.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UseTcpProtocol">
      <MemberSignature Language="C#" Value="public bool UseTcpProtocol { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool UseTcpProtocol" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.UseTcpProtocol" />
      <MemberSignature Language="VB.NET" Value="Public Property UseTcpProtocol As Boolean" />
      <MemberSignature Language="F#" Value="member this.UseTcpProtocol : bool with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.UseTcpProtocol" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fc7ea-127">Cosmos DB の Azure サービスに接続するときは、TCP 接続プロトコルを使用します。</span><span class="sxs-lookup"><span data-stu-id="fc7ea-127">Use TCP connection protocol when connecting to the Azure Cosmos DB service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="fc7ea-128">詳細については、次を参照してください。<see href="https://docs.microsoft.com/en-us/azure/documentdb/documentdb-performance-tips#use-tcp">接続ポリシー: TCP プロトコルを使用して</see>です。</span><span class="sxs-lookup"><span data-stu-id="fc7ea-128">For more information, see <see href="https://docs.microsoft.com/en-us/azure/documentdb/documentdb-performance-tips#use-tcp">Connection policy: Use the TCP protocol</see>.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>