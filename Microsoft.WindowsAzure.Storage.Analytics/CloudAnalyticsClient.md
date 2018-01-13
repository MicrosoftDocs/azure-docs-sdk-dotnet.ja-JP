<Type Name="CloudAnalyticsClient" FullName="Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient">
  <TypeSignature Language="C#" Value="public sealed class CloudAnalyticsClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit CloudAnalyticsClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class CloudAnalyticsClient" />
  <TypeSignature Language="F#" Value="type CloudAnalyticsClient = class" />
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
            <span data-ttu-id="61adf-101">Microsoft Azure Storage Analytics のクライアント側の論理表現を提供します。</span><span class="sxs-lookup"><span data-stu-id="61adf-101">Provides a client-side logical representation for Microsoft Azure Storage Analytics.</span></span> <span data-ttu-id="61adf-102">このクライアントを使用してを構成および記憶域の分析に対する要求を実行します。</span><span class="sxs-lookup"><span data-stu-id="61adf-102">This client is used to configure and execute requests against storage analytics.</span></span>
            </summary>
    <remarks><span data-ttu-id="61adf-103">分析サービス クライアントは、Blob およびテーブル サービスのエンドポイントをカプセル化します。</span><span class="sxs-lookup"><span data-stu-id="61adf-103">The analytics service client encapsulates the endpoints for the Blob and Table services.</span></span> <span data-ttu-id="61adf-104">また、ストレージ アカウントにアクセスするための資格情報をカプセル化します。</span><span class="sxs-lookup"><span data-stu-id="61adf-104">It also encapsulates credentials for accessing the storage account.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudAnalyticsClient (Microsoft.WindowsAzure.Storage.StorageUri blobStorageUri, Microsoft.WindowsAzure.Storage.StorageUri tableStorageUri, Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.StorageUri blobStorageUri, class Microsoft.WindowsAzure.Storage.StorageUri tableStorageUri, class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.#ctor(Microsoft.WindowsAzure.Storage.StorageUri,Microsoft.WindowsAzure.Storage.StorageUri,Microsoft.WindowsAzure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (blobStorageUri As StorageUri, tableStorageUri As StorageUri, credentials As StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient : Microsoft.WindowsAzure.Storage.StorageUri * Microsoft.WindowsAzure.Storage.StorageUri * Microsoft.WindowsAzure.Storage.Auth.StorageCredentials -&gt; Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient" Usage="new Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient (blobStorageUri, tableStorageUri, credentials)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="blobStorageUri" Type="Microsoft.WindowsAzure.Storage.StorageUri" />
        <Parameter Name="tableStorageUri" Type="Microsoft.WindowsAzure.Storage.StorageUri" />
        <Parameter Name="credentials" Type="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />
      </Parameters>
      <Docs>
        <param name="blobStorageUri"><span data-ttu-id="61adf-105">A<see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" />を使用してクライアントを作成する Blob サービス エンドポイントを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="61adf-105">A <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" /> object containing the Blob service endpoint to use to create the client.</span></span></param>
        <param name="tableStorageUri"><span data-ttu-id="61adf-106">A<see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" />を使用してクライアントを作成するテーブル サービスのエンドポイントを含むオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="61adf-106">A <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" /> object containing the Table service endpoint to use to create the client.</span></span></param>
        <param name="credentials"><span data-ttu-id="61adf-107"><see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="61adf-107">A <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="61adf-108">新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient" />クラスの指定した Blob およびテーブル サービスのエンドポイントを使用して、アカウントの資格情報。</span><span class="sxs-lookup"><span data-stu-id="61adf-108">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient" /> class using the specified Blob and Table service endpoints and account credentials.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateCapacityQuery">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;Microsoft.WindowsAzure.Storage.Analytics.CapacityEntity&gt; CreateCapacityQuery ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.Table.TableQuery`1&lt;class Microsoft.WindowsAzure.Storage.Analytics.CapacityEntity&gt; CreateCapacityQuery() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.CreateCapacityQuery" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateCapacityQuery () As TableQuery(Of CapacityEntity)" />
      <MemberSignature Language="F#" Value="member this.CreateCapacityQuery : unit -&gt; Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;Microsoft.WindowsAzure.Storage.Analytics.CapacityEntity&gt;" Usage="cloudAnalyticsClient.CreateCapacityQuery " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;Microsoft.WindowsAzure.Storage.Analytics.CapacityEntity&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="61adf-109">作成、 <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" /> Blob サービスの容量テーブルを照会するためのオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="61adf-109">Creates a <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" /> object for querying the Blob service capacity table.</span></span>
            </summary>
        <returns><span data-ttu-id="61adf-110"><see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="61adf-110">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" /> object.</span></span></returns>
        <remarks><span data-ttu-id="61adf-111">このメソッドは、Blob サービスにのみ適用されます。</span><span class="sxs-lookup"><span data-stu-id="61adf-111">This method is applicable only to Blob service.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateHourMetricsQuery">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity&gt; CreateHourMetricsQuery (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, Microsoft.WindowsAzure.Storage.StorageLocation location);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.Table.TableQuery`1&lt;class Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity&gt; CreateHourMetricsQuery(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, valuetype Microsoft.WindowsAzure.Storage.StorageLocation location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.CreateHourMetricsQuery(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService,Microsoft.WindowsAzure.Storage.StorageLocation)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateHourMetricsQuery (service As StorageService, location As StorageLocation) As TableQuery(Of MetricsEntity)" />
      <MemberSignature Language="F#" Value="member this.CreateHourMetricsQuery : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService * Microsoft.WindowsAzure.Storage.StorageLocation -&gt; Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity&gt;" Usage="cloudAnalyticsClient.CreateHourMetricsQuery (service, location)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
        <Parameter Name="location" Type="Microsoft.WindowsAzure.Storage.StorageLocation" />
      </Parameters>
      <Docs>
        <param name="service"><span data-ttu-id="61adf-112"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> 列挙値。</span><span class="sxs-lookup"><span data-stu-id="61adf-112">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> enumeration value.</span></span></param>
        <param name="location"><span data-ttu-id="61adf-113"><see cref="T:Microsoft.WindowsAzure.Storage.StorageLocation" /> 列挙値。</span><span class="sxs-lookup"><span data-stu-id="61adf-113">A <see cref="T:Microsoft.WindowsAzure.Storage.StorageLocation" /> enumeration value.</span></span></param>
        <summary>
            <span data-ttu-id="61adf-114">作成、<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />時間単位のメトリック ログ テーブルを照会するためのオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="61adf-114">Creates a <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" /> object for querying an hourly metrics log table.</span></span>
            </summary>
        <returns><span data-ttu-id="61adf-115"><see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="61adf-115">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMinuteMetricsQuery">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity&gt; CreateMinuteMetricsQuery (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, Microsoft.WindowsAzure.Storage.StorageLocation location);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.Table.TableQuery`1&lt;class Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity&gt; CreateMinuteMetricsQuery(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, valuetype Microsoft.WindowsAzure.Storage.StorageLocation location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.CreateMinuteMetricsQuery(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService,Microsoft.WindowsAzure.Storage.StorageLocation)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateMinuteMetricsQuery (service As StorageService, location As StorageLocation) As TableQuery(Of MetricsEntity)" />
      <MemberSignature Language="F#" Value="member this.CreateMinuteMetricsQuery : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService * Microsoft.WindowsAzure.Storage.StorageLocation -&gt; Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity&gt;" Usage="cloudAnalyticsClient.CreateMinuteMetricsQuery (service, location)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
        <Parameter Name="location" Type="Microsoft.WindowsAzure.Storage.StorageLocation" />
      </Parameters>
      <Docs>
        <param name="service"><span data-ttu-id="61adf-116"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> 列挙値。</span><span class="sxs-lookup"><span data-stu-id="61adf-116">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> enumeration value.</span></span></param>
        <param name="location"><span data-ttu-id="61adf-117"><see cref="T:Microsoft.WindowsAzure.Storage.StorageLocation" /> 列挙値。</span><span class="sxs-lookup"><span data-stu-id="61adf-117">A <see cref="T:Microsoft.WindowsAzure.Storage.StorageLocation" /> enumeration value.</span></span></param>
        <summary>
            <span data-ttu-id="61adf-118">作成、<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />分単位のメトリック ログ テーブルを照会するためのオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="61adf-118">Creates a <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" /> object for querying a minute metrics log table.</span></span>
            </summary>
        <returns><span data-ttu-id="61adf-119"><see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="61adf-119">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCapacityTable">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.CloudTable GetCapacityTable ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.Table.CloudTable GetCapacityTable() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.GetCapacityTable" />
      <MemberSignature Language="VB.NET" Value="Public Function GetCapacityTable () As CloudTable" />
      <MemberSignature Language="F#" Value="member this.GetCapacityTable : unit -&gt; Microsoft.WindowsAzure.Storage.Table.CloudTable" Usage="cloudAnalyticsClient.GetCapacityTable " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.CloudTable</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="61adf-120">Blob サービスの容量メトリック テーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="61adf-120">Gets the capacity metrics table for the Blob service.</span></span>
            </summary>
        <returns><span data-ttu-id="61adf-121"><see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTable" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="61adf-121">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTable" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHourMetricsTable">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.CloudTable GetHourMetricsTable (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.Table.CloudTable GetHourMetricsTable(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.GetHourMetricsTable(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetHourMetricsTable (service As StorageService) As CloudTable" />
      <MemberSignature Language="F#" Value="member this.GetHourMetricsTable : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService -&gt; Microsoft.WindowsAzure.Storage.Table.CloudTable" Usage="cloudAnalyticsClient.GetHourMetricsTable service" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.CloudTable</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
      </Parameters>
      <Docs>
        <param name="service"><span data-ttu-id="61adf-122"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> 列挙値。</span><span class="sxs-lookup"><span data-stu-id="61adf-122">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> enumeration value.</span></span></param>
        <summary>
            <span data-ttu-id="61adf-123">指定した記憶域サービスの時間単位のメトリックのテーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="61adf-123">Gets the hourly metrics table for the specified storage service.</span></span>
            </summary>
        <returns><span data-ttu-id="61adf-124"><see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTable" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="61adf-124">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTable" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHourMetricsTable">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.CloudTable GetHourMetricsTable (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, Microsoft.WindowsAzure.Storage.StorageLocation location);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.Table.CloudTable GetHourMetricsTable(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, valuetype Microsoft.WindowsAzure.Storage.StorageLocation location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.GetHourMetricsTable(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService,Microsoft.WindowsAzure.Storage.StorageLocation)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetHourMetricsTable (service As StorageService, location As StorageLocation) As CloudTable" />
      <MemberSignature Language="F#" Value="member this.GetHourMetricsTable : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService * Microsoft.WindowsAzure.Storage.StorageLocation -&gt; Microsoft.WindowsAzure.Storage.Table.CloudTable" Usage="cloudAnalyticsClient.GetHourMetricsTable (service, location)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.CloudTable</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
        <Parameter Name="location" Type="Microsoft.WindowsAzure.Storage.StorageLocation" />
      </Parameters>
      <Docs>
        <param name="service"><span data-ttu-id="61adf-125"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> 列挙値。</span><span class="sxs-lookup"><span data-stu-id="61adf-125">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> enumeration value.</span></span></param>
        <param name="location"><span data-ttu-id="61adf-126"><see cref="T:Microsoft.WindowsAzure.Storage.StorageLocation" /> 列挙値。</span><span class="sxs-lookup"><span data-stu-id="61adf-126">A <see cref="T:Microsoft.WindowsAzure.Storage.StorageLocation" /> enumeration value.</span></span></param>
        <summary>
            <span data-ttu-id="61adf-127">指定した記憶域サービスの時間単位のメトリックのテーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="61adf-127">Gets the hourly metrics table for the specified storage service.</span></span>
            </summary>
        <returns><span data-ttu-id="61adf-128"><see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTable" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="61adf-128">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTable" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetLogDirectory">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory GetLogDirectory (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory GetLogDirectory(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.GetLogDirectory(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetLogDirectory (service As StorageService) As CloudBlobDirectory" />
      <MemberSignature Language="F#" Value="member this.GetLogDirectory : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" Usage="cloudAnalyticsClient.GetLogDirectory service" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
      </Parameters>
      <Docs>
        <param name="service"><span data-ttu-id="61adf-129"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> 列挙値。</span><span class="sxs-lookup"><span data-stu-id="61adf-129">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> enumeration value.</span></span></param>
        <summary>
            <span data-ttu-id="61adf-130">取得、<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" />を指定した記憶域サービスのログを含むオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="61adf-130">Gets a <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" /> object containing the logs for the specified storage service.</span></span>
            </summary>
        <returns><span data-ttu-id="61adf-131"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="61adf-131">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMinuteMetricsTable">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.CloudTable GetMinuteMetricsTable (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.Table.CloudTable GetMinuteMetricsTable(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.GetMinuteMetricsTable(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMinuteMetricsTable (service As StorageService) As CloudTable" />
      <MemberSignature Language="F#" Value="member this.GetMinuteMetricsTable : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService -&gt; Microsoft.WindowsAzure.Storage.Table.CloudTable" Usage="cloudAnalyticsClient.GetMinuteMetricsTable service" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.CloudTable</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
      </Parameters>
      <Docs>
        <param name="service"><span data-ttu-id="61adf-132"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> 列挙値。</span><span class="sxs-lookup"><span data-stu-id="61adf-132">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> enumeration value.</span></span></param>
        <summary>
            <span data-ttu-id="61adf-133">指定した記憶域サービスの分単位のメトリックのテーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="61adf-133">Gets the minute metrics table for the specified storage service.</span></span>
            </summary>
        <returns><span data-ttu-id="61adf-134"><see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTable" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="61adf-134">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTable" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMinuteMetricsTable">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.CloudTable GetMinuteMetricsTable (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, Microsoft.WindowsAzure.Storage.StorageLocation location);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.Table.CloudTable GetMinuteMetricsTable(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, valuetype Microsoft.WindowsAzure.Storage.StorageLocation location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.GetMinuteMetricsTable(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService,Microsoft.WindowsAzure.Storage.StorageLocation)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMinuteMetricsTable (service As StorageService, location As StorageLocation) As CloudTable" />
      <MemberSignature Language="F#" Value="member this.GetMinuteMetricsTable : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService * Microsoft.WindowsAzure.Storage.StorageLocation -&gt; Microsoft.WindowsAzure.Storage.Table.CloudTable" Usage="cloudAnalyticsClient.GetMinuteMetricsTable (service, location)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.CloudTable</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
        <Parameter Name="location" Type="Microsoft.WindowsAzure.Storage.StorageLocation" />
      </Parameters>
      <Docs>
        <param name="service"><span data-ttu-id="61adf-135"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> 列挙値。</span><span class="sxs-lookup"><span data-stu-id="61adf-135">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> enumeration value.</span></span></param>
        <param name="location"><span data-ttu-id="61adf-136"><see cref="T:Microsoft.WindowsAzure.Storage.StorageLocation" /> 列挙値。</span><span class="sxs-lookup"><span data-stu-id="61adf-136">A <see cref="T:Microsoft.WindowsAzure.Storage.StorageLocation" /> enumeration value.</span></span></param>
        <summary>
            <span data-ttu-id="61adf-137">指定した記憶域サービスの分単位のメトリックのテーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="61adf-137">Gets the minute metrics table for the specified storage service.</span></span>
            </summary>
        <returns><span data-ttu-id="61adf-138"><see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTable" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="61adf-138">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTable" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListLogRecords">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ListLogRecords (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ListLogRecords(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ListLogRecords(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService)" />
      <MemberSignature Language="VB.NET" Value="Public Function ListLogRecords (service As StorageService) As IEnumerable(Of LogRecord)" />
      <MemberSignature Language="F#" Value="member this.ListLogRecords : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;" Usage="cloudAnalyticsClient.ListLogRecords service" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
      </Parameters>
      <Docs>
        <param name="service"><span data-ttu-id="61adf-139"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> 列挙値。</span><span class="sxs-lookup"><span data-stu-id="61adf-139">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> enumeration value.</span></span></param>
        <summary>
            <span data-ttu-id="61adf-140">遅延を取得、分析のログ レコードの列挙可能なコレクションを返します。</span><span class="sxs-lookup"><span data-stu-id="61adf-140">Returns an enumerable collection of Analytics log records, retrieved lazily.</span></span>
            </summary>
        <returns><span data-ttu-id="61adf-141">実装するオブジェクトの列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.Analytics.LogRecord" />遅れてが取得されます。</span><span class="sxs-lookup"><span data-stu-id="61adf-141">An enumerable collection of objects that implement <see cref="T:Microsoft.WindowsAzure.Storage.Analytics.LogRecord" /> and are retrieved lazily.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListLogRecords">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ListLogRecords (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ListLogRecords(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ListLogRecords(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="member this.ListLogRecords : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;" Usage="cloudAnalyticsClient.ListLogRecords (service, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="service"><span data-ttu-id="61adf-142"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> 列挙値。</span><span class="sxs-lookup"><span data-stu-id="61adf-142">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> enumeration value.</span></span></param>
        <param name="options"><span data-ttu-id="61adf-143">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="61adf-143">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="61adf-144"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="61adf-144">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="61adf-145">遅延を取得、分析のログ レコードの列挙可能なコレクションを返します。</span><span class="sxs-lookup"><span data-stu-id="61adf-145">Returns an enumerable collection of Analytics log records, retrieved lazily.</span></span>
            </summary>
        <returns><span data-ttu-id="61adf-146">実装するオブジェクトの列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.Analytics.LogRecord" />遅れてが取得されます。</span><span class="sxs-lookup"><span data-stu-id="61adf-146">An enumerable collection of objects that implement <see cref="T:Microsoft.WindowsAzure.Storage.Analytics.LogRecord" /> and are retrieved lazily.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListLogRecords">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ListLogRecords (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, DateTimeOffset startTime, Nullable&lt;DateTimeOffset&gt; endTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ListLogRecords(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, valuetype System.DateTimeOffset startTime, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; endTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ListLogRecords(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService,System.DateTimeOffset,System.Nullable{System.DateTimeOffset})" />
      <MemberSignature Language="VB.NET" Value="Public Function ListLogRecords (service As StorageService, startTime As DateTimeOffset, endTime As Nullable(Of DateTimeOffset)) As IEnumerable(Of LogRecord)" />
      <MemberSignature Language="F#" Value="member this.ListLogRecords : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService * DateTimeOffset * Nullable&lt;DateTimeOffset&gt; -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;" Usage="cloudAnalyticsClient.ListLogRecords (service, startTime, endTime)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
        <Parameter Name="startTime" Type="System.DateTimeOffset" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
      </Parameters>
      <Docs>
        <param name="service"><span data-ttu-id="61adf-147"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> 列挙値。</span><span class="sxs-lookup"><span data-stu-id="61adf-147">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> enumeration value.</span></span></param>
        <param name="startTime"><span data-ttu-id="61adf-148">A<see cref="T:System.DateTimeOffset" />ログを取得する時間の範囲の開始を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="61adf-148">A <see cref="T:System.DateTimeOffset" /> object representing the start of the time range for which logs should be retrieved.</span></span></param>
        <param name="endTime"><span data-ttu-id="61adf-149">A<see cref="T:System.DateTimeOffset" />ログを取得する時間の範囲の終わりを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="61adf-149">A <see cref="T:System.DateTimeOffset" /> object representing the end of the time range for which logs should be retrieved.</span></span></param>
        <summary>
            <span data-ttu-id="61adf-150">遅延を取得、分析のログ レコードの列挙可能なコレクションを返します。</span><span class="sxs-lookup"><span data-stu-id="61adf-150">Returns an enumerable collection of Analytics log records, retrieved lazily.</span></span>
            </summary>
        <returns><span data-ttu-id="61adf-151">実装するオブジェクトの列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.Analytics.LogRecord" />遅れてが取得されます。</span><span class="sxs-lookup"><span data-stu-id="61adf-151">An enumerable collection of objects that implement <see cref="T:Microsoft.WindowsAzure.Storage.Analytics.LogRecord" /> and are retrieved lazily.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListLogRecords">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ListLogRecords (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, DateTimeOffset startTime, Nullable&lt;DateTimeOffset&gt; endTime, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ListLogRecords(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, valuetype System.DateTimeOffset startTime, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; endTime, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ListLogRecords(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService,System.DateTimeOffset,System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="member this.ListLogRecords : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService * DateTimeOffset * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;" Usage="cloudAnalyticsClient.ListLogRecords (service, startTime, endTime, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
        <Parameter Name="startTime" Type="System.DateTimeOffset" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="service"><span data-ttu-id="61adf-152"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> 列挙値。</span><span class="sxs-lookup"><span data-stu-id="61adf-152">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> enumeration value.</span></span></param>
        <param name="startTime"><span data-ttu-id="61adf-153">A<see cref="T:System.DateTimeOffset" />ログを取得する時間の範囲の開始を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="61adf-153">A <see cref="T:System.DateTimeOffset" /> object representing the start of the time range for which logs should be retrieved.</span></span></param>
        <param name="endTime"><span data-ttu-id="61adf-154">A<see cref="T:System.DateTimeOffset" />ログを取得する時間の範囲の終わりを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="61adf-154">A <see cref="T:System.DateTimeOffset" /> object representing the end of the time range for which logs should be retrieved.</span></span></param>
        <param name="options"><span data-ttu-id="61adf-155">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="61adf-155">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="61adf-156"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="61adf-156">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="61adf-157">遅延を取得、分析のログ レコードの列挙可能なコレクションを返します。</span><span class="sxs-lookup"><span data-stu-id="61adf-157">Returns an enumerable collection of Analytics log records, retrieved lazily.</span></span>
            </summary>
        <returns><span data-ttu-id="61adf-158">実装するオブジェクトの列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.Analytics.LogRecord" />遅れてが取得されます。</span><span class="sxs-lookup"><span data-stu-id="61adf-158">An enumerable collection of objects that implement <see cref="T:Microsoft.WindowsAzure.Storage.Analytics.LogRecord" /> and are retrieved lazily.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListLogs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; ListLogs (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; ListLogs(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ListLogs(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService)" />
      <MemberSignature Language="VB.NET" Value="Public Function ListLogs (service As StorageService) As IEnumerable(Of ICloudBlob)" />
      <MemberSignature Language="F#" Value="member this.ListLogs : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;" Usage="cloudAnalyticsClient.ListLogs service" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
      </Parameters>
      <Docs>
        <param name="service"><span data-ttu-id="61adf-159"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> 列挙値。</span><span class="sxs-lookup"><span data-stu-id="61adf-159">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> enumeration value.</span></span></param>
        <summary>
            <span data-ttu-id="61adf-160">分析ログ レコードを含むログ blob の列挙可能なコレクションを返します。</span><span class="sxs-lookup"><span data-stu-id="61adf-160">Returns an enumerable collection of log blobs containing Analytics log records.</span></span> <span data-ttu-id="61adf-161">遅延は、blob を取得します。</span><span class="sxs-lookup"><span data-stu-id="61adf-161">The blobs are retrieved lazily.</span></span>
            </summary>
        <returns><span data-ttu-id="61adf-162">実装するオブジェクトの列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" />遅れてが取得されます。</span><span class="sxs-lookup"><span data-stu-id="61adf-162">An enumerable collection of objects that implement <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" /> and are retrieved lazily.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListLogs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; ListLogs (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, DateTimeOffset startTime, Nullable&lt;DateTimeOffset&gt; endTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; ListLogs(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, valuetype System.DateTimeOffset startTime, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; endTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ListLogs(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService,System.DateTimeOffset,System.Nullable{System.DateTimeOffset})" />
      <MemberSignature Language="VB.NET" Value="Public Function ListLogs (service As StorageService, startTime As DateTimeOffset, endTime As Nullable(Of DateTimeOffset)) As IEnumerable(Of ICloudBlob)" />
      <MemberSignature Language="F#" Value="member this.ListLogs : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService * DateTimeOffset * Nullable&lt;DateTimeOffset&gt; -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;" Usage="cloudAnalyticsClient.ListLogs (service, startTime, endTime)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
        <Parameter Name="startTime" Type="System.DateTimeOffset" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
      </Parameters>
      <Docs>
        <param name="service"><span data-ttu-id="61adf-163"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> 列挙値。</span><span class="sxs-lookup"><span data-stu-id="61adf-163">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> enumeration value.</span></span></param>
        <param name="startTime"><span data-ttu-id="61adf-164">A<see cref="T:System.DateTimeOffset" />ログの取得の開始時刻を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="61adf-164">A <see cref="T:System.DateTimeOffset" /> object representing the start time for which logs should be retrieved.</span></span></param>
        <param name="endTime"><span data-ttu-id="61adf-165">A<see cref="T:System.DateTimeOffset" />ログの取得の終了時刻を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="61adf-165">A <see cref="T:System.DateTimeOffset" /> object representing the end time for which logs should be retrieved.</span></span></param>
        <summary>
            <span data-ttu-id="61adf-166">分析ログ レコードを含むログ blob の列挙可能なコレクションを返します。</span><span class="sxs-lookup"><span data-stu-id="61adf-166">Returns an enumerable collection of log blobs containing Analytics log records.</span></span> <span data-ttu-id="61adf-167">遅延は、blob を取得します。</span><span class="sxs-lookup"><span data-stu-id="61adf-167">The blobs are retrieved lazily.</span></span>
            </summary>
        <returns><span data-ttu-id="61adf-168">実装するオブジェクトの列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" />遅れてが取得されます。</span><span class="sxs-lookup"><span data-stu-id="61adf-168">An enumerable collection of objects that implement <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" /> and are retrieved lazily.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListLogs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; ListLogs (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations operations, Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails details, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; ListLogs(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations operations, valuetype Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails details, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ListLogs(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService,Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations,Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="member this.ListLogs : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService * Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations * Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;" Usage="cloudAnalyticsClient.ListLogs (service, operations, details, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations" />
        <Parameter Name="details" Type="Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="service"><span data-ttu-id="61adf-169"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> 列挙値。</span><span class="sxs-lookup"><span data-stu-id="61adf-169">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> enumeration value.</span></span></param>
        <param name="operations"><span data-ttu-id="61adf-170">A<see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations" />ログ blob をフィルター処理するログ記録操作の種類を示す列挙値。</span><span class="sxs-lookup"><span data-stu-id="61adf-170">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations" /> enumeration value that indicates the types of logging operations on which to filter the log blobs.</span></span></param>
        <param name="details"><span data-ttu-id="61adf-171">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" /> blob のメタデータを返す必要があるかどうかを示す列挙値。</span><span class="sxs-lookup"><span data-stu-id="61adf-171">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" /> enumeration value that indicates whether or not blob metadata should be returned.</span></span> <span data-ttu-id="61adf-172">のみ<c>None</c>と<c>メタデータ</c>は有効な値です。</span><span class="sxs-lookup"><span data-stu-id="61adf-172">Only <c>None</c> and <c>Metadata</c> are valid values.</span></span> </param>
        <param name="options"><span data-ttu-id="61adf-173">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="61adf-173">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="61adf-174"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="61adf-174">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="61adf-175">分析ログ レコードを含むログ blob の列挙可能なコレクションを返します。</span><span class="sxs-lookup"><span data-stu-id="61adf-175">Returns an enumerable collection of log blobs containing Analytics log records.</span></span> <span data-ttu-id="61adf-176">遅延は、blob を取得します。</span><span class="sxs-lookup"><span data-stu-id="61adf-176">The blobs are retrieved lazily.</span></span>
            </summary>
        <returns><span data-ttu-id="61adf-177">実装するオブジェクトの列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" />遅れてが取得されます。</span><span class="sxs-lookup"><span data-stu-id="61adf-177">An enumerable collection of objects that implement <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" /> and are retrieved lazily.</span></span></returns>
        <remarks><span data-ttu-id="61adf-178">ログ記録操作を指定するが入力したメモ、<paramref name="operations" />パラメーターで指定されたログ記録操作を含む任意の分析ログ blob が返される場合、場合でも、そのログ blob には、その他の種類のログ記録操作も含まれています。</span><span class="sxs-lookup"><span data-stu-id="61adf-178">Note that specifying a logging operation type for the <paramref name="operations" /> parameter will return any Analytics log blob that contains the specified logging operation, even if that log blob also includes other types of logging operations.</span></span> <span data-ttu-id="61adf-179">現在サポートされている唯一メモは値を<paramref name="details" />パラメーターは<c>None</c>と<c>メタデータ</c>です。</span><span class="sxs-lookup"><span data-stu-id="61adf-179">Also note that the only currently supported values for the <paramref name="details" /> parameter are <c>None</c> and <c>Metadata</c>.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ListLogs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; ListLogs (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, DateTimeOffset startTime, Nullable&lt;DateTimeOffset&gt; endTime, Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations operations, Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails details, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; ListLogs(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, valuetype System.DateTimeOffset startTime, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; endTime, valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations operations, valuetype Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails details, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ListLogs(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService,System.DateTimeOffset,System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations,Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="member this.ListLogs : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService * DateTimeOffset * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations * Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;" Usage="cloudAnalyticsClient.ListLogs (service, startTime, endTime, operations, details, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
        <Parameter Name="startTime" Type="System.DateTimeOffset" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations" />
        <Parameter Name="details" Type="Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="service"><span data-ttu-id="61adf-180"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> 列挙値。</span><span class="sxs-lookup"><span data-stu-id="61adf-180">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> enumeration value.</span></span></param>
        <param name="startTime"><span data-ttu-id="61adf-181">A<see cref="T:System.DateTimeOffset" />ログを取得する時間の範囲の開始を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="61adf-181">A <see cref="T:System.DateTimeOffset" /> object representing the start of the time range for which logs should be retrieved.</span></span></param>
        <param name="endTime"><span data-ttu-id="61adf-182">A<see cref="T:System.DateTimeOffset" />ログを取得する時間の範囲の終わりを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="61adf-182">A <see cref="T:System.DateTimeOffset" /> object representing the end of the time range for which logs should be retrieved.</span></span></param>
        <param name="operations"><span data-ttu-id="61adf-183">A<see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations" />ログ blob をフィルター処理するログ記録操作の種類を示す列挙値。</span><span class="sxs-lookup"><span data-stu-id="61adf-183">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations" /> enumeration value that indicates the types of logging operations on which to filter the log blobs.</span></span></param>
        <param name="details"><span data-ttu-id="61adf-184">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" /> blob のメタデータを返す必要があるかどうかを示す列挙値。</span><span class="sxs-lookup"><span data-stu-id="61adf-184">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" /> enumeration value that indicates whether or not blob metadata should be returned.</span></span> <span data-ttu-id="61adf-185">のみ<c>None</c>と<c>メタデータ</c>は有効な値です。</span><span class="sxs-lookup"><span data-stu-id="61adf-185">Only <c>None</c> and <c>Metadata</c> are valid values.</span></span> </param>
        <param name="options"><span data-ttu-id="61adf-186">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="61adf-186">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="61adf-187"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="61adf-187">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="61adf-188">分析ログ レコードを含むログ blob の列挙可能なコレクションを返します。</span><span class="sxs-lookup"><span data-stu-id="61adf-188">Returns an enumerable collection of log blobs containing Analytics log records.</span></span> <span data-ttu-id="61adf-189">遅延は、blob を取得します。</span><span class="sxs-lookup"><span data-stu-id="61adf-189">The blobs are retrieved lazily.</span></span>
            </summary>
        <returns><span data-ttu-id="61adf-190">実装するオブジェクトの列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" />遅れてが取得されます。</span><span class="sxs-lookup"><span data-stu-id="61adf-190">An enumerable collection of objects that implement <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" /> and are retrieved lazily.</span></span></returns>
        <remarks><span data-ttu-id="61adf-191">ログ記録操作を指定するが入力したメモ、<paramref name="operations" />パラメーターで指定されたログ記録操作を含む任意の分析ログ blob が返される場合、場合でも、そのログ blob には、その他の種類のログ記録操作も含まれています。</span><span class="sxs-lookup"><span data-stu-id="61adf-191">Note that specifying a logging operation type for the <paramref name="operations" /> parameter will return any Analytics log blob that contains the specified logging operation, even if that log blob also includes other types of logging operations.</span></span> <span data-ttu-id="61adf-192">現在サポートされている唯一メモは値を<paramref name="details" />パラメーターは<c>None</c>と<c>メタデータ</c>です。</span><span class="sxs-lookup"><span data-stu-id="61adf-192">Also note that the only currently supported values for the <paramref name="details" /> parameter are <c>None</c> and <c>Metadata</c>.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ParseLogBlob">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ParseLogBlob (Microsoft.WindowsAzure.Storage.Blob.ICloudBlob logBlob);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ParseLogBlob(class Microsoft.WindowsAzure.Storage.Blob.ICloudBlob logBlob) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ParseLogBlob(Microsoft.WindowsAzure.Storage.Blob.ICloudBlob)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ParseLogBlob (logBlob As ICloudBlob) As IEnumerable(Of LogRecord)" />
      <MemberSignature Language="F#" Value="static member ParseLogBlob : Microsoft.WindowsAzure.Storage.Blob.ICloudBlob -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;" Usage="Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ParseLogBlob logBlob" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="logBlob" Type="Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" />
      </Parameters>
      <Docs>
        <param name="logBlob"><span data-ttu-id="61adf-193"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" />ログ レコードを解析する対象のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="61adf-193">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" /> object from which to parse log records.</span></span></param>
        <summary>
            <span data-ttu-id="61adf-194">遅延を取得、分析のログ レコードの列挙可能なコレクションを返します。</span><span class="sxs-lookup"><span data-stu-id="61adf-194">Returns an enumerable collection of Analytics log records, retrieved lazily.</span></span>
            </summary>
        <returns><span data-ttu-id="61adf-195">実装するオブジェクトの列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.Analytics.LogRecord" />遅れてが取得されます。</span><span class="sxs-lookup"><span data-stu-id="61adf-195">An enumerable collection of objects that implement <see cref="T:Microsoft.WindowsAzure.Storage.Analytics.LogRecord" /> and are retrieved lazily.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParseLogBlobs">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ParseLogBlobs (System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; logBlobs);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ParseLogBlobs(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; logBlobs) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ParseLogBlobs(System.Collections.Generic.IEnumerable{Microsoft.WindowsAzure.Storage.Blob.ICloudBlob})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ParseLogBlobs (logBlobs As IEnumerable(Of ICloudBlob)) As IEnumerable(Of LogRecord)" />
      <MemberSignature Language="F#" Value="static member ParseLogBlobs : seq&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;" Usage="Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ParseLogBlobs logBlobs" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="logBlobs" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;" />
      </Parameters>
      <Docs>
        <param name="logBlobs"><span data-ttu-id="61adf-196">列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" />ログ レコードを解析するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="61adf-196">An enumerable collection of <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" /> objects from which to parse log records.</span></span></param>
        <summary>
            <span data-ttu-id="61adf-197">遅延を取得、分析のログ レコードの列挙可能なコレクションを返します。</span><span class="sxs-lookup"><span data-stu-id="61adf-197">Returns an enumerable collection of Analytics log records, retrieved lazily.</span></span>
            </summary>
        <returns><span data-ttu-id="61adf-198">実装するオブジェクトの列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.Analytics.LogRecord" />遅れてが取得されます。</span><span class="sxs-lookup"><span data-stu-id="61adf-198">An enumerable collection of objects that implement <see cref="T:Microsoft.WindowsAzure.Storage.Analytics.LogRecord" /> and are retrieved lazily.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParseLogStream">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ParseLogStream (System.IO.Stream stream);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ParseLogStream(class System.IO.Stream stream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ParseLogStream(System.IO.Stream)" />
      <MemberSignature Language="F#" Value="static member ParseLogStream : System.IO.Stream -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;" Usage="Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ParseLogStream stream" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="stream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="stream"><span data-ttu-id="61adf-199"><see cref="T:System.IO.Stream" />ログ レコードを解析する対象のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="61adf-199">The <see cref="T:System.IO.Stream" /> object from which to parse log records.</span></span></param>
        <summary>
            <span data-ttu-id="61adf-200">遅延を取得、分析のログ レコードの列挙可能なコレクションを返します。</span><span class="sxs-lookup"><span data-stu-id="61adf-200">Returns an enumerable collection of Analytics log records, retrieved lazily.</span></span>
            </summary>
        <returns><span data-ttu-id="61adf-201">実装するオブジェクトの列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.Analytics.LogRecord" />遅れてが取得されます。</span><span class="sxs-lookup"><span data-stu-id="61adf-201">An enumerable collection of objects that implement <see cref="T:Microsoft.WindowsAzure.Storage.Analytics.LogRecord" /> and are retrieved lazily.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>