<Type Name="Status" FullName="Microsoft.Azure.Management.HDInsight.Job.Models.Status">
  <TypeSignature Language="C#" Value="public class Status" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Status extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.HDInsight.Job.Models.Status" />
  <TypeSignature Language="VB.NET" Value="Public Class Status" />
  <TypeSignature Language="F#" Value="type Status = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0176c-101">取得またはジョブの状態情報を格納するオブジェクトを設定します。</span><span class="sxs-lookup"><span data-stu-id="0176c-101">Gets or sets the object containing the job status information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Status ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.Models.Status.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0176c-102">ステータス クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0176c-102">Initializes a new instance of the Status class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CleanupProgress">
      <MemberSignature Language="C#" Value="public double CleanupProgress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 CleanupProgress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Job.Models.Status.CleanupProgress" />
      <MemberSignature Language="VB.NET" Value="Public Property CleanupProgress As Double" />
      <MemberSignature Language="F#" Value="member this.CleanupProgress : double with get, set" Usage="Microsoft.Azure.Management.HDInsight.Job.Models.Status.CleanupProgress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0176c-103">省略可能。</span><span class="sxs-lookup"><span data-stu-id="0176c-103">Optional.</span></span> <span data-ttu-id="0176c-104">取得またはクリーンアップの進行状況を設定します。</span><span class="sxs-lookup"><span data-stu-id="0176c-104">Gets or sets the progress made on the cleanup.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailureInfo">
      <MemberSignature Language="C#" Value="public string FailureInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FailureInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Job.Models.Status.FailureInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property FailureInfo As String" />
      <MemberSignature Language="F#" Value="member this.FailureInfo : string with get, set" Usage="Microsoft.Azure.Management.HDInsight.Job.Models.Status.FailureInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0176c-105">省略可能。</span><span class="sxs-lookup"><span data-stu-id="0176c-105">Optional.</span></span> <span data-ttu-id="0176c-106">取得または発生したすべての障害に関する情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="0176c-106">Gets or sets the information about any failures that have occurred.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FinishTime">
      <MemberSignature Language="C#" Value="public string FinishTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FinishTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Job.Models.Status.FinishTime" />
      <MemberSignature Language="VB.NET" Value="Public Property FinishTime As String" />
      <MemberSignature Language="F#" Value="member this.FinishTime : string with get, set" Usage="Microsoft.Azure.Management.HDInsight.Job.Models.Status.FinishTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0176c-107">省略可能。</span><span class="sxs-lookup"><span data-stu-id="0176c-107">Optional.</span></span> <span data-ttu-id="0176c-108">取得またはジョブが完了した時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="0176c-108">Gets or sets the time at which the job completed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HistoryFile">
      <MemberSignature Language="C#" Value="public string HistoryFile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HistoryFile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Job.Models.Status.HistoryFile" />
      <MemberSignature Language="VB.NET" Value="Public Property HistoryFile As String" />
      <MemberSignature Language="F#" Value="member this.HistoryFile : string with get, set" Usage="Microsoft.Azure.Management.HDInsight.Job.Models.Status.HistoryFile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0176c-109">省略可能。</span><span class="sxs-lookup"><span data-stu-id="0176c-109">Optional.</span></span> <span data-ttu-id="0176c-110">取得またはジョブの履歴ファイルを設定します。</span><span class="sxs-lookup"><span data-stu-id="0176c-110">Gets or sets the history file of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobACLs">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.HDInsight.Job.Models.JobACLs JobACLs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.HDInsight.Job.Models.JobACLs JobACLs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Job.Models.Status.JobACLs" />
      <MemberSignature Language="VB.NET" Value="Public Property JobACLs As JobACLs" />
      <MemberSignature Language="F#" Value="member this.JobACLs : Microsoft.Azure.Management.HDInsight.Job.Models.JobACLs with get, set" Usage="Microsoft.Azure.Management.HDInsight.Job.Models.Status.JobACLs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.HDInsight.Job.Models.JobACLs</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0176c-111">省略可能。</span><span class="sxs-lookup"><span data-stu-id="0176c-111">Optional.</span></span> <span data-ttu-id="0176c-112">取得またはジョブの Acl を設定します。</span><span class="sxs-lookup"><span data-stu-id="0176c-112">Gets or sets the ACLs of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobComplete">
      <MemberSignature Language="C#" Value="public bool JobComplete { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool JobComplete" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Job.Models.Status.JobComplete" />
      <MemberSignature Language="VB.NET" Value="Public Property JobComplete As Boolean" />
      <MemberSignature Language="F#" Value="member this.JobComplete : bool with get, set" Usage="Microsoft.Azure.Management.HDInsight.Job.Models.Status.JobComplete" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0176c-113">省略可能。</span><span class="sxs-lookup"><span data-stu-id="0176c-113">Optional.</span></span> <span data-ttu-id="0176c-114">かどうか、ジョブが完了しました。</span><span class="sxs-lookup"><span data-stu-id="0176c-114">Whether or not the job has completed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobFile">
      <MemberSignature Language="C#" Value="public string JobFile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string JobFile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Job.Models.Status.JobFile" />
      <MemberSignature Language="VB.NET" Value="Public Property JobFile As String" />
      <MemberSignature Language="F#" Value="member this.JobFile : string with get, set" Usage="Microsoft.Azure.Management.HDInsight.Job.Models.Status.JobFile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0176c-115">省略可能。</span><span class="sxs-lookup"><span data-stu-id="0176c-115">Optional.</span></span> <span data-ttu-id="0176c-116">取得またはジョブの構成ファイルを設定します。</span><span class="sxs-lookup"><span data-stu-id="0176c-116">Gets or sets the job configuration file.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobId">
      <MemberSignature Language="C#" Value="public string JobId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string JobId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Job.Models.Status.JobId" />
      <MemberSignature Language="VB.NET" Value="Public Property JobId As String" />
      <MemberSignature Language="F#" Value="member this.JobId : string with get, set" Usage="Microsoft.Azure.Management.HDInsight.Job.Models.Status.JobId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0176c-117">省略可能。</span><span class="sxs-lookup"><span data-stu-id="0176c-117">Optional.</span></span> <span data-ttu-id="0176c-118">取得またはジョブの完全 ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="0176c-118">Gets or sets the full ID of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobID">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.HDInsight.Job.Models.JobID JobID { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.HDInsight.Job.Models.JobID JobID" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Job.Models.Status.JobID" />
      <MemberSignature Language="VB.NET" Value="Public Property JobID As JobID" />
      <MemberSignature Language="F#" Value="member this.JobID : Microsoft.Azure.Management.HDInsight.Job.Models.JobID with get, set" Usage="Microsoft.Azure.Management.HDInsight.Job.Models.Status.JobID" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.HDInsight.Job.Models.JobID</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0176c-119">省略可能。</span><span class="sxs-lookup"><span data-stu-id="0176c-119">Optional.</span></span> <span data-ttu-id="0176c-120">取得またはジョブの ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="0176c-120">Gets or sets the ID of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobName">
      <MemberSignature Language="C#" Value="public string JobName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string JobName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Job.Models.Status.JobName" />
      <MemberSignature Language="VB.NET" Value="Public Property JobName As String" />
      <MemberSignature Language="F#" Value="member this.JobName : string with get, set" Usage="Microsoft.Azure.Management.HDInsight.Job.Models.Status.JobName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0176c-121">省略可能。</span><span class="sxs-lookup"><span data-stu-id="0176c-121">Optional.</span></span> <span data-ttu-id="0176c-122">取得またはユーザーが指定されたジョブの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="0176c-122">Gets or sets the user-specified job name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobPriority">
      <MemberSignature Language="C#" Value="public string JobPriority { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string JobPriority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Job.Models.Status.JobPriority" />
      <MemberSignature Language="VB.NET" Value="Public Property JobPriority As String" />
      <MemberSignature Language="F#" Value="member this.JobPriority : string with get, set" Usage="Microsoft.Azure.Management.HDInsight.Job.Models.Status.JobPriority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0176c-123">省略可能。</span><span class="sxs-lookup"><span data-stu-id="0176c-123">Optional.</span></span> <span data-ttu-id="0176c-124">取得またはジョブの優先順位を設定します。</span><span class="sxs-lookup"><span data-stu-id="0176c-124">Gets or sets the priority of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MapProgress">
      <MemberSignature Language="C#" Value="public double MapProgress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 MapProgress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Job.Models.Status.MapProgress" />
      <MemberSignature Language="VB.NET" Value="Public Property MapProgress As Double" />
      <MemberSignature Language="F#" Value="member this.MapProgress : double with get, set" Usage="Microsoft.Azure.Management.HDInsight.Job.Models.Status.MapProgress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0176c-125">省略可能。</span><span class="sxs-lookup"><span data-stu-id="0176c-125">Optional.</span></span> <span data-ttu-id="0176c-126">取得またはマップの進行状況を設定します。</span><span class="sxs-lookup"><span data-stu-id="0176c-126">Gets or sets the progress made on the maps.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NeededMem">
      <MemberSignature Language="C#" Value="public string NeededMem { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NeededMem" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Job.Models.Status.NeededMem" />
      <MemberSignature Language="VB.NET" Value="Public Property NeededMem As String" />
      <MemberSignature Language="F#" Value="member this.NeededMem : string with get, set" Usage="Microsoft.Azure.Management.HDInsight.Job.Models.Status.NeededMem" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0176c-127">省略可能。</span><span class="sxs-lookup"><span data-stu-id="0176c-127">Optional.</span></span> <span data-ttu-id="0176c-128">取得またはジョブに必要なメモリの量を設定します。</span><span class="sxs-lookup"><span data-stu-id="0176c-128">Gets or sets the amount of memory needed for the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NumReservedSlots">
      <MemberSignature Language="C#" Value="public string NumReservedSlots { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NumReservedSlots" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Job.Models.Status.NumReservedSlots" />
      <MemberSignature Language="VB.NET" Value="Public Property NumReservedSlots As String" />
      <MemberSignature Language="F#" Value="member this.NumReservedSlots : string with get, set" Usage="Microsoft.Azure.Management.HDInsight.Job.Models.Status.NumReservedSlots" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0176c-129">省略可能。</span><span class="sxs-lookup"><span data-stu-id="0176c-129">Optional.</span></span> <span data-ttu-id="0176c-130">取得または予約済みのスロットの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="0176c-130">Gets or sets the number of slots reserved.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NumUsedSlots">
      <MemberSignature Language="C#" Value="public string NumUsedSlots { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NumUsedSlots" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Job.Models.Status.NumUsedSlots" />
      <MemberSignature Language="VB.NET" Value="Public Property NumUsedSlots As String" />
      <MemberSignature Language="F#" Value="member this.NumUsedSlots : string with get, set" Usage="Microsoft.Azure.Management.HDInsight.Job.Models.Status.NumUsedSlots" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0176c-131">省略可能。</span><span class="sxs-lookup"><span data-stu-id="0176c-131">Optional.</span></span> <span data-ttu-id="0176c-132">取得またはジョブの使用のスロットの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="0176c-132">Gets or sets the number of slots used for the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Priority">
      <MemberSignature Language="C#" Value="public string Priority { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Priority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Job.Models.Status.Priority" />
      <MemberSignature Language="VB.NET" Value="Public Property Priority As String" />
      <MemberSignature Language="F#" Value="member this.Priority : string with get, set" Usage="Microsoft.Azure.Management.HDInsight.Job.Models.Status.Priority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0176c-133">省略可能。</span><span class="sxs-lookup"><span data-stu-id="0176c-133">Optional.</span></span> <span data-ttu-id="0176c-134">取得またはジョブの優先順位を設定します。</span><span class="sxs-lookup"><span data-stu-id="0176c-134">Gets or sets the priority of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Queue">
      <MemberSignature Language="C#" Value="public string Queue { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Queue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Job.Models.Status.Queue" />
      <MemberSignature Language="VB.NET" Value="Public Property Queue As String" />
      <MemberSignature Language="F#" Value="member this.Queue : string with get, set" Usage="Microsoft.Azure.Management.HDInsight.Job.Models.Status.Queue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0176c-135">省略可能。</span><span class="sxs-lookup"><span data-stu-id="0176c-135">Optional.</span></span> <span data-ttu-id="0176c-136">取得またはジョブ キューの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="0176c-136">Gets or sets the job queue name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReduceProgress">
      <MemberSignature Language="C#" Value="public double ReduceProgress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 ReduceProgress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Job.Models.Status.ReduceProgress" />
      <MemberSignature Language="VB.NET" Value="Public Property ReduceProgress As Double" />
      <MemberSignature Language="F#" Value="member this.ReduceProgress : double with get, set" Usage="Microsoft.Azure.Management.HDInsight.Job.Models.Status.ReduceProgress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0176c-137">省略可能。</span><span class="sxs-lookup"><span data-stu-id="0176c-137">Optional.</span></span> <span data-ttu-id="0176c-138">取得または設定の進行状況が減少します。</span><span class="sxs-lookup"><span data-stu-id="0176c-138">Gets or sets the progress made on the reduces.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReservedMem">
      <MemberSignature Language="C#" Value="public string ReservedMem { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReservedMem" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Job.Models.Status.ReservedMem" />
      <MemberSignature Language="VB.NET" Value="Public Property ReservedMem As String" />
      <MemberSignature Language="F#" Value="member this.ReservedMem : string with get, set" Usage="Microsoft.Azure.Management.HDInsight.Job.Models.Status.ReservedMem" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0176c-139">省略可能。</span><span class="sxs-lookup"><span data-stu-id="0176c-139">Optional.</span></span> <span data-ttu-id="0176c-140">取得またはジョブ用に予約されたメモリの量を設定します。</span><span class="sxs-lookup"><span data-stu-id="0176c-140">Gets or sets the amount of memory reserved for the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Retired">
      <MemberSignature Language="C#" Value="public bool Retired { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool Retired" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Job.Models.Status.Retired" />
      <MemberSignature Language="VB.NET" Value="Public Property Retired As Boolean" />
      <MemberSignature Language="F#" Value="member this.Retired : bool with get, set" Usage="Microsoft.Azure.Management.HDInsight.Job.Models.Status.Retired" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0176c-141">省略可能。</span><span class="sxs-lookup"><span data-stu-id="0176c-141">Optional.</span></span> <span data-ttu-id="0176c-142">かどうかは、ジョブは破棄されました。</span><span class="sxs-lookup"><span data-stu-id="0176c-142">Whether or not the job has been retired.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RunState">
      <MemberSignature Language="C#" Value="public int RunState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 RunState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Job.Models.Status.RunState" />
      <MemberSignature Language="VB.NET" Value="Public Property RunState As Integer" />
      <MemberSignature Language="F#" Value="member this.RunState : int with get, set" Usage="Microsoft.Azure.Management.HDInsight.Job.Models.Status.RunState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0176c-143">省略可能。</span><span class="sxs-lookup"><span data-stu-id="0176c-143">Optional.</span></span> <span data-ttu-id="0176c-144">取得またはジョブの現在の状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="0176c-144">Gets or sets the current state of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SchedulingInfo">
      <MemberSignature Language="C#" Value="public string SchedulingInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SchedulingInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Job.Models.Status.SchedulingInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property SchedulingInfo As String" />
      <MemberSignature Language="F#" Value="member this.SchedulingInfo : string with get, set" Usage="Microsoft.Azure.Management.HDInsight.Job.Models.Status.SchedulingInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0176c-145">省略可能。</span><span class="sxs-lookup"><span data-stu-id="0176c-145">Optional.</span></span> <span data-ttu-id="0176c-146">取得またはジョブのスケジュール設定に関する情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="0176c-146">Gets or sets the information about the scheduling of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetupProgress">
      <MemberSignature Language="C#" Value="public double SetupProgress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 SetupProgress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Job.Models.Status.SetupProgress" />
      <MemberSignature Language="VB.NET" Value="Public Property SetupProgress As Double" />
      <MemberSignature Language="F#" Value="member this.SetupProgress : double with get, set" Usage="Microsoft.Azure.Management.HDInsight.Job.Models.Status.SetupProgress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0176c-147">省略可能。</span><span class="sxs-lookup"><span data-stu-id="0176c-147">Optional.</span></span> <span data-ttu-id="0176c-148">取得または設定の進行状況を設定します。</span><span class="sxs-lookup"><span data-stu-id="0176c-148">Gets or sets the progress made on the setup.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public long StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Job.Models.Status.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As Long" />
      <MemberSignature Language="F#" Value="member this.StartTime : int64 with get, set" Usage="Microsoft.Azure.Management.HDInsight.Job.Models.Status.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0176c-149">省略可能。</span><span class="sxs-lookup"><span data-stu-id="0176c-149">Optional.</span></span> <span data-ttu-id="0176c-150">取得またはジョブが開始された時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="0176c-150">Gets or sets the time at which the job started.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public string State { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Job.Models.Status.State" />
      <MemberSignature Language="VB.NET" Value="Public Property State As String" />
      <MemberSignature Language="F#" Value="member this.State : string with get, set" Usage="Microsoft.Azure.Management.HDInsight.Job.Models.Status.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0176c-151">省略可能。</span><span class="sxs-lookup"><span data-stu-id="0176c-151">Optional.</span></span> <span data-ttu-id="0176c-152">取得またはジョブの状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="0176c-152">Gets or sets the state of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrackingUrl">
      <MemberSignature Language="C#" Value="public string TrackingUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TrackingUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Job.Models.Status.TrackingUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property TrackingUrl As String" />
      <MemberSignature Language="F#" Value="member this.TrackingUrl : string with get, set" Usage="Microsoft.Azure.Management.HDInsight.Job.Models.Status.TrackingUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0176c-153">省略可能。</span><span class="sxs-lookup"><span data-stu-id="0176c-153">Optional.</span></span> <span data-ttu-id="0176c-154">取得またはジョブの詳細については web ui へのリンクを設定します。</span><span class="sxs-lookup"><span data-stu-id="0176c-154">Gets or sets the link to the web-ui for details of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Uber">
      <MemberSignature Language="C#" Value="public bool Uber { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool Uber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Job.Models.Status.Uber" />
      <MemberSignature Language="VB.NET" Value="Public Property Uber As Boolean" />
      <MemberSignature Language="F#" Value="member this.Uber : bool with get, set" Usage="Microsoft.Azure.Management.HDInsight.Job.Models.Status.Uber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0176c-155">省略可能。</span><span class="sxs-lookup"><span data-stu-id="0176c-155">Optional.</span></span> <span data-ttu-id="0176c-156">Uber モードで実行されているジョブかどうか。</span><span class="sxs-lookup"><span data-stu-id="0176c-156">Whether job running in uber mode.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UsedMem">
      <MemberSignature Language="C#" Value="public string UsedMem { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UsedMem" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Job.Models.Status.UsedMem" />
      <MemberSignature Language="VB.NET" Value="Public Property UsedMem As String" />
      <MemberSignature Language="F#" Value="member this.UsedMem : string with get, set" Usage="Microsoft.Azure.Management.HDInsight.Job.Models.Status.UsedMem" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0176c-157">省略可能。</span><span class="sxs-lookup"><span data-stu-id="0176c-157">Optional.</span></span> <span data-ttu-id="0176c-158">取得またはジョブによって使用されるメモリの量を設定します。</span><span class="sxs-lookup"><span data-stu-id="0176c-158">Gets or sets the amount of memory used by the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Username">
      <MemberSignature Language="C#" Value="public string Username { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Username" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Job.Models.Status.Username" />
      <MemberSignature Language="VB.NET" Value="Public Property Username As String" />
      <MemberSignature Language="F#" Value="member this.Username : string with get, set" Usage="Microsoft.Azure.Management.HDInsight.Job.Models.Status.Username" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0176c-159">省略可能。</span><span class="sxs-lookup"><span data-stu-id="0176c-159">Optional.</span></span> <span data-ttu-id="0176c-160">取得またはジョブを送信した人のユーザー id を設定します。</span><span class="sxs-lookup"><span data-stu-id="0176c-160">Gets or sets the userid of the person who submitted the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>