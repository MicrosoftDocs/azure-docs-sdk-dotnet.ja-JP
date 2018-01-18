<Type Name="ActivityWindow" FullName="Microsoft.Azure.Management.DataFactories.Models.ActivityWindow">
  <TypeSignature Language="C#" Value="public class ActivityWindow" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ActivityWindow extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.ActivityWindow" />
  <TypeSignature Language="VB.NET" Value="Public Class ActivityWindow" />
  <TypeSignature Language="F#" Value="type ActivityWindow = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d80ea-101">アクティビティのスケジュールを指定する、一連のタンブリング ウィンドウを作成します。</span><span class="sxs-lookup"><span data-stu-id="d80ea-101">Specifying a schedule for the activity creates a series of tumbling windows.</span></span> <span data-ttu-id="d80ea-102">タンブリング ウィンドウは、一連の固定サイズ、重複しない連続した時間間隔です。</span><span class="sxs-lookup"><span data-stu-id="d80ea-102">Tumbling windows are series of fixed-sized, non-overlapping and contiguous time intervals.</span></span> <span data-ttu-id="d80ea-103">アクティビティ ウィンドウは、これらの論理タンブリング ウィンドウ、アクティビティのインスタンスです。</span><span class="sxs-lookup"><span data-stu-id="d80ea-103">Activity window is an instance of these logical tumbling windows for the activity.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActivityWindow ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.ActivityWindow.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d80ea-104">ActivityWindow クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d80ea-104">Initializes a new instance of the ActivityWindow class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActivityName">
      <MemberSignature Language="C#" Value="public string ActivityName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ActivityName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.ActivityWindow.ActivityName" />
      <MemberSignature Language="VB.NET" Value="Public Property ActivityName As String" />
      <MemberSignature Language="F#" Value="member this.ActivityName : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.ActivityWindow.ActivityName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d80ea-105">必須。</span><span class="sxs-lookup"><span data-stu-id="d80ea-105">Required.</span></span> <span data-ttu-id="d80ea-106">パイプラインのアクティビティ名。</span><span class="sxs-lookup"><span data-stu-id="d80ea-106">Pipeline activity name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActivityType">
      <MemberSignature Language="C#" Value="public string ActivityType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ActivityType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.ActivityWindow.ActivityType" />
      <MemberSignature Language="VB.NET" Value="Public Property ActivityType As String" />
      <MemberSignature Language="F#" Value="member this.ActivityType : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.ActivityWindow.ActivityType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d80ea-107">必須。</span><span class="sxs-lookup"><span data-stu-id="d80ea-107">Required.</span></span> <span data-ttu-id="d80ea-108">どちらのユーザーが定義されているか、登録されている可能性があるアクティビティの型。</span><span class="sxs-lookup"><span data-stu-id="d80ea-108">The activity type which can be either user defined or registered.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataFactoryName">
      <MemberSignature Language="C#" Value="public string DataFactoryName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DataFactoryName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.ActivityWindow.DataFactoryName" />
      <MemberSignature Language="VB.NET" Value="Public Property DataFactoryName As String" />
      <MemberSignature Language="F#" Value="member this.DataFactoryName : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.ActivityWindow.DataFactoryName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d80ea-109">必須。</span><span class="sxs-lookup"><span data-stu-id="d80ea-109">Required.</span></span> <span data-ttu-id="d80ea-110">データ ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="d80ea-110">Data factory name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Duration">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; Duration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; Duration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.ActivityWindow.Duration" />
      <MemberSignature Language="VB.NET" Value="Public Property Duration As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.Duration : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.ActivityWindow.Duration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d80ea-111">省略可能。</span><span class="sxs-lookup"><span data-stu-id="d80ea-111">Optional.</span></span> <span data-ttu-id="d80ea-112">実行の継続時間。</span><span class="sxs-lookup"><span data-stu-id="d80ea-112">Duration of run.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InputDatasets">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; InputDatasets { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; InputDatasets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.ActivityWindow.InputDatasets" />
      <MemberSignature Language="VB.NET" Value="Public Property InputDatasets As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.InputDatasets : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.ActivityWindow.InputDatasets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d80ea-113">必須。</span><span class="sxs-lookup"><span data-stu-id="d80ea-113">Required.</span></span> <span data-ttu-id="d80ea-114">アクティビティ ウィンドウに対応する入力データセット。</span><span class="sxs-lookup"><span data-stu-id="d80ea-114">The input datasets corresponding to the activity window.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LinkedServiceName">
      <MemberSignature Language="C#" Value="public string LinkedServiceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LinkedServiceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.ActivityWindow.LinkedServiceName" />
      <MemberSignature Language="VB.NET" Value="Public Property LinkedServiceName As String" />
      <MemberSignature Language="F#" Value="member this.LinkedServiceName : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.ActivityWindow.LinkedServiceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d80ea-115">必須。</span><span class="sxs-lookup"><span data-stu-id="d80ea-115">Required.</span></span> <span data-ttu-id="d80ea-116">リンクされたサービスのアクティビティ ウィンドウを実行します。</span><span class="sxs-lookup"><span data-stu-id="d80ea-116">The linked service the activity window is run on.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutputDatasets">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; OutputDatasets { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; OutputDatasets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.ActivityWindow.OutputDatasets" />
      <MemberSignature Language="VB.NET" Value="Public Property OutputDatasets As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.OutputDatasets : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.ActivityWindow.OutputDatasets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d80ea-117">必須。</span><span class="sxs-lookup"><span data-stu-id="d80ea-117">Required.</span></span> <span data-ttu-id="d80ea-118">アクティビティ ウィンドウに対応する出力データセット。</span><span class="sxs-lookup"><span data-stu-id="d80ea-118">The output datasets corresponding to the activity window.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PercentComplete">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; PercentComplete { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; PercentComplete" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.ActivityWindow.PercentComplete" />
      <MemberSignature Language="VB.NET" Value="Public Property PercentComplete As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.PercentComplete : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.ActivityWindow.PercentComplete" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d80ea-119">省略可能。</span><span class="sxs-lookup"><span data-stu-id="d80ea-119">Optional.</span></span> <span data-ttu-id="d80ea-120">アクティビティ ウィンドウの実行の Pecent 完了します。</span><span class="sxs-lookup"><span data-stu-id="d80ea-120">Pecent completion of activity window execution.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PipelineName">
      <MemberSignature Language="C#" Value="public string PipelineName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PipelineName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.ActivityWindow.PipelineName" />
      <MemberSignature Language="VB.NET" Value="Public Property PipelineName As String" />
      <MemberSignature Language="F#" Value="member this.PipelineName : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.ActivityWindow.PipelineName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d80ea-121">必須。</span><span class="sxs-lookup"><span data-stu-id="d80ea-121">Required.</span></span> <span data-ttu-id="d80ea-122">パイプラインの名前です。</span><span class="sxs-lookup"><span data-stu-id="d80ea-122">Pipeline name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceGroupName">
      <MemberSignature Language="C#" Value="public string ResourceGroupName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceGroupName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.ActivityWindow.ResourceGroupName" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceGroupName As String" />
      <MemberSignature Language="F#" Value="member this.ResourceGroupName : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.ActivityWindow.ResourceGroupName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d80ea-123">必須。</span><span class="sxs-lookup"><span data-stu-id="d80ea-123">Required.</span></span> <span data-ttu-id="d80ea-124">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="d80ea-124">Resource group name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RunAttempts">
      <MemberSignature Language="C#" Value="public int RunAttempts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 RunAttempts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.ActivityWindow.RunAttempts" />
      <MemberSignature Language="VB.NET" Value="Public Property RunAttempts As Integer" />
      <MemberSignature Language="F#" Value="member this.RunAttempts : int with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.ActivityWindow.RunAttempts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d80ea-125">必須。</span><span class="sxs-lookup"><span data-stu-id="d80ea-125">Required.</span></span> <span data-ttu-id="d80ea-126">アクティビティの実行の試行回数です。</span><span class="sxs-lookup"><span data-stu-id="d80ea-126">Number of activity run attempts.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RunEnd">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; RunEnd { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; RunEnd" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.ActivityWindow.RunEnd" />
      <MemberSignature Language="VB.NET" Value="Public Property RunEnd As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.RunEnd : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.ActivityWindow.RunEnd" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d80ea-127">省略可能。</span><span class="sxs-lookup"><span data-stu-id="d80ea-127">Optional.</span></span> <span data-ttu-id="d80ea-128">前回の実行の終了時刻。</span><span class="sxs-lookup"><span data-stu-id="d80ea-128">End time of the last run.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RunStart">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; RunStart { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; RunStart" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.ActivityWindow.RunStart" />
      <MemberSignature Language="VB.NET" Value="Public Property RunStart As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.RunStart : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.ActivityWindow.RunStart" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d80ea-129">省略可能。</span><span class="sxs-lookup"><span data-stu-id="d80ea-129">Optional.</span></span> <span data-ttu-id="d80ea-130">前回の実行の開始時刻。</span><span class="sxs-lookup"><span data-stu-id="d80ea-130">Start time of the last run.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WindowEnd">
      <MemberSignature Language="C#" Value="public DateTime WindowEnd { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime WindowEnd" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.ActivityWindow.WindowEnd" />
      <MemberSignature Language="VB.NET" Value="Public Property WindowEnd As DateTime" />
      <MemberSignature Language="F#" Value="member this.WindowEnd : DateTime with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.ActivityWindow.WindowEnd" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d80ea-131">必須。</span><span class="sxs-lookup"><span data-stu-id="d80ea-131">Required.</span></span> <span data-ttu-id="d80ea-132">アクティビティ時間帯の時刻を開始します。</span><span class="sxs-lookup"><span data-stu-id="d80ea-132">Start time of the activity window.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WindowStart">
      <MemberSignature Language="C#" Value="public DateTime WindowStart { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime WindowStart" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.ActivityWindow.WindowStart" />
      <MemberSignature Language="VB.NET" Value="Public Property WindowStart As DateTime" />
      <MemberSignature Language="F#" Value="member this.WindowStart : DateTime with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.ActivityWindow.WindowStart" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d80ea-133">必須。</span><span class="sxs-lookup"><span data-stu-id="d80ea-133">Required.</span></span> <span data-ttu-id="d80ea-134">アクティビティ時間帯の時刻を開始します。</span><span class="sxs-lookup"><span data-stu-id="d80ea-134">Start time of the activity window.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WindowState">
      <MemberSignature Language="C#" Value="public string WindowState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WindowState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.ActivityWindow.WindowState" />
      <MemberSignature Language="VB.NET" Value="Public Property WindowState As String" />
      <MemberSignature Language="F#" Value="member this.WindowState : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.ActivityWindow.WindowState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d80ea-135">必須。</span><span class="sxs-lookup"><span data-stu-id="d80ea-135">Required.</span></span> <span data-ttu-id="d80ea-136">ウィンドウの状態。</span><span class="sxs-lookup"><span data-stu-id="d80ea-136">Window state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WindowSubstate">
      <MemberSignature Language="C#" Value="public string WindowSubstate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WindowSubstate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.ActivityWindow.WindowSubstate" />
      <MemberSignature Language="VB.NET" Value="Public Property WindowSubstate As String" />
      <MemberSignature Language="F#" Value="member this.WindowSubstate : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.ActivityWindow.WindowSubstate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d80ea-137">必須。</span><span class="sxs-lookup"><span data-stu-id="d80ea-137">Required.</span></span> <span data-ttu-id="d80ea-138">ウィンドウの下位状態です。</span><span class="sxs-lookup"><span data-stu-id="d80ea-138">Window substate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>