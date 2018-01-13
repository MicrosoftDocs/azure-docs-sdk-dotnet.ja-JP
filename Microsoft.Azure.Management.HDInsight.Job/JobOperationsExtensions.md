<Type Name="JobOperationsExtensions" FullName="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class JobOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit JobOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module JobOperationsExtensions" />
  <TypeSignature Language="F#" Value="type JobOperationsExtensions = class" />
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
            <span data-ttu-id="fa172-101">HDInsight クラスターに対してジョブを管理するための操作です。</span><span class="sxs-lookup"><span data-stu-id="fa172-101">Operations for managing jobs against HDInsight clusters.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetJob">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse GetJob (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, string jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse GetJob(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, string jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.GetJob(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetJob (operations As IJobOperations, jobId As String) As JobGetResponse" />
      <MemberSignature Language="F#" Value="static member GetJob : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * string -&gt; Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.GetJob (operations, jobId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fa172-102">Microsoft.Azure.Management.HDInsight.Job.IJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fa172-102">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="fa172-103">必須。</span><span class="sxs-lookup"><span data-stu-id="fa172-103">Required.</span></span> <span data-ttu-id="fa172-104">ジョブの id。</span><span class="sxs-lookup"><span data-stu-id="fa172-104">The id of the job.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fa172-105">指定した HDInsight クラスターからジョブの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="fa172-105">Gets job details from the specified HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fa172-106">Get Job 操作の応答。</span><span class="sxs-lookup"><span data-stu-id="fa172-106">The Get Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetJobAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse&gt; GetJobAsync (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, string jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse&gt; GetJobAsync(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, string jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.GetJobAsync(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetJobAsync (operations As IJobOperations, jobId As String) As Task(Of JobGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetJobAsync : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse&gt;" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.GetJobAsync (operations, jobId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fa172-107">Microsoft.Azure.Management.HDInsight.Job.IJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fa172-107">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="fa172-108">必須。</span><span class="sxs-lookup"><span data-stu-id="fa172-108">Required.</span></span> <span data-ttu-id="fa172-109">ジョブの id。</span><span class="sxs-lookup"><span data-stu-id="fa172-109">The id of the job.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fa172-110">指定した HDInsight クラスターからジョブの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="fa172-110">Gets job details from the specified HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fa172-111">Get Job 操作の応答。</span><span class="sxs-lookup"><span data-stu-id="fa172-111">The Get Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetJobErrorLogs">
      <MemberSignature Language="C#" Value="public static System.IO.Stream GetJobErrorLogs (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, string jobId, Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess storageAccess);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.IO.Stream GetJobErrorLogs(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, string jobId, class Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess storageAccess) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.GetJobErrorLogs(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,System.String,Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetJobErrorLogs (operations As IJobOperations, jobId As String, storageAccess As IStorageAccess) As Stream" />
      <MemberSignature Language="F#" Value="static member GetJobErrorLogs : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * string * Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess -&gt; System.IO.Stream" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.GetJobErrorLogs (operations, jobId, storageAccess)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IO.Stream</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="storageAccess" Type="Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fa172-112">Microsoft.Azure.Management.HDInsight.Job.IJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fa172-112">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="fa172-113">必須。</span><span class="sxs-lookup"><span data-stu-id="fa172-113">Required.</span></span> <span data-ttu-id="fa172-114">ジョブの id。</span><span class="sxs-lookup"><span data-stu-id="fa172-114">The id of the job.</span></span>
            </param>
        <param name="storageAccess">
            <span data-ttu-id="fa172-115">必須。</span><span class="sxs-lookup"><span data-stu-id="fa172-115">Required.</span></span> <span data-ttu-id="fa172-116">型 IStorageAccess のストレージ アカウント オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="fa172-116">The storage account object of type IStorageAccess.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fa172-117">個々 の jobDetails の実行からのエラー ログを取得します。</span><span class="sxs-lookup"><span data-stu-id="fa172-117">Gets the error logs from the execution of an individual jobDetails.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fa172-118">JobId によって個々 の jobDetails のエラー ログ。</span><span class="sxs-lookup"><span data-stu-id="fa172-118">The error logs of an individual jobDetails by jobId.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetJobErrorLogsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.IO.Stream&gt; GetJobErrorLogsAsync (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, string jobId, Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess storageAccess);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.IO.Stream&gt; GetJobErrorLogsAsync(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, string jobId, class Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess storageAccess) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.GetJobErrorLogsAsync(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,System.String,Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetJobErrorLogsAsync (operations As IJobOperations, jobId As String, storageAccess As IStorageAccess) As Task(Of Stream)" />
      <MemberSignature Language="F#" Value="static member GetJobErrorLogsAsync : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * string * Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess -&gt; System.Threading.Tasks.Task&lt;System.IO.Stream&gt;" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.GetJobErrorLogsAsync (operations, jobId, storageAccess)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.IO.Stream&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="storageAccess" Type="Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fa172-119">Microsoft.Azure.Management.HDInsight.Job.IJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fa172-119">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="fa172-120">必須。</span><span class="sxs-lookup"><span data-stu-id="fa172-120">Required.</span></span> <span data-ttu-id="fa172-121">ジョブの id。</span><span class="sxs-lookup"><span data-stu-id="fa172-121">The id of the job.</span></span>
            </param>
        <param name="storageAccess">
            <span data-ttu-id="fa172-122">必須。</span><span class="sxs-lookup"><span data-stu-id="fa172-122">Required.</span></span> <span data-ttu-id="fa172-123">型 IStorageAccess のストレージ アカウント オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="fa172-123">The storage account object of type IStorageAccess.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fa172-124">個々 の jobDetails の実行からのエラー ログを取得します。</span><span class="sxs-lookup"><span data-stu-id="fa172-124">Gets the error logs from the execution of an individual jobDetails.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fa172-125">JobId によって個々 の jobDetails のエラー ログ。</span><span class="sxs-lookup"><span data-stu-id="fa172-125">The error logs of an individual jobDetails by jobId.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetJobOutput">
      <MemberSignature Language="C#" Value="public static System.IO.Stream GetJobOutput (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, string jobId, Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess storageAccess);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.IO.Stream GetJobOutput(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, string jobId, class Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess storageAccess) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.GetJobOutput(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,System.String,Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetJobOutput (operations As IJobOperations, jobId As String, storageAccess As IStorageAccess) As Stream" />
      <MemberSignature Language="F#" Value="static member GetJobOutput : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * string * Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess -&gt; System.IO.Stream" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.GetJobOutput (operations, jobId, storageAccess)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IO.Stream</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="storageAccess" Type="Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fa172-126">Microsoft.Azure.Management.HDInsight.Job.IJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fa172-126">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="fa172-127">必須。</span><span class="sxs-lookup"><span data-stu-id="fa172-127">Required.</span></span> <span data-ttu-id="fa172-128">ジョブの id。</span><span class="sxs-lookup"><span data-stu-id="fa172-128">The id of the job.</span></span>
            </param>
        <param name="storageAccess">
            <span data-ttu-id="fa172-129">必須。</span><span class="sxs-lookup"><span data-stu-id="fa172-129">Required.</span></span> <span data-ttu-id="fa172-130">型 IStorageAccess のストレージ アカウント オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="fa172-130">The storage account object of type IStorageAccess.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fa172-131">個々 の jobDetails の実行からの出力を取得します。</span><span class="sxs-lookup"><span data-stu-id="fa172-131">Gets the output from the execution of an individual jobDetails.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fa172-132">JobId によって個々 の jobDetails の出力。</span><span class="sxs-lookup"><span data-stu-id="fa172-132">The output of an individual jobDetails by jobId.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetJobOutputAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.IO.Stream&gt; GetJobOutputAsync (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, string jobId, Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess storageAccess);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.IO.Stream&gt; GetJobOutputAsync(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, string jobId, class Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess storageAccess) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.GetJobOutputAsync(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,System.String,Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetJobOutputAsync (operations As IJobOperations, jobId As String, storageAccess As IStorageAccess) As Task(Of Stream)" />
      <MemberSignature Language="F#" Value="static member GetJobOutputAsync : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * string * Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess -&gt; System.Threading.Tasks.Task&lt;System.IO.Stream&gt;" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.GetJobOutputAsync (operations, jobId, storageAccess)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.IO.Stream&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="storageAccess" Type="Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fa172-133">Microsoft.Azure.Management.HDInsight.Job.IJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fa172-133">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="fa172-134">必須。</span><span class="sxs-lookup"><span data-stu-id="fa172-134">Required.</span></span> <span data-ttu-id="fa172-135">ジョブの id。</span><span class="sxs-lookup"><span data-stu-id="fa172-135">The id of the job.</span></span>
            </param>
        <param name="storageAccess">
            <span data-ttu-id="fa172-136">必須。</span><span class="sxs-lookup"><span data-stu-id="fa172-136">Required.</span></span> <span data-ttu-id="fa172-137">型 IStorageAccess のストレージ アカウント オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="fa172-137">The storage account object of type IStorageAccess.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fa172-138">個々 の jobDetails の実行からの出力を取得します。</span><span class="sxs-lookup"><span data-stu-id="fa172-138">Gets the output from the execution of an individual jobDetails.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fa172-139">JobId によって個々 の jobDetails の出力。</span><span class="sxs-lookup"><span data-stu-id="fa172-139">The output of an individual jobDetails by jobId.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KillJob">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse KillJob (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, string jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse KillJob(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, string jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.KillJob(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function KillJob (operations As IJobOperations, jobId As String) As JobGetResponse" />
      <MemberSignature Language="F#" Value="static member KillJob : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * string -&gt; Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.KillJob (operations, jobId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fa172-140">Microsoft.Azure.Management.HDInsight.Job.IJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fa172-140">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="fa172-141">必須。</span><span class="sxs-lookup"><span data-stu-id="fa172-141">Required.</span></span> <span data-ttu-id="fa172-142">ジョブの id。</span><span class="sxs-lookup"><span data-stu-id="fa172-142">The id of the job.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fa172-143">開始キャンセルで指定した HDInsight クラスターで実行中のジョブを指定します。</span><span class="sxs-lookup"><span data-stu-id="fa172-143">Initiates cancel on given running job in the specified HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fa172-144">Get Job 操作の応答。</span><span class="sxs-lookup"><span data-stu-id="fa172-144">The Get Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KillJobAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse&gt; KillJobAsync (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, string jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse&gt; KillJobAsync(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, string jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.KillJobAsync(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function KillJobAsync (operations As IJobOperations, jobId As String) As Task(Of JobGetResponse)" />
      <MemberSignature Language="F#" Value="static member KillJobAsync : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse&gt;" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.KillJobAsync (operations, jobId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fa172-145">Microsoft.Azure.Management.HDInsight.Job.IJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fa172-145">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="fa172-146">必須。</span><span class="sxs-lookup"><span data-stu-id="fa172-146">Required.</span></span> <span data-ttu-id="fa172-147">ジョブの id。</span><span class="sxs-lookup"><span data-stu-id="fa172-147">The id of the job.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fa172-148">開始キャンセルで指定した HDInsight クラスターで実行中のジョブを指定します。</span><span class="sxs-lookup"><span data-stu-id="fa172-148">Initiates cancel on given running job in the specified HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fa172-149">Get Job 操作の応答。</span><span class="sxs-lookup"><span data-stu-id="fa172-149">The Get Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListJobs">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.HDInsight.Job.Models.JobListResponse ListJobs (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.HDInsight.Job.Models.JobListResponse ListJobs(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.ListJobs(Microsoft.Azure.Management.HDInsight.Job.IJobOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListJobs (operations As IJobOperations) As JobListResponse" />
      <MemberSignature Language="F#" Value="static member ListJobs : Microsoft.Azure.Management.HDInsight.Job.IJobOperations -&gt; Microsoft.Azure.Management.HDInsight.Job.Models.JobListResponse" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.ListJobs operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.HDInsight.Job.Models.JobListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fa172-150">Microsoft.Azure.Management.HDInsight.Job.IJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fa172-150">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fa172-151">指定した HDInsight クラスターからジョブの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="fa172-151">Gets the list of jobs from the specified HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fa172-152">一覧のジョブ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="fa172-152">The List Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListJobsAfterJobId">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.HDInsight.Job.Models.JobListResponse ListJobsAfterJobId (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, string jobId, int numOfJobs);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.HDInsight.Job.Models.JobListResponse ListJobsAfterJobId(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, string jobId, int32 numOfJobs) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.ListJobsAfterJobId(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListJobsAfterJobId (operations As IJobOperations, jobId As String, numOfJobs As Integer) As JobListResponse" />
      <MemberSignature Language="F#" Value="static member ListJobsAfterJobId : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * string * int -&gt; Microsoft.Azure.Management.HDInsight.Job.Models.JobListResponse" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.ListJobsAfterJobId (operations, jobId, numOfJobs)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.HDInsight.Job.Models.JobListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="numOfJobs" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fa172-153">Microsoft.Azure.Management.HDInsight.Job.IJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fa172-153">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="fa172-154">省略可能。</span><span class="sxs-lookup"><span data-stu-id="fa172-154">Optional.</span></span> <span data-ttu-id="fa172-155">ジョブはどこからの Id でジョブを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="fa172-155">jobId from where to list jobs.</span></span>
            </param>
        <param name="numOfJobs">
            <span data-ttu-id="fa172-156">必須。</span><span class="sxs-lookup"><span data-stu-id="fa172-156">Required.</span></span> <span data-ttu-id="fa172-157">ジョブの数を取得します。</span><span class="sxs-lookup"><span data-stu-id="fa172-157">Number of jobs to fetch.</span></span> <span data-ttu-id="fa172-158">すべてを取得するには、-1 を使用します。</span><span class="sxs-lookup"><span data-stu-id="fa172-158">Use -1 to get all.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fa172-159">指定した HDInsight クラスターから jobId 後 numOfJobs を取得します。</span><span class="sxs-lookup"><span data-stu-id="fa172-159">Gets numOfJobs after jobId from the specified HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fa172-160">一覧のジョブ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="fa172-160">The List Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListJobsAfterJobIdAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobListResponse&gt; ListJobsAfterJobIdAsync (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, string jobId, int numOfJobs);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.HDInsight.Job.Models.JobListResponse&gt; ListJobsAfterJobIdAsync(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, string jobId, int32 numOfJobs) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.ListJobsAfterJobIdAsync(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListJobsAfterJobIdAsync (operations As IJobOperations, jobId As String, numOfJobs As Integer) As Task(Of JobListResponse)" />
      <MemberSignature Language="F#" Value="static member ListJobsAfterJobIdAsync : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * string * int -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobListResponse&gt;" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.ListJobsAfterJobIdAsync (operations, jobId, numOfJobs)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="numOfJobs" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fa172-161">Microsoft.Azure.Management.HDInsight.Job.IJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fa172-161">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="fa172-162">省略可能。</span><span class="sxs-lookup"><span data-stu-id="fa172-162">Optional.</span></span> <span data-ttu-id="fa172-163">ジョブはどこからの Id でジョブを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="fa172-163">jobId from where to list jobs.</span></span>
            </param>
        <param name="numOfJobs">
            <span data-ttu-id="fa172-164">必須。</span><span class="sxs-lookup"><span data-stu-id="fa172-164">Required.</span></span> <span data-ttu-id="fa172-165">ジョブの数を取得します。</span><span class="sxs-lookup"><span data-stu-id="fa172-165">Number of jobs to fetch.</span></span> <span data-ttu-id="fa172-166">すべてを取得するには、-1 を使用します。</span><span class="sxs-lookup"><span data-stu-id="fa172-166">Use -1 to get all.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fa172-167">指定した HDInsight クラスターから jobId 後 numOfJobs を取得します。</span><span class="sxs-lookup"><span data-stu-id="fa172-167">Gets numOfJobs after jobId from the specified HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fa172-168">一覧のジョブ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="fa172-168">The List Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListJobsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobListResponse&gt; ListJobsAsync (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.HDInsight.Job.Models.JobListResponse&gt; ListJobsAsync(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.ListJobsAsync(Microsoft.Azure.Management.HDInsight.Job.IJobOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListJobsAsync (operations As IJobOperations) As Task(Of JobListResponse)" />
      <MemberSignature Language="F#" Value="static member ListJobsAsync : Microsoft.Azure.Management.HDInsight.Job.IJobOperations -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobListResponse&gt;" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.ListJobsAsync operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fa172-169">Microsoft.Azure.Management.HDInsight.Job.IJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fa172-169">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fa172-170">指定した HDInsight クラスターからジョブの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="fa172-170">Gets the list of jobs from the specified HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fa172-171">一覧のジョブ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="fa172-171">The List Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitHiveJob">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse SubmitHiveJob (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, Microsoft.Azure.Management.HDInsight.Job.Models.HiveJobSubmissionParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse SubmitHiveJob(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, class Microsoft.Azure.Management.HDInsight.Job.Models.HiveJobSubmissionParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitHiveJob(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,Microsoft.Azure.Management.HDInsight.Job.Models.HiveJobSubmissionParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SubmitHiveJob (operations As IJobOperations, parameters As HiveJobSubmissionParameters) As JobSubmissionResponse" />
      <MemberSignature Language="F#" Value="static member SubmitHiveJob : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * Microsoft.Azure.Management.HDInsight.Job.Models.HiveJobSubmissionParameters -&gt; Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitHiveJob (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Job.Models.HiveJobSubmissionParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fa172-172">Microsoft.Azure.Management.HDInsight.Job.IJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fa172-172">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fa172-173">必須。</span><span class="sxs-lookup"><span data-stu-id="fa172-173">Required.</span></span> <span data-ttu-id="fa172-174">ジョブのパラメーターを hive します。</span><span class="sxs-lookup"><span data-stu-id="fa172-174">Hive job parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fa172-175">HDInsight クラスターに Hive ジョブを送信します。</span><span class="sxs-lookup"><span data-stu-id="fa172-175">Submits a Hive job to an HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fa172-176">ジョブの作成操作の応答。</span><span class="sxs-lookup"><span data-stu-id="fa172-176">The Create Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitHiveJob">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse SubmitHiveJob (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse SubmitHiveJob(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitHiveJob(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SubmitHiveJob (operations As IJobOperations, parameters As JobSubmissionParameters) As JobSubmissionResponse" />
      <MemberSignature Language="F#" Value="static member SubmitHiveJob : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters -&gt; Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitHiveJob (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fa172-177">Microsoft.Azure.Management.HDInsight.Job.IJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fa172-177">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fa172-178">必須。</span><span class="sxs-lookup"><span data-stu-id="fa172-178">Required.</span></span> <span data-ttu-id="fa172-179">ジョブのパラメーターを hive します。</span><span class="sxs-lookup"><span data-stu-id="fa172-179">Hive job parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fa172-180">HDInsight クラスターに Hive ジョブを送信します。</span><span class="sxs-lookup"><span data-stu-id="fa172-180">Submits a Hive job to an HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fa172-181">ジョブの作成操作の応答。</span><span class="sxs-lookup"><span data-stu-id="fa172-181">The Create Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitHiveJobAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitHiveJobAsync (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, Microsoft.Azure.Management.HDInsight.Job.Models.HiveJobSubmissionParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitHiveJobAsync(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, class Microsoft.Azure.Management.HDInsight.Job.Models.HiveJobSubmissionParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitHiveJobAsync(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,Microsoft.Azure.Management.HDInsight.Job.Models.HiveJobSubmissionParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SubmitHiveJobAsync (operations As IJobOperations, parameters As HiveJobSubmissionParameters) As Task(Of JobSubmissionResponse)" />
      <MemberSignature Language="F#" Value="static member SubmitHiveJobAsync : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * Microsoft.Azure.Management.HDInsight.Job.Models.HiveJobSubmissionParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitHiveJobAsync (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Job.Models.HiveJobSubmissionParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fa172-182">Microsoft.Azure.Management.HDInsight.Job.IJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fa172-182">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fa172-183">必須。</span><span class="sxs-lookup"><span data-stu-id="fa172-183">Required.</span></span> <span data-ttu-id="fa172-184">ジョブのパラメーターを hive します。</span><span class="sxs-lookup"><span data-stu-id="fa172-184">Hive job parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fa172-185">HDInsight クラスターに Hive ジョブを送信します。</span><span class="sxs-lookup"><span data-stu-id="fa172-185">Submits a Hive job to an HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fa172-186">ジョブの作成操作の応答。</span><span class="sxs-lookup"><span data-stu-id="fa172-186">The Create Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitHiveJobAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitHiveJobAsync (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitHiveJobAsync(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitHiveJobAsync(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SubmitHiveJobAsync (operations As IJobOperations, parameters As JobSubmissionParameters) As Task(Of JobSubmissionResponse)" />
      <MemberSignature Language="F#" Value="static member SubmitHiveJobAsync : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitHiveJobAsync (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fa172-187">Microsoft.Azure.Management.HDInsight.Job.IJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fa172-187">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fa172-188">必須。</span><span class="sxs-lookup"><span data-stu-id="fa172-188">Required.</span></span> <span data-ttu-id="fa172-189">ジョブのパラメーターを hive します。</span><span class="sxs-lookup"><span data-stu-id="fa172-189">Hive job parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fa172-190">HDInsight クラスターに Hive ジョブを送信します。</span><span class="sxs-lookup"><span data-stu-id="fa172-190">Submits a Hive job to an HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fa172-191">ジョブの作成操作の応答。</span><span class="sxs-lookup"><span data-stu-id="fa172-191">The Create Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitMapReduceJob">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse SubmitMapReduceJob (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse SubmitMapReduceJob(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitMapReduceJob(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SubmitMapReduceJob (operations As IJobOperations, parameters As JobSubmissionParameters) As JobSubmissionResponse" />
      <MemberSignature Language="F#" Value="static member SubmitMapReduceJob : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters -&gt; Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitMapReduceJob (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fa172-192">Microsoft.Azure.Management.HDInsight.Job.IJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fa172-192">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fa172-193">必須。</span><span class="sxs-lookup"><span data-stu-id="fa172-193">Required.</span></span> <span data-ttu-id="fa172-194">MapReduce ジョブのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="fa172-194">MapReduce job parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fa172-195">HDInsight クラスターに MapReduce ジョブを送信します。</span><span class="sxs-lookup"><span data-stu-id="fa172-195">Submits a MapReduce job to an HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fa172-196">ジョブの作成操作の応答。</span><span class="sxs-lookup"><span data-stu-id="fa172-196">The Create Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitMapReduceJob">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse SubmitMapReduceJob (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, Microsoft.Azure.Management.HDInsight.Job.Models.MapReduceJobSubmissionParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse SubmitMapReduceJob(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, class Microsoft.Azure.Management.HDInsight.Job.Models.MapReduceJobSubmissionParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitMapReduceJob(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,Microsoft.Azure.Management.HDInsight.Job.Models.MapReduceJobSubmissionParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SubmitMapReduceJob (operations As IJobOperations, parameters As MapReduceJobSubmissionParameters) As JobSubmissionResponse" />
      <MemberSignature Language="F#" Value="static member SubmitMapReduceJob : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * Microsoft.Azure.Management.HDInsight.Job.Models.MapReduceJobSubmissionParameters -&gt; Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitMapReduceJob (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Job.Models.MapReduceJobSubmissionParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fa172-197">Microsoft.Azure.Management.HDInsight.Job.IJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fa172-197">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fa172-198">必須。</span><span class="sxs-lookup"><span data-stu-id="fa172-198">Required.</span></span> <span data-ttu-id="fa172-199">MapReduce ジョブのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="fa172-199">MapReduce job parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fa172-200">HDInsight クラスターに MapReduce ジョブを送信します。</span><span class="sxs-lookup"><span data-stu-id="fa172-200">Submits a MapReduce job to an HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fa172-201">ジョブの作成操作の応答。</span><span class="sxs-lookup"><span data-stu-id="fa172-201">The Create Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitMapReduceJobAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitMapReduceJobAsync (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitMapReduceJobAsync(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitMapReduceJobAsync(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SubmitMapReduceJobAsync (operations As IJobOperations, parameters As JobSubmissionParameters) As Task(Of JobSubmissionResponse)" />
      <MemberSignature Language="F#" Value="static member SubmitMapReduceJobAsync : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitMapReduceJobAsync (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fa172-202">Microsoft.Azure.Management.HDInsight.Job.IJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fa172-202">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fa172-203">必須。</span><span class="sxs-lookup"><span data-stu-id="fa172-203">Required.</span></span> <span data-ttu-id="fa172-204">MapReduce ジョブのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="fa172-204">MapReduce job parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fa172-205">HDInsight クラスターに MapReduce ジョブを送信します。</span><span class="sxs-lookup"><span data-stu-id="fa172-205">Submits a MapReduce job to an HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fa172-206">ジョブの作成操作の応答。</span><span class="sxs-lookup"><span data-stu-id="fa172-206">The Create Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitMapReduceJobAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitMapReduceJobAsync (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, Microsoft.Azure.Management.HDInsight.Job.Models.MapReduceJobSubmissionParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitMapReduceJobAsync(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, class Microsoft.Azure.Management.HDInsight.Job.Models.MapReduceJobSubmissionParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitMapReduceJobAsync(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,Microsoft.Azure.Management.HDInsight.Job.Models.MapReduceJobSubmissionParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SubmitMapReduceJobAsync (operations As IJobOperations, parameters As MapReduceJobSubmissionParameters) As Task(Of JobSubmissionResponse)" />
      <MemberSignature Language="F#" Value="static member SubmitMapReduceJobAsync : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * Microsoft.Azure.Management.HDInsight.Job.Models.MapReduceJobSubmissionParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitMapReduceJobAsync (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Job.Models.MapReduceJobSubmissionParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fa172-207">Microsoft.Azure.Management.HDInsight.Job.IJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fa172-207">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fa172-208">必須。</span><span class="sxs-lookup"><span data-stu-id="fa172-208">Required.</span></span> <span data-ttu-id="fa172-209">MapReduce ジョブのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="fa172-209">MapReduce job parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fa172-210">HDInsight クラスターに MapReduce ジョブを送信します。</span><span class="sxs-lookup"><span data-stu-id="fa172-210">Submits a MapReduce job to an HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fa172-211">ジョブの作成操作の応答。</span><span class="sxs-lookup"><span data-stu-id="fa172-211">The Create Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitMapReduceStreamingJob">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse SubmitMapReduceStreamingJob (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse SubmitMapReduceStreamingJob(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitMapReduceStreamingJob(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SubmitMapReduceStreamingJob (operations As IJobOperations, parameters As JobSubmissionParameters) As JobSubmissionResponse" />
      <MemberSignature Language="F#" Value="static member SubmitMapReduceStreamingJob : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters -&gt; Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitMapReduceStreamingJob (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fa172-212">Microsoft.Azure.Management.HDInsight.Job.IJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fa172-212">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fa172-213">必須。</span><span class="sxs-lookup"><span data-stu-id="fa172-213">Required.</span></span> <span data-ttu-id="fa172-214">MapReduce ジョブのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="fa172-214">MapReduce job parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fa172-215">HDInsight クラスターにストリーミング MapReduce ジョブを送信します。</span><span class="sxs-lookup"><span data-stu-id="fa172-215">Submits a MapReduce streaming job to an HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fa172-216">ジョブの作成操作の応答。</span><span class="sxs-lookup"><span data-stu-id="fa172-216">The Create Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitMapReduceStreamingJob">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse SubmitMapReduceStreamingJob (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, Microsoft.Azure.Management.HDInsight.Job.Models.MapReduceStreamingJobSubmissionParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse SubmitMapReduceStreamingJob(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, class Microsoft.Azure.Management.HDInsight.Job.Models.MapReduceStreamingJobSubmissionParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitMapReduceStreamingJob(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,Microsoft.Azure.Management.HDInsight.Job.Models.MapReduceStreamingJobSubmissionParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SubmitMapReduceStreamingJob (operations As IJobOperations, parameters As MapReduceStreamingJobSubmissionParameters) As JobSubmissionResponse" />
      <MemberSignature Language="F#" Value="static member SubmitMapReduceStreamingJob : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * Microsoft.Azure.Management.HDInsight.Job.Models.MapReduceStreamingJobSubmissionParameters -&gt; Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitMapReduceStreamingJob (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Job.Models.MapReduceStreamingJobSubmissionParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fa172-217">Microsoft.Azure.Management.HDInsight.Job.IJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fa172-217">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fa172-218">必須。</span><span class="sxs-lookup"><span data-stu-id="fa172-218">Required.</span></span> <span data-ttu-id="fa172-219">MapReduce ジョブのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="fa172-219">MapReduce job parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fa172-220">HDInsight クラスターにストリーミング MapReduce ジョブを送信します。</span><span class="sxs-lookup"><span data-stu-id="fa172-220">Submits a MapReduce streaming job to an HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fa172-221">ジョブの作成操作の応答。</span><span class="sxs-lookup"><span data-stu-id="fa172-221">The Create Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitMapReduceStreamingJobAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitMapReduceStreamingJobAsync (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitMapReduceStreamingJobAsync(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitMapReduceStreamingJobAsync(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SubmitMapReduceStreamingJobAsync (operations As IJobOperations, parameters As JobSubmissionParameters) As Task(Of JobSubmissionResponse)" />
      <MemberSignature Language="F#" Value="static member SubmitMapReduceStreamingJobAsync : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitMapReduceStreamingJobAsync (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fa172-222">Microsoft.Azure.Management.HDInsight.Job.IJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fa172-222">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fa172-223">必須。</span><span class="sxs-lookup"><span data-stu-id="fa172-223">Required.</span></span> <span data-ttu-id="fa172-224">MapReduce ジョブのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="fa172-224">MapReduce job parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fa172-225">HDInsight クラスターにストリーミング MapReduce ジョブを送信します。</span><span class="sxs-lookup"><span data-stu-id="fa172-225">Submits a MapReduce streaming job to an HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fa172-226">ジョブの作成操作の応答。</span><span class="sxs-lookup"><span data-stu-id="fa172-226">The Create Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitMapReduceStreamingJobAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitMapReduceStreamingJobAsync (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, Microsoft.Azure.Management.HDInsight.Job.Models.MapReduceStreamingJobSubmissionParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitMapReduceStreamingJobAsync(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, class Microsoft.Azure.Management.HDInsight.Job.Models.MapReduceStreamingJobSubmissionParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitMapReduceStreamingJobAsync(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,Microsoft.Azure.Management.HDInsight.Job.Models.MapReduceStreamingJobSubmissionParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SubmitMapReduceStreamingJobAsync (operations As IJobOperations, parameters As MapReduceStreamingJobSubmissionParameters) As Task(Of JobSubmissionResponse)" />
      <MemberSignature Language="F#" Value="static member SubmitMapReduceStreamingJobAsync : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * Microsoft.Azure.Management.HDInsight.Job.Models.MapReduceStreamingJobSubmissionParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitMapReduceStreamingJobAsync (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Job.Models.MapReduceStreamingJobSubmissionParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fa172-227">Microsoft.Azure.Management.HDInsight.Job.IJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fa172-227">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fa172-228">必須。</span><span class="sxs-lookup"><span data-stu-id="fa172-228">Required.</span></span> <span data-ttu-id="fa172-229">MapReduce ジョブのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="fa172-229">MapReduce job parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fa172-230">HDInsight クラスターにストリーミング MapReduce ジョブを送信します。</span><span class="sxs-lookup"><span data-stu-id="fa172-230">Submits a MapReduce streaming job to an HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fa172-231">ジョブの作成操作の応答。</span><span class="sxs-lookup"><span data-stu-id="fa172-231">The Create Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitPigJob">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse SubmitPigJob (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse SubmitPigJob(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitPigJob(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SubmitPigJob (operations As IJobOperations, parameters As JobSubmissionParameters) As JobSubmissionResponse" />
      <MemberSignature Language="F#" Value="static member SubmitPigJob : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters -&gt; Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitPigJob (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fa172-232">Microsoft.Azure.Management.HDInsight.Job.IJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fa172-232">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fa172-233">必須。</span><span class="sxs-lookup"><span data-stu-id="fa172-233">Required.</span></span> <span data-ttu-id="fa172-234">Pig ジョブのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="fa172-234">Pig job parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fa172-235">HDInsight クラスターに Pig ジョブを送信します。</span><span class="sxs-lookup"><span data-stu-id="fa172-235">Submits a Pig job to an HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fa172-236">ジョブの作成操作の応答。</span><span class="sxs-lookup"><span data-stu-id="fa172-236">The Create Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitPigJob">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse SubmitPigJob (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, Microsoft.Azure.Management.HDInsight.Job.Models.PigJobSubmissionParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse SubmitPigJob(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, class Microsoft.Azure.Management.HDInsight.Job.Models.PigJobSubmissionParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitPigJob(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,Microsoft.Azure.Management.HDInsight.Job.Models.PigJobSubmissionParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SubmitPigJob (operations As IJobOperations, parameters As PigJobSubmissionParameters) As JobSubmissionResponse" />
      <MemberSignature Language="F#" Value="static member SubmitPigJob : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * Microsoft.Azure.Management.HDInsight.Job.Models.PigJobSubmissionParameters -&gt; Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitPigJob (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Job.Models.PigJobSubmissionParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fa172-237">Microsoft.Azure.Management.HDInsight.Job.IJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fa172-237">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fa172-238">必須。</span><span class="sxs-lookup"><span data-stu-id="fa172-238">Required.</span></span> <span data-ttu-id="fa172-239">Pig ジョブのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="fa172-239">Pig job parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fa172-240">HDInsight クラスターに Pig ジョブを送信します。</span><span class="sxs-lookup"><span data-stu-id="fa172-240">Submits a Pig job to an HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fa172-241">ジョブの作成操作の応答。</span><span class="sxs-lookup"><span data-stu-id="fa172-241">The Create Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitPigJobAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitPigJobAsync (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitPigJobAsync(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitPigJobAsync(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SubmitPigJobAsync (operations As IJobOperations, parameters As JobSubmissionParameters) As Task(Of JobSubmissionResponse)" />
      <MemberSignature Language="F#" Value="static member SubmitPigJobAsync : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitPigJobAsync (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fa172-242">Microsoft.Azure.Management.HDInsight.Job.IJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fa172-242">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fa172-243">必須。</span><span class="sxs-lookup"><span data-stu-id="fa172-243">Required.</span></span> <span data-ttu-id="fa172-244">Pig ジョブのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="fa172-244">Pig job parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fa172-245">HDInsight クラスターに Pig ジョブを送信します。</span><span class="sxs-lookup"><span data-stu-id="fa172-245">Submits a Pig job to an HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fa172-246">ジョブの作成操作の応答。</span><span class="sxs-lookup"><span data-stu-id="fa172-246">The Create Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitPigJobAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitPigJobAsync (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, Microsoft.Azure.Management.HDInsight.Job.Models.PigJobSubmissionParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitPigJobAsync(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, class Microsoft.Azure.Management.HDInsight.Job.Models.PigJobSubmissionParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitPigJobAsync(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,Microsoft.Azure.Management.HDInsight.Job.Models.PigJobSubmissionParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SubmitPigJobAsync (operations As IJobOperations, parameters As PigJobSubmissionParameters) As Task(Of JobSubmissionResponse)" />
      <MemberSignature Language="F#" Value="static member SubmitPigJobAsync : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * Microsoft.Azure.Management.HDInsight.Job.Models.PigJobSubmissionParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitPigJobAsync (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Job.Models.PigJobSubmissionParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fa172-247">Microsoft.Azure.Management.HDInsight.Job.IJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fa172-247">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fa172-248">必須。</span><span class="sxs-lookup"><span data-stu-id="fa172-248">Required.</span></span> <span data-ttu-id="fa172-249">Pig ジョブのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="fa172-249">Pig job parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fa172-250">HDInsight クラスターに Pig ジョブを送信します。</span><span class="sxs-lookup"><span data-stu-id="fa172-250">Submits a Pig job to an HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fa172-251">ジョブの作成操作の応答。</span><span class="sxs-lookup"><span data-stu-id="fa172-251">The Create Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitSqoopJob">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse SubmitSqoopJob (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse SubmitSqoopJob(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitSqoopJob(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SubmitSqoopJob (operations As IJobOperations, parameters As JobSubmissionParameters) As JobSubmissionResponse" />
      <MemberSignature Language="F#" Value="static member SubmitSqoopJob : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters -&gt; Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitSqoopJob (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fa172-252">Microsoft.Azure.Management.HDInsight.Job.IJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fa172-252">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fa172-253">必須。</span><span class="sxs-lookup"><span data-stu-id="fa172-253">Required.</span></span> <span data-ttu-id="fa172-254">Sqoop ジョブのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="fa172-254">Sqoop job parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fa172-255">HDInsight クラスターに Sqoop ジョブを送信します。</span><span class="sxs-lookup"><span data-stu-id="fa172-255">Submits a Sqoop job to an HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fa172-256">ジョブの作成操作の応答。</span><span class="sxs-lookup"><span data-stu-id="fa172-256">The Create Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitSqoopJob">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse SubmitSqoopJob (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, Microsoft.Azure.Management.HDInsight.Job.Models.SqoopJobSubmissionParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse SubmitSqoopJob(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, class Microsoft.Azure.Management.HDInsight.Job.Models.SqoopJobSubmissionParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitSqoopJob(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,Microsoft.Azure.Management.HDInsight.Job.Models.SqoopJobSubmissionParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SubmitSqoopJob (operations As IJobOperations, parameters As SqoopJobSubmissionParameters) As JobSubmissionResponse" />
      <MemberSignature Language="F#" Value="static member SubmitSqoopJob : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * Microsoft.Azure.Management.HDInsight.Job.Models.SqoopJobSubmissionParameters -&gt; Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitSqoopJob (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Job.Models.SqoopJobSubmissionParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fa172-257">Microsoft.Azure.Management.HDInsight.Job.IJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fa172-257">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fa172-258">必須。</span><span class="sxs-lookup"><span data-stu-id="fa172-258">Required.</span></span> <span data-ttu-id="fa172-259">Sqoop ジョブのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="fa172-259">Sqoop job parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fa172-260">HDInsight クラスターに Sqoop ジョブを送信します。</span><span class="sxs-lookup"><span data-stu-id="fa172-260">Submits a Sqoop job to an HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fa172-261">ジョブの作成操作の応答。</span><span class="sxs-lookup"><span data-stu-id="fa172-261">The Create Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitSqoopJobAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitSqoopJobAsync (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitSqoopJobAsync(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitSqoopJobAsync(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SubmitSqoopJobAsync (operations As IJobOperations, parameters As JobSubmissionParameters) As Task(Of JobSubmissionResponse)" />
      <MemberSignature Language="F#" Value="static member SubmitSqoopJobAsync : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitSqoopJobAsync (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fa172-262">Microsoft.Azure.Management.HDInsight.Job.IJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fa172-262">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fa172-263">必須。</span><span class="sxs-lookup"><span data-stu-id="fa172-263">Required.</span></span> <span data-ttu-id="fa172-264">Sqoop ジョブのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="fa172-264">Sqoop job parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fa172-265">HDInsight クラスターに Sqoop ジョブを送信します。</span><span class="sxs-lookup"><span data-stu-id="fa172-265">Submits a Sqoop job to an HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fa172-266">ジョブの作成操作の応答。</span><span class="sxs-lookup"><span data-stu-id="fa172-266">The Create Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitSqoopJobAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitSqoopJobAsync (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, Microsoft.Azure.Management.HDInsight.Job.Models.SqoopJobSubmissionParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitSqoopJobAsync(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, class Microsoft.Azure.Management.HDInsight.Job.Models.SqoopJobSubmissionParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitSqoopJobAsync(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,Microsoft.Azure.Management.HDInsight.Job.Models.SqoopJobSubmissionParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SubmitSqoopJobAsync (operations As IJobOperations, parameters As SqoopJobSubmissionParameters) As Task(Of JobSubmissionResponse)" />
      <MemberSignature Language="F#" Value="static member SubmitSqoopJobAsync : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * Microsoft.Azure.Management.HDInsight.Job.Models.SqoopJobSubmissionParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitSqoopJobAsync (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Job.Models.SqoopJobSubmissionParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fa172-267">Microsoft.Azure.Management.HDInsight.Job.IJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fa172-267">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fa172-268">必須。</span><span class="sxs-lookup"><span data-stu-id="fa172-268">Required.</span></span> <span data-ttu-id="fa172-269">Sqoop ジョブのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="fa172-269">Sqoop job parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fa172-270">HDInsight クラスターに Sqoop ジョブを送信します。</span><span class="sxs-lookup"><span data-stu-id="fa172-270">Submits a Sqoop job to an HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fa172-271">ジョブの作成操作の応答。</span><span class="sxs-lookup"><span data-stu-id="fa172-271">The Create Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WaitForJobCompletion">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse WaitForJobCompletion (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, string jobId, Nullable&lt;TimeSpan&gt; duration = null, Nullable&lt;TimeSpan&gt; waitInterval = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse WaitForJobCompletion(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, string jobId, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; duration, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; waitInterval) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.WaitForJobCompletion(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,System.String,System.Nullable{System.TimeSpan},System.Nullable{System.TimeSpan})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function WaitForJobCompletion (operations As IJobOperations, jobId As String, Optional duration As Nullable(Of TimeSpan) = null, Optional waitInterval As Nullable(Of TimeSpan) = null) As JobGetResponse" />
      <MemberSignature Language="F#" Value="static member WaitForJobCompletion : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * string * Nullable&lt;TimeSpan&gt; * Nullable&lt;TimeSpan&gt; -&gt; Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.WaitForJobCompletion (operations, jobId, duration, waitInterval)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="duration" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="waitInterval" Type="System.Nullable&lt;System.TimeSpan&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="jobId">
            <span data-ttu-id="fa172-272">必須。</span><span class="sxs-lookup"><span data-stu-id="fa172-272">Required.</span></span> <span data-ttu-id="fa172-273">ジョブの id。</span><span class="sxs-lookup"><span data-stu-id="fa172-273">The id of the job.</span></span>
            </param>
        <param name="duration">
            <span data-ttu-id="fa172-274">省略可能。</span><span class="sxs-lookup"><span data-stu-id="fa172-274">Optional.</span></span> <span data-ttu-id="fa172-275">クライアントに返す前にジョブの完了を待機する最大時間。</span><span class="sxs-lookup"><span data-stu-id="fa172-275">The maximum duration to wait for completion of job before returning to client.</span></span> <span data-ttu-id="fa172-276">ジョブが完了するまで待機が渡されません。 場合、</span><span class="sxs-lookup"><span data-stu-id="fa172-276">If not passed then wait till job is completed.</span></span>
            </param>
        <param name="waitInterval">
            <span data-ttu-id="fa172-277">省略可能。</span><span class="sxs-lookup"><span data-stu-id="fa172-277">Optional.</span></span> <span data-ttu-id="fa172-278">ジョブの状態をポーリングする間隔です。</span><span class="sxs-lookup"><span data-stu-id="fa172-278">The interval to poll for job status.</span></span> <span data-ttu-id="fa172-279">既定値は、HDInsight ジョブ管理クライアントの DefaultPollInterval プロパティから設定されます。</span><span class="sxs-lookup"><span data-stu-id="fa172-279">The default value is set from DefaultPollInterval property of HDInsight job management client.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fa172-280">ジョブの完了を待ちます。</span><span class="sxs-lookup"><span data-stu-id="fa172-280">Wait for completion of a Job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">
            <span data-ttu-id="fa172-281">ジョブの完了の待機期間のパラメーターで指定した最大期間を超えたときにスローされます。</span><span class="sxs-lookup"><span data-stu-id="fa172-281">Thrown when waiting for job completion exceeds the maximum duration specified by parameter duration.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="WaitForJobCompletionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse&gt; WaitForJobCompletionAsync (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, string jobId, Nullable&lt;TimeSpan&gt; duration = null, Nullable&lt;TimeSpan&gt; waitInterval = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse&gt; WaitForJobCompletionAsync(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, string jobId, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; duration, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; waitInterval) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.WaitForJobCompletionAsync(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,System.String,System.Nullable{System.TimeSpan},System.Nullable{System.TimeSpan})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function WaitForJobCompletionAsync (operations As IJobOperations, jobId As String, Optional duration As Nullable(Of TimeSpan) = null, Optional waitInterval As Nullable(Of TimeSpan) = null) As Task(Of JobGetResponse)" />
      <MemberSignature Language="F#" Value="static member WaitForJobCompletionAsync : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * string * Nullable&lt;TimeSpan&gt; * Nullable&lt;TimeSpan&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse&gt;" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.WaitForJobCompletionAsync (operations, jobId, duration, waitInterval)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="duration" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="waitInterval" Type="System.Nullable&lt;System.TimeSpan&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="jobId">
            <span data-ttu-id="fa172-282">必須。</span><span class="sxs-lookup"><span data-stu-id="fa172-282">Required.</span></span> <span data-ttu-id="fa172-283">ジョブの id。</span><span class="sxs-lookup"><span data-stu-id="fa172-283">The id of the job.</span></span>
            </param>
        <param name="duration">
            <span data-ttu-id="fa172-284">省略可能。</span><span class="sxs-lookup"><span data-stu-id="fa172-284">Optional.</span></span> <span data-ttu-id="fa172-285">クライアントに返す前にジョブの完了を待機する最大時間。</span><span class="sxs-lookup"><span data-stu-id="fa172-285">The maximum duration to wait for completion of job before returning to client.</span></span> <span data-ttu-id="fa172-286">ジョブが完了するまで待機が渡されません。 場合、</span><span class="sxs-lookup"><span data-stu-id="fa172-286">If not passed then wait till job is completed.</span></span>
            </param>
        <param name="waitInterval">
            <span data-ttu-id="fa172-287">省略可能。</span><span class="sxs-lookup"><span data-stu-id="fa172-287">Optional.</span></span> <span data-ttu-id="fa172-288">ジョブの状態をポーリングする間隔です。</span><span class="sxs-lookup"><span data-stu-id="fa172-288">The interval to poll for job status.</span></span> <span data-ttu-id="fa172-289">既定値は、HDInsight ジョブ管理クライアントの DefaultPollInterval プロパティから設定されます。</span><span class="sxs-lookup"><span data-stu-id="fa172-289">The default value is set from DefaultPollInterval property of HDInsight job management client.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fa172-290">ジョブの完了を待ちます。</span><span class="sxs-lookup"><span data-stu-id="fa172-290">Wait for completion of a Job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">
            <span data-ttu-id="fa172-291">ジョブの完了の待機期間のパラメーターで指定した最大期間を超えたときにスローされます。</span><span class="sxs-lookup"><span data-stu-id="fa172-291">Thrown when waiting for job completion exceeds the maximum duration specified by parameter duration.</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>