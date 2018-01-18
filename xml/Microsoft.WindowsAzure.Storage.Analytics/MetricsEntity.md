<Type Name="MetricsEntity" FullName="Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity">
  <TypeSignature Language="C#" Value="public class MetricsEntity : Microsoft.WindowsAzure.Storage.Table.TableEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MetricsEntity extends Microsoft.WindowsAzure.Storage.Table.TableEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity" />
  <TypeSignature Language="VB.NET" Value="Public Class MetricsEntity&#xA;Inherits TableEntity" />
  <TypeSignature Language="F#" Value="type MetricsEntity = class&#xA;    inherit TableEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.WindowsAzure.Storage.Table.TableEntity</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="fb194-101">Storage analytics のメトリック テーブル内のエンティティを表します。</span><span class="sxs-lookup"><span data-stu-id="fb194-101">Represents an entity in a storage analytics metrics table.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricsEntity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="fb194-102"><see cref="T:Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fb194-102">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessType">
      <MemberSignature Language="C#" Value="public string AccessType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AccessType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.AccessType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccessType As String" />
      <MemberSignature Language="F#" Value="member this.AccessType : string" Usage="Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.AccessType" />
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
            <span data-ttu-id="fb194-103">ログイン アクセスの種類を示す、メトリック エンティティの AccessType プロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="fb194-103">Gets the AccessType property for the metrics entity, indicating the type of access logged.</span></span>
            </summary>
        <value><span data-ttu-id="fb194-104">メトリックのエンティティのアクセスの種類を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="fb194-104">A string containing the access type for the metrics entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AnonymousAuthorizationError">
      <MemberSignature Language="C#" Value="public long AnonymousAuthorizationError { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 AnonymousAuthorizationError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.AnonymousAuthorizationError" />
      <MemberSignature Language="VB.NET" Value="Public Property AnonymousAuthorizationError As Long" />
      <MemberSignature Language="F#" Value="member this.AnonymousAuthorizationError : int64 with get, set" Usage="Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.AnonymousAuthorizationError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb194-105">取得または、AuthorizationError が返された匿名要求の数を示すメトリック エンティティは、AnonymousAuthorizationError プロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="fb194-105">Gets or sets the AnonymousAuthorizationError property for the metrics entity, indicating the number of anonymous requests that returned an AuthorizationError.</span></span>
            </summary>
        <value><span data-ttu-id="fb194-106">メトリックのエンティティに対して、AuthorizationError が返された匿名要求の数を表す long 値です。</span><span class="sxs-lookup"><span data-stu-id="fb194-106">A long containing the number of anonymous requests that returned an AuthorizationError for the metrics entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AnonymousClientOtherError">
      <MemberSignature Language="C#" Value="public long AnonymousClientOtherError { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 AnonymousClientOtherError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.AnonymousClientOtherError" />
      <MemberSignature Language="VB.NET" Value="Public Property AnonymousClientOtherError As Long" />
      <MemberSignature Language="F#" Value="member this.AnonymousClientOtherError : int64 with get, set" Usage="Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.AnonymousClientOtherError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb194-107">取得または、ClientOtherError が返された匿名要求の数を示すメトリック エンティティは、AnonymousClientOtherError プロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="fb194-107">Gets or sets the AnonymousClientOtherError property for the metrics entity, indicating the number of anonymous requests that returned an ClientOtherError.</span></span>
            </summary>
        <value><span data-ttu-id="fb194-108">メトリックのエンティティの ClientOtherError が返された匿名要求の数を表す long 値です。</span><span class="sxs-lookup"><span data-stu-id="fb194-108">A long containing the number of anonymous requests that returned a ClientOtherError for the metrics entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AnonymousClientTimeoutError">
      <MemberSignature Language="C#" Value="public long AnonymousClientTimeoutError { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 AnonymousClientTimeoutError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.AnonymousClientTimeoutError" />
      <MemberSignature Language="VB.NET" Value="Public Property AnonymousClientTimeoutError As Long" />
      <MemberSignature Language="F#" Value="member this.AnonymousClientTimeoutError : int64 with get, set" Usage="Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.AnonymousClientTimeoutError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb194-109">取得または、ClientTimeoutError が返された匿名要求の数を示すメトリック エンティティは、AnonymousClientTimeoutError プロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="fb194-109">Gets or sets the AnonymousClientTimeoutError property for the metrics entity, indicating the number of anonymous requests that returned a ClientTimeoutError.</span></span>
            </summary>
        <value><span data-ttu-id="fb194-110">メトリックのエンティティの ClientTimeoutError が返された匿名要求の数を表す long 値です。</span><span class="sxs-lookup"><span data-stu-id="fb194-110">A long containing the number of anonymous requests that returned a ClientTimeoutError for the metrics entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AnonymousNetworkError">
      <MemberSignature Language="C#" Value="public long AnonymousNetworkError { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 AnonymousNetworkError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.AnonymousNetworkError" />
      <MemberSignature Language="VB.NET" Value="Public Property AnonymousNetworkError As Long" />
      <MemberSignature Language="F#" Value="member this.AnonymousNetworkError : int64 with get, set" Usage="Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.AnonymousNetworkError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb194-111">取得または、NetworkError が返された匿名要求の数を示すメトリック エンティティは、AnonymousNetworkError プロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="fb194-111">Gets or sets the AnonymousNetworkError property for the metrics entity, indicating the number of anonymous requests that returned a NetworkError.</span></span>
            </summary>
        <value><span data-ttu-id="fb194-112">メトリックのエンティティの NetworkError が返された匿名要求の数を表す long 値です。</span><span class="sxs-lookup"><span data-stu-id="fb194-112">A long containing the number of anonymous requests that returned a NetworkError for the metrics entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AnonymousServerOtherError">
      <MemberSignature Language="C#" Value="public long AnonymousServerOtherError { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 AnonymousServerOtherError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.AnonymousServerOtherError" />
      <MemberSignature Language="VB.NET" Value="Public Property AnonymousServerOtherError As Long" />
      <MemberSignature Language="F#" Value="member this.AnonymousServerOtherError : int64 with get, set" Usage="Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.AnonymousServerOtherError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb194-113">取得または、ServerOtherError が返された匿名要求の数を示すメトリック エンティティは、AnonymousServerOtherError プロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="fb194-113">Gets or sets the AnonymousServerOtherError property for the metrics entity, indicating the number of anonymous requests that returned a ServerOtherError.</span></span>
            </summary>
        <value><span data-ttu-id="fb194-114">メトリックのエンティティの ServerOtherError が返された匿名要求の数を表す long 値です。</span><span class="sxs-lookup"><span data-stu-id="fb194-114">A long containing the number of anonymous requests that returned a ServerOtherError for the metrics entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AnonymousServerTimeoutError">
      <MemberSignature Language="C#" Value="public long AnonymousServerTimeoutError { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 AnonymousServerTimeoutError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.AnonymousServerTimeoutError" />
      <MemberSignature Language="VB.NET" Value="Public Property AnonymousServerTimeoutError As Long" />
      <MemberSignature Language="F#" Value="member this.AnonymousServerTimeoutError : int64 with get, set" Usage="Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.AnonymousServerTimeoutError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb194-115">取得または、ServerTimeoutError が返された匿名要求の数を示すメトリック エンティティは、AnonymousServerTimeoutError プロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="fb194-115">Gets or sets the AnonymousServerTimeoutError property for the metrics entity, indicating the number of anonymous requests that returned a ServerTimeoutError.</span></span>
            </summary>
        <value><span data-ttu-id="fb194-116">メトリックのエンティティの ServerTimeoutError が返された匿名要求の数を表す long 値です。</span><span class="sxs-lookup"><span data-stu-id="fb194-116">A long containing the number of anonymous requests that returned a ServerTimeoutError for the metrics entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AnonymousSuccess">
      <MemberSignature Language="C#" Value="public long AnonymousSuccess { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 AnonymousSuccess" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.AnonymousSuccess" />
      <MemberSignature Language="VB.NET" Value="Public Property AnonymousSuccess As Long" />
      <MemberSignature Language="F#" Value="member this.AnonymousSuccess : int64 with get, set" Usage="Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.AnonymousSuccess" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb194-117">取得または成功した匿名要求の数を示すメトリック エンティティの AnonymousSuccess プロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="fb194-117">Gets or sets the AnonymousSuccess property for the metrics entity, indicating the number of successful anonymous requests.</span></span>
            </summary>
        <value><span data-ttu-id="fb194-118">メトリックのエンティティの成功した匿名要求の数を表す long 値です。</span><span class="sxs-lookup"><span data-stu-id="fb194-118">A long containing the number of successful anonymous requests for the metrics entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AnonymousThrottlingError">
      <MemberSignature Language="C#" Value="public long AnonymousThrottlingError { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 AnonymousThrottlingError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.AnonymousThrottlingError" />
      <MemberSignature Language="VB.NET" Value="Public Property AnonymousThrottlingError As Long" />
      <MemberSignature Language="F#" Value="member this.AnonymousThrottlingError : int64 with get, set" Usage="Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.AnonymousThrottlingError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb194-119">取得または、ThrottlingError が返された匿名要求の数を示すメトリック エンティティは、AnonymousThrottlingError プロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="fb194-119">Gets or sets the AnonymousThrottlingError property for the metrics entity, indicating the number of anonymous requests that returned a ThrottlingError.</span></span>
            </summary>
        <value><span data-ttu-id="fb194-120">メトリックのエンティティの ThrottlingError が返された匿名要求の数を表す long 値です。</span><span class="sxs-lookup"><span data-stu-id="fb194-120">A long containing the number of anonymous requests that returned a ThrottlingError for the metrics entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthorizationError">
      <MemberSignature Language="C#" Value="public long AuthorizationError { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 AuthorizationError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.AuthorizationError" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthorizationError As Long" />
      <MemberSignature Language="F#" Value="member this.AuthorizationError : int64 with get, set" Usage="Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.AuthorizationError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb194-121">取得または、AuthorizationError が返された認証済みの要求の数を示すメトリック エンティティの AuthorizationError プロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="fb194-121">Gets or sets the AuthorizationError property for the metrics entity, indicating the number of authenticated requests that returned an AuthorizationError.</span></span>
            </summary>
        <value><span data-ttu-id="fb194-122">メトリックのエンティティに対して、AuthorizationError が返された認証済みの要求の数を表す long 値です。</span><span class="sxs-lookup"><span data-stu-id="fb194-122">A long containing the number of authenticated requests that returned an AuthorizationError for the metrics entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Availability">
      <MemberSignature Language="C#" Value="public double Availability { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 Availability" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.Availability" />
      <MemberSignature Language="VB.NET" Value="Public Property Availability As Double" />
      <MemberSignature Language="F#" Value="member this.Availability : double with get, set" Usage="Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.Availability" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb194-123">取得または可用性の割合を示すメトリック エンティティの可用性プロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="fb194-123">Gets or sets the Availability property for the metrics entity, indicating the percentage of availability.</span></span>
            </summary>
        <value><span data-ttu-id="fb194-124">メトリックのエンティティの可用性の割合を表す double 値。</span><span class="sxs-lookup"><span data-stu-id="fb194-124">A double containing the percentage of availability for the metrics entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AverageE2ELatency">
      <MemberSignature Language="C#" Value="public double AverageE2ELatency { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 AverageE2ELatency" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.AverageE2ELatency" />
      <MemberSignature Language="VB.NET" Value="Public Property AverageE2ELatency As Double" />
      <MemberSignature Language="F#" Value="member this.AverageE2ELatency : double with get, set" Usage="Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.AverageE2ELatency" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb194-125">取得または成功した要求の平均のエンド ツー エンドの待機時間を示すメトリック エンティティの AverageE2ELatency プロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="fb194-125">Gets or sets the AverageE2ELatency property for the metrics entity, indicating the average end-to-end latency of successful requests.</span></span>
            </summary>
        <value><span data-ttu-id="fb194-126">メトリックのエンティティの成功した要求の平均のエンド ツー エンドの待機時間を表す double 値。</span><span class="sxs-lookup"><span data-stu-id="fb194-126">A double containing the average end-to-end latency of successful requests for the metrics entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AverageServerLatency">
      <MemberSignature Language="C#" Value="public double AverageServerLatency { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 AverageServerLatency" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.AverageServerLatency" />
      <MemberSignature Language="VB.NET" Value="Public Property AverageServerLatency As Double" />
      <MemberSignature Language="F#" Value="member this.AverageServerLatency : double with get, set" Usage="Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.AverageServerLatency" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb194-127">取得またはメトリック エンティティは、サービスが成功した要求を処理するための平均待機時間を示す AverageServerLatency プロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="fb194-127">Gets or sets the AverageServerLatency property for the metrics entity, indicating the average latency for the service to process a successful request.</span></span>
            </summary>
        <value><span data-ttu-id="fb194-128">サービス メトリックのエンティティの成功した要求を処理するための平均待機時間を表す double 値。</span><span class="sxs-lookup"><span data-stu-id="fb194-128">A double containing the average latency for the service to process a successful request for the metrics entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientOtherError">
      <MemberSignature Language="C#" Value="public long ClientOtherError { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ClientOtherError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.ClientOtherError" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientOtherError As Long" />
      <MemberSignature Language="F#" Value="member this.ClientOtherError : int64 with get, set" Usage="Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.ClientOtherError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb194-129">取得または、ClientOtherError が返された認証済みの要求の数を示すメトリック エンティティの ClientOtherError プロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="fb194-129">Gets or sets the ClientOtherError property for the metrics entity, indicating the number of authenticated requests that returned a ClientOtherError.</span></span>
            </summary>
        <value><span data-ttu-id="fb194-130">メトリックのエンティティの ClientOtherError が返された認証済みの要求の数を表す long 値です。</span><span class="sxs-lookup"><span data-stu-id="fb194-130">A long containing the number of authenticated requests that returned a ClientOtherError for the metrics entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientTimeoutError">
      <MemberSignature Language="C#" Value="public long ClientTimeoutError { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ClientTimeoutError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.ClientTimeoutError" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientTimeoutError As Long" />
      <MemberSignature Language="F#" Value="member this.ClientTimeoutError : int64 with get, set" Usage="Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.ClientTimeoutError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb194-131">取得または、ClientTimeoutError が返された認証済みの要求の数を示すメトリック エンティティは、ClientTimeoutError プロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="fb194-131">Gets or sets the ClientTimeoutError property for the metrics entity, indicating the number of authenticated requests that returned a ClientTimeoutError.</span></span>
            </summary>
        <value><span data-ttu-id="fb194-132">メトリックのエンティティの ClientTimeoutError が返された認証済みの要求の数を表す long 値です。</span><span class="sxs-lookup"><span data-stu-id="fb194-132">A long containing the number of authenticated requests that returned a ClientTimeoutError for the metrics entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkError">
      <MemberSignature Language="C#" Value="public long NetworkError { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 NetworkError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.NetworkError" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkError As Long" />
      <MemberSignature Language="F#" Value="member this.NetworkError : int64 with get, set" Usage="Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.NetworkError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb194-133">取得または、NetworkError が返された認証済みの要求の数を示すメトリック エンティティの NetworkError プロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="fb194-133">Gets or sets the NetworkError property for the metrics entity, indicating the number of authenticated requests that returned a NetworkError.</span></span>
            </summary>
        <value><span data-ttu-id="fb194-134">メトリックのエンティティの NetworkError が返された認証済みの要求の数を表す long 値です。</span><span class="sxs-lookup"><span data-stu-id="fb194-134">A long containing the number of authenticated requests that returned a NetworkError for the metrics entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PercentAuthorizationError">
      <MemberSignature Language="C#" Value="public double PercentAuthorizationError { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 PercentAuthorizationError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.PercentAuthorizationError" />
      <MemberSignature Language="VB.NET" Value="Public Property PercentAuthorizationError As Double" />
      <MemberSignature Language="F#" Value="member this.PercentAuthorizationError : double with get, set" Usage="Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.PercentAuthorizationError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb194-135">取得または authorizationerror によって失敗した要求の割合を示すメトリック エンティティの PercentAuthorizationError プロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="fb194-135">Gets or sets the PercentAuthorizationError property for the metrics entity, indicating the percentage of requests that failed with an AuthorizationError.</span></span>
            </summary>
        <value><span data-ttu-id="fb194-136">メトリックのエンティティの authorizationerror によって失敗した要求の割合を表す double 値。</span><span class="sxs-lookup"><span data-stu-id="fb194-136">A double containing the percentage of requests that failed with an AuthorizationError for the metrics entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PercentClientOtherError">
      <MemberSignature Language="C#" Value="public double PercentClientOtherError { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 PercentClientOtherError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.PercentClientOtherError" />
      <MemberSignature Language="VB.NET" Value="Public Property PercentClientOtherError As Double" />
      <MemberSignature Language="F#" Value="member this.PercentClientOtherError : double with get, set" Usage="Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.PercentClientOtherError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb194-137">取得または clientothererror によって失敗した要求の割合を示すメトリック エンティティの PercentClientOtherError プロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="fb194-137">Gets or sets the PercentClientOtherError property for the metrics entity, indicating the percentage of requests that failed with a ClientOtherError.</span></span>
            </summary>
        <value><span data-ttu-id="fb194-138">メトリックのエンティティの clientothererror によって失敗した要求の割合を表す double 値。</span><span class="sxs-lookup"><span data-stu-id="fb194-138">A double containing the percentage of requests that failed with a ClientOtherError for the metrics entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PercentNetworkError">
      <MemberSignature Language="C#" Value="public double PercentNetworkError { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 PercentNetworkError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.PercentNetworkError" />
      <MemberSignature Language="VB.NET" Value="Public Property PercentNetworkError As Double" />
      <MemberSignature Language="F#" Value="member this.PercentNetworkError : double with get, set" Usage="Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.PercentNetworkError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb194-139">取得または networkerror によって失敗した要求の割合を示すメトリック エンティティの PercentNetworkError プロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="fb194-139">Gets or sets the PercentNetworkError property for the metrics entity, indicating the percentage of requests that failed with a NetworkError.</span></span>
            </summary>
        <value><span data-ttu-id="fb194-140">メトリックのエンティティの networkerror によって失敗した要求の割合を表す double 値。</span><span class="sxs-lookup"><span data-stu-id="fb194-140">A double containing the percentage of requests that failed with a NetworkError for the metrics entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PercentServerOtherError">
      <MemberSignature Language="C#" Value="public double PercentServerOtherError { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 PercentServerOtherError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.PercentServerOtherError" />
      <MemberSignature Language="VB.NET" Value="Public Property PercentServerOtherError As Double" />
      <MemberSignature Language="F#" Value="member this.PercentServerOtherError : double with get, set" Usage="Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.PercentServerOtherError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb194-141">取得または serverothererror によって失敗した要求の割合を示すメトリック エンティティの PercentServerOtherError プロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="fb194-141">Gets or sets the PercentServerOtherError property for the metrics entity, indicating the percentage of requests that failed with a ServerOtherError.</span></span>
            </summary>
        <value><span data-ttu-id="fb194-142">メトリックのエンティティの serverothererror によって失敗した要求の割合を表す double 値。</span><span class="sxs-lookup"><span data-stu-id="fb194-142">A double containing the percentage of requests that failed with a ServerOtherError for the metrics entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PercentSuccess">
      <MemberSignature Language="C#" Value="public double PercentSuccess { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 PercentSuccess" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.PercentSuccess" />
      <MemberSignature Language="VB.NET" Value="Public Property PercentSuccess As Double" />
      <MemberSignature Language="F#" Value="member this.PercentSuccess : double with get, set" Usage="Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.PercentSuccess" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb194-143">取得または成功した要求の割合を示すメトリック エンティティの PercentSuccess プロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="fb194-143">Gets or sets the PercentSuccess property for the metrics entity, indicating the percentage of successful requests.</span></span>
            </summary>
        <value><span data-ttu-id="fb194-144">メトリックのエンティティの成功した要求の割合を表す double 値。</span><span class="sxs-lookup"><span data-stu-id="fb194-144">A double containing the percentage of successful requests for the metrics entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PercentThrottlingError">
      <MemberSignature Language="C#" Value="public double PercentThrottlingError { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 PercentThrottlingError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.PercentThrottlingError" />
      <MemberSignature Language="VB.NET" Value="Public Property PercentThrottlingError As Double" />
      <MemberSignature Language="F#" Value="member this.PercentThrottlingError : double with get, set" Usage="Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.PercentThrottlingError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb194-145">取得または調整エラーによって失敗した要求の割合を示すメトリック エンティティの PercentThrottlingError プロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="fb194-145">Gets or sets the PercentThrottlingError property for the metrics entity, indicating the percentage of requests that failed with a throttling error.</span></span>
            </summary>
        <value><span data-ttu-id="fb194-146">メトリックのエンティティの調整エラーによって失敗した要求の割合を表す double 値。</span><span class="sxs-lookup"><span data-stu-id="fb194-146">A double containing the percentage of requests that failed with a throttling error for the metrics entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PercentTimeoutError">
      <MemberSignature Language="C#" Value="public double PercentTimeoutError { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 PercentTimeoutError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.PercentTimeoutError" />
      <MemberSignature Language="VB.NET" Value="Public Property PercentTimeoutError As Double" />
      <MemberSignature Language="F#" Value="member this.PercentTimeoutError : double with get, set" Usage="Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.PercentTimeoutError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb194-147">取得またはタイムアウト エラーで失敗した要求の割合を示すメトリック エンティティの PercentTimeoutError プロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="fb194-147">Gets or sets the PercentTimeoutError property for the metrics entity, indicating the percentage of requests that failed with a timeout error.</span></span>
            </summary>
        <value><span data-ttu-id="fb194-148">メトリックのエンティティのタイムアウト エラーで失敗した要求の割合を表す double 値。</span><span class="sxs-lookup"><span data-stu-id="fb194-148">A double containing the percentage of requests that failed with a timeout error for the metrics entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SASAuthorizationError">
      <MemberSignature Language="C#" Value="public long SASAuthorizationError { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SASAuthorizationError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.SASAuthorizationError" />
      <MemberSignature Language="VB.NET" Value="Public Property SASAuthorizationError As Long" />
      <MemberSignature Language="F#" Value="member this.SASAuthorizationError : int64 with get, set" Usage="Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.SASAuthorizationError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb194-149">取得または、AuthorizationError が返された SAS 要求の数を示すメトリック エンティティは、SASAuthorizationError プロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="fb194-149">Gets or sets the SASAuthorizationError property for the metrics entity, indicating the number of SAS requests that returned an AuthorizationError.</span></span>
            </summary>
        <value><span data-ttu-id="fb194-150">メトリックのエンティティに対して、AuthorizationError が返された SAS 要求の数を表す long 値です。</span><span class="sxs-lookup"><span data-stu-id="fb194-150">A long containing the number of SAS requests that returned an AuthorizationError for the metrics entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SASClientOtherError">
      <MemberSignature Language="C#" Value="public long SASClientOtherError { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SASClientOtherError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.SASClientOtherError" />
      <MemberSignature Language="VB.NET" Value="Public Property SASClientOtherError As Long" />
      <MemberSignature Language="F#" Value="member this.SASClientOtherError : int64 with get, set" Usage="Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.SASClientOtherError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb194-151">取得または、ClientOtherError が返された SAS 要求の数を示すメトリック エンティティは、SASClientOtherError プロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="fb194-151">Gets or sets the SASClientOtherError property for the metrics entity, indicating the number of SAS requests that returned a ClientOtherError.</span></span>
            </summary>
        <value><span data-ttu-id="fb194-152">メトリックのエンティティの ClientOtherError が返された SAS 要求の数を表す long 値です。</span><span class="sxs-lookup"><span data-stu-id="fb194-152">A long containing the number of SAS requests that returned a ClientOtherError for the metrics entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SASClientTimeoutError">
      <MemberSignature Language="C#" Value="public long SASClientTimeoutError { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SASClientTimeoutError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.SASClientTimeoutError" />
      <MemberSignature Language="VB.NET" Value="Public Property SASClientTimeoutError As Long" />
      <MemberSignature Language="F#" Value="member this.SASClientTimeoutError : int64 with get, set" Usage="Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.SASClientTimeoutError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb194-153">取得または、ClientTimeoutError が返された SAS 要求の数を示すメトリック エンティティは、SASClientTimeoutError プロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="fb194-153">Gets or sets the SASClientTimeoutError property for the metrics entity, indicating the number of SAS requests that returned a ClientTimeoutError.</span></span>
            </summary>
        <value><span data-ttu-id="fb194-154">メトリックのエンティティの ClientTimeoutError が返された SAS 要求の数を表す long 値です。</span><span class="sxs-lookup"><span data-stu-id="fb194-154">A long containing the number of SAS requests that returned a ClientTimeoutError for the metrics entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SASNetworkError">
      <MemberSignature Language="C#" Value="public long SASNetworkError { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SASNetworkError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.SASNetworkError" />
      <MemberSignature Language="VB.NET" Value="Public Property SASNetworkError As Long" />
      <MemberSignature Language="F#" Value="member this.SASNetworkError : int64 with get, set" Usage="Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.SASNetworkError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb194-155">取得または、NetworkError が返された SAS 要求の数を示すメトリック エンティティは、SASNetworkError プロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="fb194-155">Gets or sets the SASNetworkError property for the metrics entity, indicating the number of SAS requests that returned a NetworkError.</span></span>
            </summary>
        <value><span data-ttu-id="fb194-156">メトリックのエンティティの NetworkError が返された SAS 要求の数を表す long 値です。</span><span class="sxs-lookup"><span data-stu-id="fb194-156">A long containing the number of SAS requests that returned a NetworkError for the metrics entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SASServerOtherError">
      <MemberSignature Language="C#" Value="public long SASServerOtherError { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SASServerOtherError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.SASServerOtherError" />
      <MemberSignature Language="VB.NET" Value="Public Property SASServerOtherError As Long" />
      <MemberSignature Language="F#" Value="member this.SASServerOtherError : int64 with get, set" Usage="Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.SASServerOtherError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb194-157">取得または、ServerOtherError が返された SAS 要求の数を示すメトリック エンティティは、SASServerOtherError プロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="fb194-157">Gets or sets the SASServerOtherError property for the metrics entity, indicating the number of SAS requests that returned a ServerOtherError.</span></span>
            </summary>
        <value><span data-ttu-id="fb194-158">メトリックのエンティティの ServerOtherError が返された SAS 要求の数を表す long 値です。</span><span class="sxs-lookup"><span data-stu-id="fb194-158">A long containing the number of SAS requests that returned a ServerOtherError for the metrics entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SASServerTimeoutError">
      <MemberSignature Language="C#" Value="public long SASServerTimeoutError { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SASServerTimeoutError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.SASServerTimeoutError" />
      <MemberSignature Language="VB.NET" Value="Public Property SASServerTimeoutError As Long" />
      <MemberSignature Language="F#" Value="member this.SASServerTimeoutError : int64 with get, set" Usage="Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.SASServerTimeoutError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb194-159">取得または、ServerTimeoutError が返された SAS 要求の数を示すメトリック エンティティは、SASServerTimeoutError プロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="fb194-159">Gets or sets the SASServerTimeoutError property for the metrics entity, indicating the number of SAS requests that returned a ServerTimeoutError.</span></span>
            </summary>
        <value><span data-ttu-id="fb194-160">メトリックのエンティティの ServerTimeoutError が返された SAS 要求の数を表す long 値です。</span><span class="sxs-lookup"><span data-stu-id="fb194-160">A long containing the number of SAS requests that returned a ServerTimeoutError for the metrics entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SASSuccess">
      <MemberSignature Language="C#" Value="public long SASSuccess { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SASSuccess" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.SASSuccess" />
      <MemberSignature Language="VB.NET" Value="Public Property SASSuccess As Long" />
      <MemberSignature Language="F#" Value="member this.SASSuccess : int64 with get, set" Usage="Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.SASSuccess" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb194-161">取得または成功した SAS 要求の数を示すメトリック エンティティの SASSuccess プロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="fb194-161">Gets or sets the SASSuccess property for the metrics entity, indicating the number of successful SAS requests.</span></span>
            </summary>
        <value><span data-ttu-id="fb194-162">メトリックのエンティティの成功した SAS 要求の数を表す long 値です。</span><span class="sxs-lookup"><span data-stu-id="fb194-162">A long containing the number of successful SAS requests for the metrics entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SASThrottlingError">
      <MemberSignature Language="C#" Value="public long SASThrottlingError { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SASThrottlingError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.SASThrottlingError" />
      <MemberSignature Language="VB.NET" Value="Public Property SASThrottlingError As Long" />
      <MemberSignature Language="F#" Value="member this.SASThrottlingError : int64 with get, set" Usage="Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.SASThrottlingError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb194-163">取得または、ThrottlingError が返された SAS 要求の数を示すメトリック エンティティは、SASThrottlingError プロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="fb194-163">Gets or sets the SASThrottlingError property for the metrics entity, indicating the number of SAS requests that returned a ThrottlingError.</span></span>
            </summary>
        <value><span data-ttu-id="fb194-164">メトリックのエンティティの ThrottlingError が返された SAS 要求の数を表す long 値です。</span><span class="sxs-lookup"><span data-stu-id="fb194-164">A long containing the number of SAS requests that returned a ThrottlingError for the metrics entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerOtherError">
      <MemberSignature Language="C#" Value="public long ServerOtherError { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ServerOtherError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.ServerOtherError" />
      <MemberSignature Language="VB.NET" Value="Public Property ServerOtherError As Long" />
      <MemberSignature Language="F#" Value="member this.ServerOtherError : int64 with get, set" Usage="Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.ServerOtherError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb194-165">取得または、ServerOtherError が返された認証済みの要求の数を示すメトリック エンティティの ServerOtherError プロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="fb194-165">Gets or sets the ServerOtherError property for the metrics entity, indicating the number of authenticated requests that returned a ServerOtherError.</span></span>
            </summary>
        <value><span data-ttu-id="fb194-166">メトリックのエンティティの ServerOtherError が返された認証済みの要求の数を表す long 値です。</span><span class="sxs-lookup"><span data-stu-id="fb194-166">A long containing the number of authenticated requests that returned a ServerOtherError for the metrics entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerTimeoutError">
      <MemberSignature Language="C#" Value="public long ServerTimeoutError { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ServerTimeoutError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.ServerTimeoutError" />
      <MemberSignature Language="VB.NET" Value="Public Property ServerTimeoutError As Long" />
      <MemberSignature Language="F#" Value="member this.ServerTimeoutError : int64 with get, set" Usage="Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.ServerTimeoutError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb194-167">取得または、ServerTimeoutError が返された認証済みの要求の数を示すメトリック エンティティは、ServerTimeoutError プロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="fb194-167">Gets or sets the ServerTimeoutError property for the metrics entity, indicating the number of authenticated requests that returned a ServerTimeoutError.</span></span>
            </summary>
        <value><span data-ttu-id="fb194-168">メトリックのエンティティの ServerTimeoutError が返された認証済みの要求の数を表す long 値です。</span><span class="sxs-lookup"><span data-stu-id="fb194-168">A long containing the number of authenticated requests that returned a ServerTimeoutError for the metrics entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Success">
      <MemberSignature Language="C#" Value="public long Success { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Success" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.Success" />
      <MemberSignature Language="VB.NET" Value="Public Property Success As Long" />
      <MemberSignature Language="F#" Value="member this.Success : int64 with get, set" Usage="Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.Success" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb194-169">取得または成功した要求の数を示すメトリック エンティティは、成功プロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="fb194-169">Gets or sets the Success property for the metrics entity, indicating the number of successful requests.</span></span>
            </summary>
        <value><span data-ttu-id="fb194-170">メトリックのエンティティの成功した要求の数を表す long 値です。</span><span class="sxs-lookup"><span data-stu-id="fb194-170">A long containing the number of successful requests for the metrics entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ThrottlingError">
      <MemberSignature Language="C#" Value="public long ThrottlingError { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ThrottlingError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.ThrottlingError" />
      <MemberSignature Language="VB.NET" Value="Public Property ThrottlingError As Long" />
      <MemberSignature Language="F#" Value="member this.ThrottlingError : int64 with get, set" Usage="Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.ThrottlingError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb194-171">取得または、ThrottlingError が返された認証済みの要求の数を示すメトリック エンティティは、ThrottlingError プロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="fb194-171">Gets or sets the ThrottlingError property for the metrics entity, indicating the number of authenticated requests that returned a ThrottlingError.</span></span>
            </summary>
        <value><span data-ttu-id="fb194-172">メトリックのエンティティの ThrottlingError が返された認証済みの要求の数を表す long 値です。</span><span class="sxs-lookup"><span data-stu-id="fb194-172">A long containing the number of authenticated requests that returned a ThrottlingError for the metrics entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Time">
      <MemberSignature Language="C#" Value="public DateTimeOffset Time { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTimeOffset Time" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.Time" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Time As DateTimeOffset" />
      <MemberSignature Language="F#" Value="member this.Time : DateTimeOffset" Usage="Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.Time" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTimeOffset</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb194-173">(Utc)、そのログ エントリの開始時刻を表すメトリック エンティティのタイムスタンプを取得します。</span><span class="sxs-lookup"><span data-stu-id="fb194-173">Gets the metrics entity's timestamp in UTC, representing the start time for that log entry.</span></span>
            </summary>
        <value><span data-ttu-id="fb194-174">UTC のタイムスタンプを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="fb194-174">A string containing the timestamp in UTC.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalBillableRequests">
      <MemberSignature Language="C#" Value="public long TotalBillableRequests { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TotalBillableRequests" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.TotalBillableRequests" />
      <MemberSignature Language="VB.NET" Value="Public Property TotalBillableRequests As Long" />
      <MemberSignature Language="F#" Value="member this.TotalBillableRequests : int64 with get, set" Usage="Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.TotalBillableRequests" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb194-175">取得またはメトリック エンティティは、課金対象の要求の合計数を示す TotalBillableRequests プロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="fb194-175">Gets or sets the TotalBillableRequests property for the metrics entity, indicating the total number of billable requests.</span></span>
            </summary>
        <value><span data-ttu-id="fb194-176">メトリックのエンティティの課金対象の要求の合計数を表す long 値です。</span><span class="sxs-lookup"><span data-stu-id="fb194-176">A long containing the total number of billable requests for the metrics entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalEgress">
      <MemberSignature Language="C#" Value="public long TotalEgress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TotalEgress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.TotalEgress" />
      <MemberSignature Language="VB.NET" Value="Public Property TotalEgress As Long" />
      <MemberSignature Language="F#" Value="member this.TotalEgress : int64 with get, set" Usage="Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.TotalEgress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb194-177">取得またはメトリック エンティティは、(バイト単位)、egress データの量を示す TotalEgress プロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="fb194-177">Gets or sets the TotalEgress property for the metrics entity, indicating the quantity of egress data, in bytes.</span></span>
            </summary>
        <value><span data-ttu-id="fb194-178">(バイト単位) メトリックのエンティティの egress データの量を表す long 値です。</span><span class="sxs-lookup"><span data-stu-id="fb194-178">A long containing the quantity of egress data, in bytes, for the metrics entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalIngress">
      <MemberSignature Language="C#" Value="public long TotalIngress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TotalIngress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.TotalIngress" />
      <MemberSignature Language="VB.NET" Value="Public Property TotalIngress As Long" />
      <MemberSignature Language="F#" Value="member this.TotalIngress : int64 with get, set" Usage="Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.TotalIngress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb194-179">取得またはメトリック エンティティは、(バイト単位) の受信データの量を示す TotalIngress プロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="fb194-179">Gets or sets the TotalIngress property for the metrics entity, indicating the quantity of ingress data, in bytes.</span></span>
            </summary>
        <value><span data-ttu-id="fb194-180">メトリックのエンティティのバイト単位での受信データの量を表す long 値です。</span><span class="sxs-lookup"><span data-stu-id="fb194-180">A long containing the quantity of ingress data, in bytes, for the metrics entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalRequests">
      <MemberSignature Language="C#" Value="public long TotalRequests { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TotalRequests" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.TotalRequests" />
      <MemberSignature Language="VB.NET" Value="Public Property TotalRequests As Long" />
      <MemberSignature Language="F#" Value="member this.TotalRequests : int64 with get, set" Usage="Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.TotalRequests" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb194-181">取得または要求の合計数を示すメトリック エンティティの TotalRequests プロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="fb194-181">Gets or sets the TotalRequests property for the metrics entity, indicating the total number of requests.</span></span>
            </summary>
        <value><span data-ttu-id="fb194-182">メトリックのエンティティの要求の合計数を表す long 値です。</span><span class="sxs-lookup"><span data-stu-id="fb194-182">A long containing the number of total requests for the metrics entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransactionType">
      <MemberSignature Language="C#" Value="public string TransactionType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TransactionType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.TransactionType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TransactionType As String" />
      <MemberSignature Language="F#" Value="member this.TransactionType : string" Usage="Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity.TransactionType" />
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
            <span data-ttu-id="fb194-183">トランザクション ログに記録の種類を示す、メトリックのエンティティの TransactionType プロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="fb194-183">Gets the TransactionType property for the metrics entity, indicating the type of transaction logged.</span></span>
            </summary>
        <value><span data-ttu-id="fb194-184">メトリックのエンティティのトランザクションの種類を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="fb194-184">A string containing the transaction type for the metrics entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>