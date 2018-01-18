<Type Name="JobsOperationsExtensions" FullName="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class JobsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit JobsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module JobsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type JobsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="150c1-101">JobsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="150c1-101">Extension methods for JobsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BatchAI.Models.Job BeginCreate (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName, Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BatchAI.Models.Job BeginCreate(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName, class Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.BeginCreate(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String,System.String,Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreate (operations As IJobsOperations, resourceGroupName As String, jobName As String, parameters As JobCreateParameters) As Job" />
      <MemberSignature Language="F#" Value="static member BeginCreate : Microsoft.Azure.Management.BatchAI.IJobsOperations * string * string * Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters -&gt; Microsoft.Azure.Management.BatchAI.Models.Job" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.BeginCreate (operations, resourceGroupName, jobName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.Job</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="150c1-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="150c1-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="150c1-103">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="150c1-103">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="150c1-104">指定されたリソース グループ内でジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="150c1-104">The name of the job within the specified resource group.</span></span> <span data-ttu-id="150c1-105">ジョブ名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="150c1-105">Job names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="150c1-106">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="150c1-106">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="150c1-107">ジョブの作成を提供するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="150c1-107">The parameters to provide for job creation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="150c1-108">クラスターで実行されるジョブを追加します。</span><span class="sxs-lookup"><span data-stu-id="150c1-108">Adds a Job that gets executed on a cluster.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt; BeginCreateAsync (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName, Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Job&gt; BeginCreateAsync(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName, class Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.BeginCreateAsync(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String,System.String,Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateAsync : Microsoft.Azure.Management.BatchAI.IJobsOperations * string * string * Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.BeginCreateAsync (operations, resourceGroupName, jobName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions/&lt;BeginCreateAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="150c1-109">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="150c1-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="150c1-110">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="150c1-110">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="150c1-111">指定されたリソース グループ内でジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="150c1-111">The name of the job within the specified resource group.</span></span> <span data-ttu-id="150c1-112">ジョブ名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="150c1-112">Job names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="150c1-113">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="150c1-113">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="150c1-114">ジョブの作成を提供するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="150c1-114">The parameters to provide for job creation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="150c1-115">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="150c1-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="150c1-116">クラスターで実行されるジョブを追加します。</span><span class="sxs-lookup"><span data-stu-id="150c1-116">Adds a Job that gets executed on a cluster.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.BeginDelete(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IJobsOperations, resourceGroupName As String, jobName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.BatchAI.IJobsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.BeginDelete (operations, resourceGroupName, jobName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="150c1-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="150c1-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="150c1-118">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="150c1-118">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="150c1-119">指定されたリソース グループ内でジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="150c1-119">The name of the job within the specified resource group.</span></span> <span data-ttu-id="150c1-120">ジョブ名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="150c1-120">Job names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="150c1-121">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="150c1-121">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <summary>
            <span data-ttu-id="150c1-122">指定されたバッチ AI ジョブを削除します。</span><span class="sxs-lookup"><span data-stu-id="150c1-122">Deletes the specified Batch AI job.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.BatchAI.IJobsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, jobName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="150c1-123">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="150c1-123">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="150c1-124">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="150c1-124">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="150c1-125">指定されたリソース グループ内でジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="150c1-125">The name of the job within the specified resource group.</span></span> <span data-ttu-id="150c1-126">ジョブ名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="150c1-126">Job names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="150c1-127">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="150c1-127">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="150c1-128">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="150c1-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="150c1-129">指定されたバッチ AI ジョブを削除します。</span><span class="sxs-lookup"><span data-stu-id="150c1-129">Deletes the specified Batch AI job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginTerminate">
      <MemberSignature Language="C#" Value="public static void BeginTerminate (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginTerminate(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.BeginTerminate(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginTerminate (operations As IJobsOperations, resourceGroupName As String, jobName As String)" />
      <MemberSignature Language="F#" Value="static member BeginTerminate : Microsoft.Azure.Management.BatchAI.IJobsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.BeginTerminate (operations, resourceGroupName, jobName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="150c1-130">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="150c1-130">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="150c1-131">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="150c1-131">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="150c1-132">指定されたリソース グループ内でジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="150c1-132">The name of the job within the specified resource group.</span></span> <span data-ttu-id="150c1-133">ジョブ名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="150c1-133">Job names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="150c1-134">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="150c1-134">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <summary>
            <span data-ttu-id="150c1-135">ジョブを終了します。</span><span class="sxs-lookup"><span data-stu-id="150c1-135">Terminates a job.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginTerminateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginTerminateAsync (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginTerminateAsync(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.BeginTerminateAsync(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginTerminateAsync : Microsoft.Azure.Management.BatchAI.IJobsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.BeginTerminateAsync (operations, resourceGroupName, jobName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions/&lt;BeginTerminateAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="150c1-136">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="150c1-136">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="150c1-137">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="150c1-137">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="150c1-138">指定されたリソース グループ内でジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="150c1-138">The name of the job within the specified resource group.</span></span> <span data-ttu-id="150c1-139">ジョブ名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="150c1-139">Job names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="150c1-140">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="150c1-140">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="150c1-141">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="150c1-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="150c1-142">ジョブを終了します。</span><span class="sxs-lookup"><span data-stu-id="150c1-142">Terminates a job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BatchAI.Models.Job Create (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName, Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BatchAI.Models.Job Create(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName, class Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.Create(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String,System.String,Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Create (operations As IJobsOperations, resourceGroupName As String, jobName As String, parameters As JobCreateParameters) As Job" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.BatchAI.IJobsOperations * string * string * Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters -&gt; Microsoft.Azure.Management.BatchAI.Models.Job" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.Create (operations, resourceGroupName, jobName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.Job</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="150c1-143">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="150c1-143">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="150c1-144">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="150c1-144">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="150c1-145">指定されたリソース グループ内でジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="150c1-145">The name of the job within the specified resource group.</span></span> <span data-ttu-id="150c1-146">ジョブ名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="150c1-146">Job names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="150c1-147">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="150c1-147">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="150c1-148">ジョブの作成を提供するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="150c1-148">The parameters to provide for job creation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="150c1-149">クラスターで実行されるジョブを追加します。</span><span class="sxs-lookup"><span data-stu-id="150c1-149">Adds a Job that gets executed on a cluster.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt; CreateAsync (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName, Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Job&gt; CreateAsync(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName, class Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.CreateAsync(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String,System.String,Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.BatchAI.IJobsOperations * string * string * Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.CreateAsync (operations, resourceGroupName, jobName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions/&lt;CreateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="150c1-150">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="150c1-150">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="150c1-151">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="150c1-151">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="150c1-152">指定されたリソース グループ内でジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="150c1-152">The name of the job within the specified resource group.</span></span> <span data-ttu-id="150c1-153">ジョブ名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="150c1-153">Job names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="150c1-154">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="150c1-154">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="150c1-155">ジョブの作成を提供するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="150c1-155">The parameters to provide for job creation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="150c1-156">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="150c1-156">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="150c1-157">クラスターで実行されるジョブを追加します。</span><span class="sxs-lookup"><span data-stu-id="150c1-157">Adds a Job that gets executed on a cluster.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.Delete(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IJobsOperations, resourceGroupName As String, jobName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.BatchAI.IJobsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.Delete (operations, resourceGroupName, jobName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="150c1-158">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="150c1-158">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="150c1-159">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="150c1-159">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="150c1-160">指定されたリソース グループ内でジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="150c1-160">The name of the job within the specified resource group.</span></span> <span data-ttu-id="150c1-161">ジョブ名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="150c1-161">Job names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="150c1-162">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="150c1-162">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <summary>
            <span data-ttu-id="150c1-163">指定されたバッチ AI ジョブを削除します。</span><span class="sxs-lookup"><span data-stu-id="150c1-163">Deletes the specified Batch AI job.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.BatchAI.IJobsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.DeleteAsync (operations, resourceGroupName, jobName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="150c1-164">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="150c1-164">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="150c1-165">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="150c1-165">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="150c1-166">指定されたリソース グループ内でジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="150c1-166">The name of the job within the specified resource group.</span></span> <span data-ttu-id="150c1-167">ジョブ名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="150c1-167">Job names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="150c1-168">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="150c1-168">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="150c1-169">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="150c1-169">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="150c1-170">指定されたバッチ AI ジョブを削除します。</span><span class="sxs-lookup"><span data-stu-id="150c1-170">Deletes the specified Batch AI job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BatchAI.Models.Job Get (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BatchAI.Models.Job Get(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.Get(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IJobsOperations, resourceGroupName As String, jobName As String) As Job" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.BatchAI.IJobsOperations * string * string -&gt; Microsoft.Azure.Management.BatchAI.Models.Job" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.Get (operations, resourceGroupName, jobName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.Job</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="150c1-171">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="150c1-171">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="150c1-172">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="150c1-172">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="150c1-173">指定されたリソース グループ内でジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="150c1-173">The name of the job within the specified resource group.</span></span> <span data-ttu-id="150c1-174">ジョブ名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="150c1-174">Job names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="150c1-175">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="150c1-175">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <summary>
            <span data-ttu-id="150c1-176">指定したバッチ AI ジョブに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="150c1-176">Gets information about the specified Batch AI job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt; GetAsync (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Job&gt; GetAsync(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.GetAsync(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.BatchAI.IJobsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.GetAsync (operations, resourceGroupName, jobName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="150c1-177">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="150c1-177">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="150c1-178">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="150c1-178">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="150c1-179">指定されたリソース グループ内でジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="150c1-179">The name of the job within the specified resource group.</span></span> <span data-ttu-id="150c1-180">ジョブ名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="150c1-180">Job names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="150c1-181">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="150c1-181">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="150c1-182">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="150c1-182">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="150c1-183">指定したバッチ AI ジョブに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="150c1-183">Gets information about the specified Batch AI job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt; List (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, Microsoft.Azure.Management.BatchAI.Models.JobsListOptions jobsListOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Job&gt; List(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, class Microsoft.Azure.Management.BatchAI.Models.JobsListOptions jobsListOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.List(Microsoft.Azure.Management.BatchAI.IJobsOperations,Microsoft.Azure.Management.BatchAI.Models.JobsListOptions)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.BatchAI.IJobsOperations * Microsoft.Azure.Management.BatchAI.Models.JobsListOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.List (operations, jobsListOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="jobsListOptions" Type="Microsoft.Azure.Management.BatchAI.Models.JobsListOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="150c1-184">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="150c1-184">The operations group for this extension method.</span></span>
            </param>
        <param name="jobsListOptions">
            <span data-ttu-id="150c1-185">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="150c1-185">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="150c1-186">サブスクリプションに関連付けられているジョブに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="150c1-186">Gets information about the jobs associated with the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt; ListAsync (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, Microsoft.Azure.Management.BatchAI.Models.JobsListOptions jobsListOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt; ListAsync(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, class Microsoft.Azure.Management.BatchAI.Models.JobsListOptions jobsListOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListAsync(Microsoft.Azure.Management.BatchAI.IJobsOperations,Microsoft.Azure.Management.BatchAI.Models.JobsListOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.BatchAI.IJobsOperations * Microsoft.Azure.Management.BatchAI.Models.JobsListOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt;" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListAsync (operations, jobsListOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions/&lt;ListAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="jobsListOptions" Type="Microsoft.Azure.Management.BatchAI.Models.JobsListOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="150c1-187">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="150c1-187">The operations group for this extension method.</span></span>
            </param>
        <param name="jobsListOptions">
            <span data-ttu-id="150c1-188">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="150c1-188">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="150c1-189">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="150c1-189">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="150c1-190">サブスクリプションに関連付けられているジョブに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="150c1-190">Gets information about the jobs associated with the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt; ListByResourceGroup (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, Microsoft.Azure.Management.BatchAI.Models.JobsListByResourceGroupOptions jobsListByResourceGroupOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Job&gt; ListByResourceGroup(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, class Microsoft.Azure.Management.BatchAI.Models.JobsListByResourceGroupOptions jobsListByResourceGroupOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String,Microsoft.Azure.Management.BatchAI.Models.JobsListByResourceGroupOptions)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.BatchAI.IJobsOperations * string * Microsoft.Azure.Management.BatchAI.Models.JobsListByResourceGroupOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListByResourceGroup (operations, resourceGroupName, jobsListByResourceGroupOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobsListByResourceGroupOptions" Type="Microsoft.Azure.Management.BatchAI.Models.JobsListByResourceGroupOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="150c1-191">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="150c1-191">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="150c1-192">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="150c1-192">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="jobsListByResourceGroupOptions">
            <span data-ttu-id="150c1-193">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="150c1-193">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="150c1-194">指定されたリソース グループ内で関連付けられているバッチ AI ジョブに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="150c1-194">Gets information about the Batch AI jobs associated within the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, Microsoft.Azure.Management.BatchAI.Models.JobsListByResourceGroupOptions jobsListByResourceGroupOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, class Microsoft.Azure.Management.BatchAI.Models.JobsListByResourceGroupOptions jobsListByResourceGroupOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String,Microsoft.Azure.Management.BatchAI.Models.JobsListByResourceGroupOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.BatchAI.IJobsOperations * string * Microsoft.Azure.Management.BatchAI.Models.JobsListByResourceGroupOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt;" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, jobsListByResourceGroupOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobsListByResourceGroupOptions" Type="Microsoft.Azure.Management.BatchAI.Models.JobsListByResourceGroupOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="150c1-195">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="150c1-195">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="150c1-196">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="150c1-196">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="jobsListByResourceGroupOptions">
            <span data-ttu-id="150c1-197">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="150c1-197">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="150c1-198">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="150c1-198">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="150c1-199">指定されたリソース グループ内で関連付けられているバッチ AI ジョブに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="150c1-199">Gets information about the Batch AI jobs associated within the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt; ListByResourceGroupNext (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Job&gt; ListByResourceGroupNext(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListByResourceGroupNext(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroupNext (operations As IJobsOperations, nextPageLink As String) As IPage(Of Job)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNext : Microsoft.Azure.Management.BatchAI.IJobsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListByResourceGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="150c1-200">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="150c1-200">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="150c1-201">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="150c1-201">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="150c1-202">指定されたリソース グループ内で関連付けられているバッチ AI ジョブに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="150c1-202">Gets information about the Batch AI jobs associated within the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.BatchAI.IJobsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt;" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="150c1-203">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="150c1-203">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="150c1-204">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="150c1-204">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="150c1-205">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="150c1-205">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="150c1-206">指定されたリソース グループ内で関連付けられているバッチ AI ジョブに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="150c1-206">Gets information about the Batch AI jobs associated within the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt; ListNext (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Job&gt; ListNext(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListNext(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IJobsOperations, nextPageLink As String) As IPage(Of Job)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.BatchAI.IJobsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="150c1-207">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="150c1-207">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="150c1-208">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="150c1-208">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="150c1-209">サブスクリプションに関連付けられているジョブに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="150c1-209">Gets information about the jobs associated with the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.BatchAI.IJobsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt;" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions/&lt;ListNextAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="150c1-210">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="150c1-210">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="150c1-211">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="150c1-211">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="150c1-212">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="150c1-212">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="150c1-213">サブスクリプションに関連付けられているジョブに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="150c1-213">Gets information about the jobs associated with the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListOutputFiles">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.File&gt; ListOutputFiles (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName, Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions jobsListOutputFilesOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.File&gt; ListOutputFiles(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName, class Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions jobsListOutputFilesOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListOutputFiles(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String,System.String,Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions)" />
      <MemberSignature Language="F#" Value="static member ListOutputFiles : Microsoft.Azure.Management.BatchAI.IJobsOperations * string * string * Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.File&gt;" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListOutputFiles (operations, resourceGroupName, jobName, jobsListOutputFilesOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.File&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="jobsListOutputFilesOptions" Type="Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="150c1-214">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="150c1-214">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="150c1-215">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="150c1-215">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="150c1-216">指定されたリソース グループ内でジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="150c1-216">The name of the job within the specified resource group.</span></span> <span data-ttu-id="150c1-217">ジョブ名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="150c1-217">Job names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="150c1-218">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="150c1-218">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="jobsListOutputFilesOptions">
            <span data-ttu-id="150c1-219">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="150c1-219">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="150c1-220">(場合にのみ、出力ディレクトリは、Azure のファイル共有または Azure ストレージ コンテナーには) は、指定された出力ディレクトリ内のすべてのファイルを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="150c1-220">List all files inside the given output directory (Only if the output directory is on Azure File Share or Azure Storage container).</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListOutputFilesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.File&gt;&gt; ListOutputFilesAsync (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName, Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions jobsListOutputFilesOptions, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.File&gt;&gt; ListOutputFilesAsync(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName, class Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions jobsListOutputFilesOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListOutputFilesAsync(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String,System.String,Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListOutputFilesAsync : Microsoft.Azure.Management.BatchAI.IJobsOperations * string * string * Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.File&gt;&gt;" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListOutputFilesAsync (operations, resourceGroupName, jobName, jobsListOutputFilesOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions/&lt;ListOutputFilesAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.File&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="jobsListOutputFilesOptions" Type="Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="150c1-221">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="150c1-221">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="150c1-222">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="150c1-222">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="150c1-223">指定されたリソース グループ内でジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="150c1-223">The name of the job within the specified resource group.</span></span> <span data-ttu-id="150c1-224">ジョブ名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="150c1-224">Job names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="150c1-225">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="150c1-225">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="jobsListOutputFilesOptions">
            <span data-ttu-id="150c1-226">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="150c1-226">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="150c1-227">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="150c1-227">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="150c1-228">(場合にのみ、出力ディレクトリは、Azure のファイル共有または Azure ストレージ コンテナーには) は、指定された出力ディレクトリ内のすべてのファイルを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="150c1-228">List all files inside the given output directory (Only if the output directory is on Azure File Share or Azure Storage container).</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListOutputFilesNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.File&gt; ListOutputFilesNext (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.File&gt; ListOutputFilesNext(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListOutputFilesNext(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListOutputFilesNext (operations As IJobsOperations, nextPageLink As String) As IPage(Of File)" />
      <MemberSignature Language="F#" Value="static member ListOutputFilesNext : Microsoft.Azure.Management.BatchAI.IJobsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.File&gt;" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListOutputFilesNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.File&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="150c1-229">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="150c1-229">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="150c1-230">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="150c1-230">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="150c1-231">(場合にのみ、出力ディレクトリは、Azure のファイル共有または Azure ストレージ コンテナーには) は、指定された出力ディレクトリ内のすべてのファイルを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="150c1-231">List all files inside the given output directory (Only if the output directory is on Azure File Share or Azure Storage container).</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListOutputFilesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.File&gt;&gt; ListOutputFilesNextAsync (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.File&gt;&gt; ListOutputFilesNextAsync(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListOutputFilesNextAsync(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListOutputFilesNextAsync : Microsoft.Azure.Management.BatchAI.IJobsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.File&gt;&gt;" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListOutputFilesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions/&lt;ListOutputFilesNextAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.File&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="150c1-232">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="150c1-232">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="150c1-233">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="150c1-233">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="150c1-234">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="150c1-234">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="150c1-235">(場合にのみ、出力ディレクトリは、Azure のファイル共有または Azure ストレージ コンテナーには) は、指定された出力ディレクトリ内のすべてのファイルを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="150c1-235">List all files inside the given output directory (Only if the output directory is on Azure File Share or Azure Storage container).</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRemoteLoginInformation">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt; ListRemoteLoginInformation (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt; ListRemoteLoginInformation(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListRemoteLoginInformation(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListRemoteLoginInformation (operations As IJobsOperations, resourceGroupName As String, jobName As String) As IPage(Of RemoteLoginInformation)" />
      <MemberSignature Language="F#" Value="static member ListRemoteLoginInformation : Microsoft.Azure.Management.BatchAI.IJobsOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListRemoteLoginInformation (operations, resourceGroupName, jobName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="150c1-236">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="150c1-236">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="150c1-237">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="150c1-237">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="150c1-238">指定されたリソース グループ内でジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="150c1-238">The name of the job within the specified resource group.</span></span> <span data-ttu-id="150c1-239">ジョブ名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="150c1-239">Job names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="150c1-240">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="150c1-240">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <summary>
            <span data-ttu-id="150c1-241">ジョブの実行に使用されるすべてのコンピューティング ノードの IP アドレスとポート情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="150c1-241">Gets the IP address and port information of all the compute nodes which are used for job execution.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRemoteLoginInformationAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;&gt; ListRemoteLoginInformationAsync (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;&gt; ListRemoteLoginInformationAsync(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListRemoteLoginInformationAsync(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListRemoteLoginInformationAsync : Microsoft.Azure.Management.BatchAI.IJobsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;&gt;" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListRemoteLoginInformationAsync (operations, resourceGroupName, jobName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions/&lt;ListRemoteLoginInformationAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="150c1-242">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="150c1-242">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="150c1-243">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="150c1-243">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="150c1-244">指定されたリソース グループ内でジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="150c1-244">The name of the job within the specified resource group.</span></span> <span data-ttu-id="150c1-245">ジョブ名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="150c1-245">Job names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="150c1-246">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="150c1-246">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="150c1-247">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="150c1-247">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="150c1-248">ジョブの実行に使用されるすべてのコンピューティング ノードの IP アドレスとポート情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="150c1-248">Gets the IP address and port information of all the compute nodes which are used for job execution.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRemoteLoginInformationNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt; ListRemoteLoginInformationNext (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt; ListRemoteLoginInformationNext(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListRemoteLoginInformationNext(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListRemoteLoginInformationNext (operations As IJobsOperations, nextPageLink As String) As IPage(Of RemoteLoginInformation)" />
      <MemberSignature Language="F#" Value="static member ListRemoteLoginInformationNext : Microsoft.Azure.Management.BatchAI.IJobsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListRemoteLoginInformationNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="150c1-249">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="150c1-249">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="150c1-250">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="150c1-250">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="150c1-251">ジョブの実行に使用されるすべてのコンピューティング ノードの IP アドレスとポート情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="150c1-251">Gets the IP address and port information of all the compute nodes which are used for job execution.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRemoteLoginInformationNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;&gt; ListRemoteLoginInformationNextAsync (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;&gt; ListRemoteLoginInformationNextAsync(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListRemoteLoginInformationNextAsync(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListRemoteLoginInformationNextAsync : Microsoft.Azure.Management.BatchAI.IJobsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;&gt;" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListRemoteLoginInformationNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions/&lt;ListRemoteLoginInformationNextAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="150c1-252">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="150c1-252">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="150c1-253">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="150c1-253">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="150c1-254">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="150c1-254">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="150c1-255">ジョブの実行に使用されるすべてのコンピューティング ノードの IP アドレスとポート情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="150c1-255">Gets the IP address and port information of all the compute nodes which are used for job execution.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Terminate">
      <MemberSignature Language="C#" Value="public static void Terminate (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Terminate(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.Terminate(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Terminate (operations As IJobsOperations, resourceGroupName As String, jobName As String)" />
      <MemberSignature Language="F#" Value="static member Terminate : Microsoft.Azure.Management.BatchAI.IJobsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.Terminate (operations, resourceGroupName, jobName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="150c1-256">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="150c1-256">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="150c1-257">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="150c1-257">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="150c1-258">指定されたリソース グループ内でジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="150c1-258">The name of the job within the specified resource group.</span></span> <span data-ttu-id="150c1-259">ジョブ名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="150c1-259">Job names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="150c1-260">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="150c1-260">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <summary>
            <span data-ttu-id="150c1-261">ジョブを終了します。</span><span class="sxs-lookup"><span data-stu-id="150c1-261">Terminates a job.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TerminateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task TerminateAsync (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task TerminateAsync(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.TerminateAsync(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member TerminateAsync : Microsoft.Azure.Management.BatchAI.IJobsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.TerminateAsync (operations, resourceGroupName, jobName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions/&lt;TerminateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="150c1-262">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="150c1-262">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="150c1-263">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="150c1-263">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="150c1-264">指定されたリソース グループ内でジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="150c1-264">The name of the job within the specified resource group.</span></span> <span data-ttu-id="150c1-265">ジョブ名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="150c1-265">Job names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="150c1-266">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="150c1-266">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="150c1-267">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="150c1-267">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="150c1-268">ジョブを終了します。</span><span class="sxs-lookup"><span data-stu-id="150c1-268">Terminates a job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>