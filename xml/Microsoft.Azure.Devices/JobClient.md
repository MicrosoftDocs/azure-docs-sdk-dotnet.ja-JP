<Type Name="JobClient" FullName="Microsoft.Azure.Devices.JobClient">
  <TypeSignature Language="C#" Value="public abstract class JobClient : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit JobClient extends System.Object implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.JobClient" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class JobClient&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type JobClient = class&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="377a0-101">ジョブの管理</span><span class="sxs-lookup"><span data-stu-id="377a0-101">Job management</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected JobClient ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobClient.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelJobAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt; CancelJobAsync (string jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.JobResponse&gt; CancelJobAsync(string jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobClient.CancelJobAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CancelJobAsync (jobId As String) As Task(Of JobResponse)" />
      <MemberSignature Language="F#" Value="abstract member CancelJobAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt;" Usage="jobClient.CancelJobAsync jobId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="jobId"><span data-ttu-id="377a0-102">キャンセルするジョブの id</span><span class="sxs-lookup"><span data-stu-id="377a0-102">Id of the Job to cancel</span></span></param>
        <summary>
            <span data-ttu-id="377a0-103">指定した ID を使用してジョブを取り消します/削除</span><span class="sxs-lookup"><span data-stu-id="377a0-103">Cancels/Deletes the job with the specified ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelJobAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt; CancelJobAsync (string jobId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.JobResponse&gt; CancelJobAsync(string jobId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobClient.CancelJobAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CancelJobAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt;" Usage="jobClient.CancelJobAsync (jobId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId"><span data-ttu-id="377a0-104">キャンセルするジョブの id</span><span class="sxs-lookup"><span data-stu-id="377a0-104">Id of the job to cancel</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="377a0-105">タスクのキャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="377a0-105">Task cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="377a0-106">指定した ID を使用してジョブを取り消します/削除</span><span class="sxs-lookup"><span data-stu-id="377a0-106">Cancels/Deletes the job with the specified ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task CloseAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CloseAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobClient.CloseAsync" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CloseAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member CloseAsync : unit -&gt; System.Threading.Tasks.Task" Usage="jobClient.CloseAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="377a0-107">JobClient インスタンスを終了し、そのリソースを破棄します。</span><span class="sxs-lookup"><span data-stu-id="377a0-107">Closes the JobClient instance and disposes its resources.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Devices.JobClient CreateFromConnectionString (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Devices.JobClient CreateFromConnectionString(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobClient.CreateFromConnectionString(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String) As JobClient" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string -&gt; Microsoft.Azure.Devices.JobClient" Usage="Microsoft.Azure.Devices.JobClient.CreateFromConnectionString connectionString" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.JobClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString"> <span data-ttu-id="377a0-108">Iot Hub の接続文字列。</span><span class="sxs-lookup"><span data-stu-id="377a0-108">The Iot Hub connection string.</span></span></param>
        <summary>
            <span data-ttu-id="377a0-109">Iot ハブの接続文字列から、JobClient を作成します。</span><span class="sxs-lookup"><span data-stu-id="377a0-109">Creates a JobClient from the Iot Hub connection string.</span></span>
            </summary>
        <returns> <span data-ttu-id="377a0-110">JobClient インスタンス。</span><span class="sxs-lookup"><span data-stu-id="377a0-110">A JobClient instance.</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateQuery">
      <MemberSignature Language="C#" Value="public abstract Microsoft.Azure.Devices.IQuery CreateQuery ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Devices.IQuery CreateQuery() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobClient.CreateQuery" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CreateQuery () As IQuery" />
      <MemberSignature Language="F#" Value="abstract member CreateQuery : unit -&gt; Microsoft.Azure.Devices.IQuery" Usage="jobClient.CreateQuery " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.IQuery</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="377a0-111">どのジョブからすべてのジョブの種類と状態の応答が取得されますページによってページ IQuery を取得します。</span><span class="sxs-lookup"><span data-stu-id="377a0-111">Get IQuery through which job responses for all job types and statuses are retrieved page by page</span></span>
            </summary>
        <returns><span data-ttu-id="377a0-112">IQuery</span><span class="sxs-lookup"><span data-stu-id="377a0-112">IQuery</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateQuery">
      <MemberSignature Language="C#" Value="public abstract Microsoft.Azure.Devices.IQuery CreateQuery (Nullable&lt;int&gt; pageSize);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Devices.IQuery CreateQuery(valuetype System.Nullable`1&lt;int32&gt; pageSize) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobClient.CreateQuery(System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CreateQuery (pageSize As Nullable(Of Integer)) As IQuery" />
      <MemberSignature Language="F#" Value="abstract member CreateQuery : Nullable&lt;int&gt; -&gt; Microsoft.Azure.Devices.IQuery" Usage="jobClient.CreateQuery pageSize" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.IQuery</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="pageSize" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="pageSize"><span data-ttu-id="377a0-113">ジョブ応答をページの数</span><span class="sxs-lookup"><span data-stu-id="377a0-113">Number of job responses in a page</span></span></param>
        <summary>
            <span data-ttu-id="377a0-114">IQuery 使用されるジョブ応答がページによってページが取得され、ページ サイズを指定の取得します。</span><span class="sxs-lookup"><span data-stu-id="377a0-114">Get IQuery through which job responses are retrieved page by page and specify page size</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateQuery">
      <MemberSignature Language="C#" Value="public abstract Microsoft.Azure.Devices.IQuery CreateQuery (Nullable&lt;Microsoft.Azure.Devices.JobType&gt; jobType, Nullable&lt;Microsoft.Azure.Devices.JobStatus&gt; jobStatus);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Devices.IQuery CreateQuery(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Devices.JobType&gt; jobType, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Devices.JobStatus&gt; jobStatus) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobClient.CreateQuery(System.Nullable{Microsoft.Azure.Devices.JobType},System.Nullable{Microsoft.Azure.Devices.JobStatus})" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CreateQuery (jobType As Nullable(Of JobType), jobStatus As Nullable(Of JobStatus)) As IQuery" />
      <MemberSignature Language="F#" Value="abstract member CreateQuery : Nullable&lt;Microsoft.Azure.Devices.JobType&gt; * Nullable&lt;Microsoft.Azure.Devices.JobStatus&gt; -&gt; Microsoft.Azure.Devices.IQuery" Usage="jobClient.CreateQuery (jobType, jobStatus)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.IQuery</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobType" Type="System.Nullable&lt;Microsoft.Azure.Devices.JobType&gt;" />
        <Parameter Name="jobStatus" Type="System.Nullable&lt;Microsoft.Azure.Devices.JobStatus&gt;" />
      </Parameters>
      <Docs>
        <param name="jobType"><span data-ttu-id="377a0-115">クエリにジョブの種類。</span><span class="sxs-lookup"><span data-stu-id="377a0-115">The job type to query.</span></span> <span data-ttu-id="377a0-116">クエリを実行しない場合は null になります。</span><span class="sxs-lookup"><span data-stu-id="377a0-116">Could be null if not querying.</span></span></param>
        <param name="jobStatus"><span data-ttu-id="377a0-117">ジョブの状態をクエリします。</span><span class="sxs-lookup"><span data-stu-id="377a0-117">The job status to query.</span></span> <span data-ttu-id="377a0-118">クエリを実行しない場合は null になります。</span><span class="sxs-lookup"><span data-stu-id="377a0-118">Could be null if not querying.</span></span></param>
        <summary>
            <span data-ttu-id="377a0-119">取得するジョブを指定した jobType と jobStatus に対する応答が取得されますページによってページ IQuery</span><span class="sxs-lookup"><span data-stu-id="377a0-119">Get IQuery through which job responses for specified jobType and jobStatus are retrieved page by page</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateQuery">
      <MemberSignature Language="C#" Value="public abstract Microsoft.Azure.Devices.IQuery CreateQuery (Nullable&lt;Microsoft.Azure.Devices.JobType&gt; jobType, Nullable&lt;Microsoft.Azure.Devices.JobStatus&gt; jobStatus, Nullable&lt;int&gt; pageSize);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Devices.IQuery CreateQuery(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Devices.JobType&gt; jobType, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Devices.JobStatus&gt; jobStatus, valuetype System.Nullable`1&lt;int32&gt; pageSize) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobClient.CreateQuery(System.Nullable{Microsoft.Azure.Devices.JobType},System.Nullable{Microsoft.Azure.Devices.JobStatus},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CreateQuery (jobType As Nullable(Of JobType), jobStatus As Nullable(Of JobStatus), pageSize As Nullable(Of Integer)) As IQuery" />
      <MemberSignature Language="F#" Value="abstract member CreateQuery : Nullable&lt;Microsoft.Azure.Devices.JobType&gt; * Nullable&lt;Microsoft.Azure.Devices.JobStatus&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Devices.IQuery" Usage="jobClient.CreateQuery (jobType, jobStatus, pageSize)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.IQuery</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobType" Type="System.Nullable&lt;Microsoft.Azure.Devices.JobType&gt;" />
        <Parameter Name="jobStatus" Type="System.Nullable&lt;Microsoft.Azure.Devices.JobStatus&gt;" />
        <Parameter Name="pageSize" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="jobType"><span data-ttu-id="377a0-120">クエリにジョブの種類。</span><span class="sxs-lookup"><span data-stu-id="377a0-120">The job type to query.</span></span> <span data-ttu-id="377a0-121">クエリを実行しない場合は null になります。</span><span class="sxs-lookup"><span data-stu-id="377a0-121">Could be null if not querying.</span></span></param>
        <param name="jobStatus"><span data-ttu-id="377a0-122">ジョブの状態をクエリします。</span><span class="sxs-lookup"><span data-stu-id="377a0-122">The job status to query.</span></span> <span data-ttu-id="377a0-123">クエリを実行しない場合は null になります。</span><span class="sxs-lookup"><span data-stu-id="377a0-123">Could be null if not querying.</span></span></param>
        <param name="pageSize"><span data-ttu-id="377a0-124">ジョブ応答をページの数</span><span class="sxs-lookup"><span data-stu-id="377a0-124">Number of job responses in a page</span></span></param>
        <summary>
            <span data-ttu-id="377a0-125">JobType jobStatus ページ単位で取得し、ページ サイズを指定するジョブをへの応答が指定された IQuery を取得します。</span><span class="sxs-lookup"><span data-stu-id="377a0-125">Get IQuery through which job responses for specified jobType and jobStatus are retrieved page by page, and specify page size</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobClient.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="jobClient.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
        <inheritdoc />
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="protected virtual void Dispose (bool disposing);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void Dispose(bool disposing) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobClient.Dispose(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub Dispose (disposing As Boolean)" />
      <MemberSignature Language="F#" Value="abstract member Dispose : bool -&gt; unit&#xA;override this.Dispose : bool -&gt; unit" Usage="jobClient.Dispose disposing" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="disposing" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="disposing">
          <span data-ttu-id="377a0-126"><c>true</c>マネージ コードとアンマネージ リソースを解放するには<c>false</c>アンマネージ リソースだけを解放します。</span><span class="sxs-lookup"><span data-stu-id="377a0-126"><c>true</c> to release both managed and unmanaged resources; <c>false</c> to release only unmanaged resources.</span></span></param>
        <summary>
            <span data-ttu-id="377a0-127">リリースでは、アンマネージし、必要に応じてマネージ リソース。</span><span class="sxs-lookup"><span data-stu-id="377a0-127">Releases unmanaged and - optionally - managed resources.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetJobAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt; GetJobAsync (string jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.JobResponse&gt; GetJobAsync(string jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobClient.GetJobAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function GetJobAsync (jobId As String) As Task(Of JobResponse)" />
      <MemberSignature Language="F#" Value="abstract member GetJobAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt;" Usage="jobClient.GetJobAsync jobId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="jobId"><span data-ttu-id="377a0-128">取得するジョブの id</span><span class="sxs-lookup"><span data-stu-id="377a0-128">Id of the Job to retrieve</span></span></param>
        <summary>
            <span data-ttu-id="377a0-129">指定した ID を使用してジョブを取得します。</span><span class="sxs-lookup"><span data-stu-id="377a0-129">Gets the job with the specified ID.</span></span>
            </summary>
        <returns><span data-ttu-id="377a0-130">一致する JobResponse オブジェクト</span><span class="sxs-lookup"><span data-stu-id="377a0-130">The matching JobResponse object</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetJobAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt; GetJobAsync (string jobId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.JobResponse&gt; GetJobAsync(string jobId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobClient.GetJobAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetJobAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt;" Usage="jobClient.GetJobAsync (jobId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId"><span data-ttu-id="377a0-131">取得するジョブの id</span><span class="sxs-lookup"><span data-stu-id="377a0-131">Id of the job to retrieve</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="377a0-132">タスクのキャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="377a0-132">Task cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="377a0-133">指定した ID を使用してジョブを取得します。</span><span class="sxs-lookup"><span data-stu-id="377a0-133">Gets the job with the specified ID.</span></span>
            </summary>
        <returns><span data-ttu-id="377a0-134">一致する JobResponse オブジェクト</span><span class="sxs-lookup"><span data-stu-id="377a0-134">The matching JobResponse object</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task OpenAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task OpenAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobClient.OpenAsync" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function OpenAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member OpenAsync : unit -&gt; System.Threading.Tasks.Task" Usage="jobClient.OpenAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="377a0-135">JobClient インスタンスを明示的に開きます。</span><span class="sxs-lookup"><span data-stu-id="377a0-135">Explicitly open the JobClient instance.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduleDeviceMethodAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt; ScheduleDeviceMethodAsync (string jobId, string queryCondition, Microsoft.Azure.Devices.CloudToDeviceMethod cloudToDeviceMethod, DateTime startTimeUtc, long maxExecutionTimeInSeconds);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.JobResponse&gt; ScheduleDeviceMethodAsync(string jobId, string queryCondition, class Microsoft.Azure.Devices.CloudToDeviceMethod cloudToDeviceMethod, valuetype System.DateTime startTimeUtc, int64 maxExecutionTimeInSeconds) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobClient.ScheduleDeviceMethodAsync(System.String,System.String,Microsoft.Azure.Devices.CloudToDeviceMethod,System.DateTime,System.Int64)" />
      <MemberSignature Language="F#" Value="abstract member ScheduleDeviceMethodAsync : string * string * Microsoft.Azure.Devices.CloudToDeviceMethod * DateTime * int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt;" Usage="jobClient.ScheduleDeviceMethodAsync (jobId, queryCondition, cloudToDeviceMethod, startTimeUtc, maxExecutionTimeInSeconds)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="queryCondition" Type="System.String" />
        <Parameter Name="cloudToDeviceMethod" Type="Microsoft.Azure.Devices.CloudToDeviceMethod" />
        <Parameter Name="startTimeUtc" Type="System.DateTime" />
        <Parameter Name="maxExecutionTimeInSeconds" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="jobId"><span data-ttu-id="377a0-136">このジョブの一意のジョブ Id</span><span class="sxs-lookup"><span data-stu-id="377a0-136">Unique Job Id for this job</span></span></param>
        <param name="queryCondition"><span data-ttu-id="377a0-137">ジョブを実行するデバイスを評価する条件をクエリします。</span><span class="sxs-lookup"><span data-stu-id="377a0-137">Query condition to evaluate which devices to run the job on</span></span></param>
        <param name="cloudToDeviceMethod"><span data-ttu-id="377a0-138">メソッドの呼び出しのパラメーター</span><span class="sxs-lookup"><span data-stu-id="377a0-138">Method call parameters</span></span></param>
        <param name="startTimeUtc"><span data-ttu-id="377a0-139">ジョブを開始する Utc の日付時刻</span><span class="sxs-lookup"><span data-stu-id="377a0-139">Date time in Utc to start the job</span></span></param>
        <param name="maxExecutionTimeInSeconds"><span data-ttu-id="377a0-140">最大実行時間 (秒)、つまり、ttl 期間のジョブを実行できます。</span><span class="sxs-lookup"><span data-stu-id="377a0-140">Max execution time in seconds, i.e., ttl duration the job can run</span></span></param>
        <summary>
            <span data-ttu-id="377a0-141">1 つまたは複数のデバイスでデバイス メソッドを実行する新しいジョブを作成します。</span><span class="sxs-lookup"><span data-stu-id="377a0-141">Creates a new Job to run a device method on one or multiple devices</span></span>
            </summary>
        <returns><span data-ttu-id="377a0-142">JobResponse オブジェクト</span><span class="sxs-lookup"><span data-stu-id="377a0-142">A JobResponse object</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduleDeviceMethodAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt; ScheduleDeviceMethodAsync (string jobId, string queryCondition, Microsoft.Azure.Devices.CloudToDeviceMethod cloudToDeviceMethod, DateTime startTimeUtc, long maxExecutionTimeInSeconds, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.JobResponse&gt; ScheduleDeviceMethodAsync(string jobId, string queryCondition, class Microsoft.Azure.Devices.CloudToDeviceMethod cloudToDeviceMethod, valuetype System.DateTime startTimeUtc, int64 maxExecutionTimeInSeconds, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobClient.ScheduleDeviceMethodAsync(System.String,System.String,Microsoft.Azure.Devices.CloudToDeviceMethod,System.DateTime,System.Int64,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ScheduleDeviceMethodAsync : string * string * Microsoft.Azure.Devices.CloudToDeviceMethod * DateTime * int64 * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt;" Usage="jobClient.ScheduleDeviceMethodAsync (jobId, queryCondition, cloudToDeviceMethod, startTimeUtc, maxExecutionTimeInSeconds, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="queryCondition" Type="System.String" />
        <Parameter Name="cloudToDeviceMethod" Type="Microsoft.Azure.Devices.CloudToDeviceMethod" />
        <Parameter Name="startTimeUtc" Type="System.DateTime" />
        <Parameter Name="maxExecutionTimeInSeconds" Type="System.Int64" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId"><span data-ttu-id="377a0-143">このジョブの一意のジョブ Id</span><span class="sxs-lookup"><span data-stu-id="377a0-143">Unique Job Id for this job</span></span></param>
        <param name="queryCondition"><span data-ttu-id="377a0-144">ジョブを実行するデバイスを評価する条件をクエリします。</span><span class="sxs-lookup"><span data-stu-id="377a0-144">Query condition to evaluate which devices to run the job on</span></span></param>
        <param name="cloudToDeviceMethod"><span data-ttu-id="377a0-145">メソッドの呼び出しのパラメーター</span><span class="sxs-lookup"><span data-stu-id="377a0-145">Method call parameters</span></span></param>
        <param name="startTimeUtc"><span data-ttu-id="377a0-146">ジョブを開始する Utc の日付時刻</span><span class="sxs-lookup"><span data-stu-id="377a0-146">Date time in Utc to start the job</span></span></param>
        <param name="maxExecutionTimeInSeconds"><span data-ttu-id="377a0-147">最大実行時間 (秒)、つまり、ttl 期間のジョブを実行できます。</span><span class="sxs-lookup"><span data-stu-id="377a0-147">Max execution time in seconds, i.e., ttl duration the job can run</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="377a0-148">タスクのキャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="377a0-148">Task cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="377a0-149">1 つまたは複数のデバイスでデバイス メソッドを実行する新しいジョブを作成します。</span><span class="sxs-lookup"><span data-stu-id="377a0-149">Creates a new Job to run a device method on one or multiple devices</span></span>
            </summary>
        <returns><span data-ttu-id="377a0-150">JobResponse オブジェクト</span><span class="sxs-lookup"><span data-stu-id="377a0-150">A JobResponse object</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduleTwinUpdateAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt; ScheduleTwinUpdateAsync (string jobId, string queryCondition, Microsoft.Azure.Devices.Shared.Twin twin, DateTime startTimeUtc, long maxExecutionTimeInSeconds);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.JobResponse&gt; ScheduleTwinUpdateAsync(string jobId, string queryCondition, class Microsoft.Azure.Devices.Shared.Twin twin, valuetype System.DateTime startTimeUtc, int64 maxExecutionTimeInSeconds) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobClient.ScheduleTwinUpdateAsync(System.String,System.String,Microsoft.Azure.Devices.Shared.Twin,System.DateTime,System.Int64)" />
      <MemberSignature Language="F#" Value="abstract member ScheduleTwinUpdateAsync : string * string * Microsoft.Azure.Devices.Shared.Twin * DateTime * int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt;" Usage="jobClient.ScheduleTwinUpdateAsync (jobId, queryCondition, twin, startTimeUtc, maxExecutionTimeInSeconds)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="queryCondition" Type="System.String" />
        <Parameter Name="twin" Type="Microsoft.Azure.Devices.Shared.Twin" />
        <Parameter Name="startTimeUtc" Type="System.DateTime" />
        <Parameter Name="maxExecutionTimeInSeconds" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="jobId"><span data-ttu-id="377a0-151">このジョブの一意のジョブ Id</span><span class="sxs-lookup"><span data-stu-id="377a0-151">Unique Job Id for this job</span></span></param>
        <param name="queryCondition"><span data-ttu-id="377a0-152">ジョブを実行するデバイスを評価する条件をクエリします。</span><span class="sxs-lookup"><span data-stu-id="377a0-152">Query condition to evaluate which devices to run the job on</span></span></param>
        <param name="twin"><span data-ttu-id="377a0-153">対になったオブジェクトの更新を使用するには</span><span class="sxs-lookup"><span data-stu-id="377a0-153">Twin object to use for the update</span></span></param>
        <param name="startTimeUtc"><span data-ttu-id="377a0-154">ジョブを開始する Utc の日付時刻</span><span class="sxs-lookup"><span data-stu-id="377a0-154">Date time in Utc to start the job</span></span></param>
        <param name="maxExecutionTimeInSeconds"><span data-ttu-id="377a0-155">最大実行時間 (秒)、つまり、ttl 期間のジョブを実行できます。</span><span class="sxs-lookup"><span data-stu-id="377a0-155">Max execution time in seconds, i.e., ttl duration the job can run</span></span></param>
        <summary>
            <span data-ttu-id="377a0-156">対になったタグと 1 つまたは複数のデバイスで必要なプロパティを更新する、新しいジョブを作成します。</span><span class="sxs-lookup"><span data-stu-id="377a0-156">Creates a new Job to update twin tags and desired properties on one or multiple devices</span></span>
            </summary>
        <returns><span data-ttu-id="377a0-157">JobResponse オブジェクト</span><span class="sxs-lookup"><span data-stu-id="377a0-157">A JobResponse object</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduleTwinUpdateAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt; ScheduleTwinUpdateAsync (string jobId, string queryCondition, Microsoft.Azure.Devices.Shared.Twin twin, DateTime startTimeUtc, long maxExecutionTimeInSeconds, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.JobResponse&gt; ScheduleTwinUpdateAsync(string jobId, string queryCondition, class Microsoft.Azure.Devices.Shared.Twin twin, valuetype System.DateTime startTimeUtc, int64 maxExecutionTimeInSeconds, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobClient.ScheduleTwinUpdateAsync(System.String,System.String,Microsoft.Azure.Devices.Shared.Twin,System.DateTime,System.Int64,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ScheduleTwinUpdateAsync : string * string * Microsoft.Azure.Devices.Shared.Twin * DateTime * int64 * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt;" Usage="jobClient.ScheduleTwinUpdateAsync (jobId, queryCondition, twin, startTimeUtc, maxExecutionTimeInSeconds, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="queryCondition" Type="System.String" />
        <Parameter Name="twin" Type="Microsoft.Azure.Devices.Shared.Twin" />
        <Parameter Name="startTimeUtc" Type="System.DateTime" />
        <Parameter Name="maxExecutionTimeInSeconds" Type="System.Int64" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId"><span data-ttu-id="377a0-158">このジョブの一意のジョブ Id</span><span class="sxs-lookup"><span data-stu-id="377a0-158">Unique Job Id for this job</span></span></param>
        <param name="queryCondition"><span data-ttu-id="377a0-159">ジョブを実行するデバイスを評価する条件をクエリします。</span><span class="sxs-lookup"><span data-stu-id="377a0-159">Query condition to evaluate which devices to run the job on</span></span></param>
        <param name="twin"><span data-ttu-id="377a0-160">対になったオブジェクトの更新を使用するには</span><span class="sxs-lookup"><span data-stu-id="377a0-160">Twin object to use for the update</span></span></param>
        <param name="startTimeUtc"><span data-ttu-id="377a0-161">ジョブを開始する Utc の日付時刻</span><span class="sxs-lookup"><span data-stu-id="377a0-161">Date time in Utc to start the job</span></span></param>
        <param name="maxExecutionTimeInSeconds"><span data-ttu-id="377a0-162">最大実行時間 (秒)、つまり、ttl 期間のジョブを実行できます。</span><span class="sxs-lookup"><span data-stu-id="377a0-162">Max execution time in seconds, i.e., ttl duration the job can run</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="377a0-163">タスクのキャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="377a0-163">Task cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="377a0-164">対になったタグと 1 つまたは複数のデバイスで必要なプロパティを更新する、新しいジョブを作成します。</span><span class="sxs-lookup"><span data-stu-id="377a0-164">Creates a new Job to update twin tags and desired properties on one or multiple devices</span></span>
            </summary>
        <returns><span data-ttu-id="377a0-165">JobResponse オブジェクト</span><span class="sxs-lookup"><span data-stu-id="377a0-165">A JobResponse object</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>