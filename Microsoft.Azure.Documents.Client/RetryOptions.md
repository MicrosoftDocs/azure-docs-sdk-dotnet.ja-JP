<Type Name="RetryOptions" FullName="Microsoft.Azure.Documents.Client.RetryOptions">
  <TypeSignature Language="C#" Value="public class RetryOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RetryOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Client.RetryOptions" />
  <TypeSignature Language="VB.NET" Value="Public Class RetryOptions" />
  <TypeSignature Language="F#" Value="type RetryOptions = class" />
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
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8b9de-101">RetryOptions クラスは、アプリケーションが Azure Cosmos DB サービスの組み込みの再試行ポリシーをカスタマイズする設定できるパラメーターを定義します。</span><span class="sxs-lookup"><span data-stu-id="8b9de-101">RetryOptions class defines the parameters an application can set to customize the built-in retry policies in the Azure Cosmos DB service.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="8b9de-102"><see cref="T:Microsoft.Azure.Documents.Client.DocumentClient" />クラスは、特定の種類の例外の再試行をサポートしています。</span><span class="sxs-lookup"><span data-stu-id="8b9de-102">The <see cref="T:Microsoft.Azure.Documents.Client.DocumentClient" /> class supports retry on certain types of exceptions.</span></span> <span data-ttu-id="8b9de-103">このクラスは、アプリケーションの再試行動作を制御するためのオプションを提供します。</span><span class="sxs-lookup"><span data-stu-id="8b9de-103">This class provides options for applications to control the retry behavior.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RetryOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.RetryOptions.#ctor" />
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
            <span data-ttu-id="8b9de-104">RetryOptions クラスの新しいインスタンスを作成して Azure Cosmos DB サービスの既定値にすべてのプロパティを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8b9de-104">Creates a new instance of the RetryOptions class and intialize all properties to default values for the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxRetryAttemptsOnThrottledRequests">
      <MemberSignature Language="C#" Value="public int MaxRetryAttemptsOnThrottledRequests { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxRetryAttemptsOnThrottledRequests" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.RetryOptions.MaxRetryAttemptsOnThrottledRequests" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxRetryAttemptsOnThrottledRequests As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxRetryAttemptsOnThrottledRequests : int with get, set" Usage="Microsoft.Azure.Documents.Client.RetryOptions.MaxRetryAttemptsOnThrottledRequests" />
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
            <span data-ttu-id="8b9de-105">取得または Cosmos DB の Azure サービスには、クライアントに頻度の制限が適用されるので、要求が失敗した場合の再試行の最大数を設定します。</span><span class="sxs-lookup"><span data-stu-id="8b9de-105">Gets or sets the maximum number of retries in the case where the request fails because the Azure Cosmos DB service has applied rate limiting on the client.</span></span>
            </summary>
        <value>
            <span data-ttu-id="8b9de-106">既定値は 9 です。</span><span class="sxs-lookup"><span data-stu-id="8b9de-106">The default value is 9.</span></span> <span data-ttu-id="8b9de-107">つまり、要求の率が制限されている場合に、同じ要求の送信は最大 10 倍の時間のサーバーにアプリケーションにエラーが返される前にします。</span><span class="sxs-lookup"><span data-stu-id="8b9de-107">This means in the case where the request is rate limited, the same request will be issued for a maximum of 10 times to the server before an error is returned to the application.</span></span> <span data-ttu-id="8b9de-108">このプロパティの値が 0 に設定されている場合は行われません頻度のクライアントからの要求の制限で自動再試行および例外は、アプリケーション レベルで処理する必要があります。</span><span class="sxs-lookup"><span data-stu-id="8b9de-108">If the value of this property is set to 0, there will be no automatic retry on rate limiting requests from the client and the exception needs to handled at the application level.</span></span> <span data-ttu-id="8b9de-109">この値を設定する方法の例を参照してください<see cref="P:Microsoft.Azure.Documents.Client.ConnectionPolicy.RetryOptions" />です。</span><span class="sxs-lookup"><span data-stu-id="8b9de-109">For an example on how to set this value, please refer to <see cref="P:Microsoft.Azure.Documents.Client.ConnectionPolicy.RetryOptions" />.</span></span>
            </value>
        <remarks>
          <para>
            <span data-ttu-id="8b9de-110">送信している場合、クライアント要求、許可されているレートよりも高速、サービスはクライアント使用率の上限を HttpStatusCode 429 (要求が多すぎます) を返します。</span><span class="sxs-lookup"><span data-stu-id="8b9de-110">When a client is sending requests faster than the allowed rate, the service will return HttpStatusCode 429 (Too Many Request) to rate limit the client.</span></span> <span data-ttu-id="8b9de-111">SDK の現在の実装は、時間、サービス、時間が経過後の処理を再試行するように指示し、待機します。</span><span class="sxs-lookup"><span data-stu-id="8b9de-111">The current implementation in the SDK will then wait for the amount of time the service tells it to wait and retry after the time has elapsed.</span></span>  
            </para>
          <para>
            <span data-ttu-id="8b9de-112">詳細については、次を参照してください。<see href="https://docs.microsoft.com/en-us/azure/documentdb/documentdb-performance-tips#429">ハンドル レート制限/要求の処理率が大きすぎます</see>です。</span><span class="sxs-lookup"><span data-stu-id="8b9de-112">For more information, see <see href="https://docs.microsoft.com/en-us/azure/documentdb/documentdb-performance-tips#429">Handle rate limiting/request rate too large</see>.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxRetryWaitTimeInSeconds">
      <MemberSignature Language="C#" Value="public int MaxRetryWaitTimeInSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxRetryWaitTimeInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.RetryOptions.MaxRetryWaitTimeInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxRetryWaitTimeInSeconds As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxRetryWaitTimeInSeconds : int with get, set" Usage="Microsoft.Azure.Documents.Client.RetryOptions.MaxRetryWaitTimeInSeconds" />
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
            <span data-ttu-id="8b9de-113">取得または Azure Cosmos DB サービスの秒単位の最大再試行時間を設定します。</span><span class="sxs-lookup"><span data-stu-id="8b9de-113">Gets or sets the maximum retry time in seconds for the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="8b9de-114">既定値は 30 秒です。</span><span class="sxs-lookup"><span data-stu-id="8b9de-114">The default value is 30 seconds.</span></span> <span data-ttu-id="8b9de-115">この値を設定する方法の例を参照してください<see cref="P:Microsoft.Azure.Documents.Client.ConnectionPolicy.RetryOptions" />です。</span><span class="sxs-lookup"><span data-stu-id="8b9de-115">For an example on how to set this value, please refer to <see cref="P:Microsoft.Azure.Documents.Client.ConnectionPolicy.RetryOptions" />.</span></span>
            </value>
        <remarks>
          <para>
            <span data-ttu-id="8b9de-116">エラーを制限する速度のため、要求に失敗したときに、サービス応答を返信する前に、クライアントが再試行する必要がありますかを示す値を含む、<see cref="P:Microsoft.Azure.Documents.DocumentClientException.RetryAfter" />期間が経過しました。</span><span class="sxs-lookup"><span data-stu-id="8b9de-116">When a request fails due to a rate limiting error, the service sends back a response that contains a value indicating the client should not retry before the <see cref="P:Microsoft.Azure.Documents.DocumentClientException.RetryAfter" /> time period has elapsed.</span></span> <span data-ttu-id="8b9de-117">このプロパティは、すべての再試行回数の最大待機時間を設定するアプリケーションを使用します。</span><span class="sxs-lookup"><span data-stu-id="8b9de-117">This property allows the application to set a maximum wait time for all retry attempts.</span></span>
            <span data-ttu-id="8b9de-118">累積待機時間が、これを超えると、値と、クライアントは再試行を停止、アプリケーションに、エラーが返されます。</span><span class="sxs-lookup"><span data-stu-id="8b9de-118">If the cumulative wait time exceeds the this value, the client will stop retrying and return the error to the application.</span></span>
            </para>
          <para>
            <span data-ttu-id="8b9de-119">詳細については、次を参照してください。<see href="https://docs.microsoft.com/en-us/azure/documentdb/documentdb-performance-tips#429">ハンドル レート制限/要求の処理率が大きすぎます</see>です。</span><span class="sxs-lookup"><span data-stu-id="8b9de-119">For more information, see <see href="https://docs.microsoft.com/en-us/azure/documentdb/documentdb-performance-tips#429">Handle rate limiting/request rate too large</see>.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>