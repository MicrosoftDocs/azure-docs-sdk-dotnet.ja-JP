<Type Name="JobReleaseTask" FullName="Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask">
  <TypeSignature Language="C#" Value="public class JobReleaseTask" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobReleaseTask extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask" />
  <TypeSignature Language="VB.NET" Value="Public Class JobReleaseTask" />
  <TypeSignature Language="F#" Value="type JobReleaseTask = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2ed4c-101">ジョブのリリース タスクをジョブを実行した任意のコンピューティング ノードでジョブの完了時に実行します。</span><span class="sxs-lookup"><span data-stu-id="2ed4c-101">A Job Release task to run on job completion on any compute node where the job has run.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="2ed4c-102">ジョブのリリース タスクを実行、ジョブが終了すると、次のいずれかの理由: ユーザーを呼び出して終了ジョブ API、または削除ジョブ API ジョブがアクティブである、ジョブの最大のウォール クロック時間の制限に達すると、およびジョブがアクティブであるときに、または完了すると、ジョブのジョブ マネージャー タスクとジョブがジョブ マネージャーが完了したときに終了するように構成します。</span><span class="sxs-lookup"><span data-stu-id="2ed4c-102">The Job Release task runs when the job ends, because of one of the following: The user calls the Terminate Job API, or the Delete Job API while the job is still active, the job's maximum wall clock time constraint is reached, and the job is still active, or the job's Job Manager task completed, and the job is configured to terminate when the Job Manager completes.</span></span> <span data-ttu-id="2ed4c-103">ここで、ジョブのタスクが実行し、ジョブの準備タスクが実行され、完了した各コンピューティング ノードでジョブのリリース タスクが実行されます。</span><span class="sxs-lookup"><span data-stu-id="2ed4c-103">The Job Release task runs on each compute node where tasks of the job have run and the Job Preparation task ran and completed.</span></span> <span data-ttu-id="2ed4c-104">コンピューティング ノードをコンピューティング ノードが実行したジョブの準備タスクとジョブが、これ以上のタスクで実行されているジョブの終了後に再イメージ化する (そのため、ジョブの準備タスクが再実行されない) 場合、ジョブのリリース タスクが実行されないそのノード上。</span><span class="sxs-lookup"><span data-stu-id="2ed4c-104">If you reimage a compute node after it has run the Job Preparation task, and the job ends without any further tasks of the job running on that compute node (and hence the Job Preparation task does not re-run), then the Job Release task does not run on that node.</span></span> <span data-ttu-id="2ed4c-105">場合は、コンピューティング ノードを再起動すると、ジョブのリリース タスクが実行中でも、コンピューティング ノードの起動時には、ジョブのリリース タスクが再度実行されます。</span><span class="sxs-lookup"><span data-stu-id="2ed4c-105">If a compute node reboots while the Job Release task is still running, the Job Release task runs again when the compute node starts up.</span></span> <span data-ttu-id="2ed4c-106">すべてのジョブのリリース タスクが完了するまで、ジョブは完了済みとしてマークされません。</span><span class="sxs-lookup"><span data-stu-id="2ed4c-106">The job is not marked as complete until all Job Release tasks have completed.</span></span> <span data-ttu-id="2ed4c-107">ジョブのリリース タスクは、バック グラウンドで実行されます。</span><span class="sxs-lookup"><span data-stu-id="2ed4c-107">The Job Release task runs in the background.</span></span> <span data-ttu-id="2ed4c-108">スケジュールのスロットを占有しませんつまり、プールに指定された maxTasksPerNode 上限に達するまではカウントされません。</span><span class="sxs-lookup"><span data-stu-id="2ed4c-108">It does not occupy a scheduling slot; that is, it does not count towards the maxTasksPerNode limit specified on the pool.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobReleaseTask ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2ed4c-109">JobReleaseTask クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2ed4c-109">Initializes a new instance of the JobReleaseTask class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobReleaseTask (string commandLine, string id = null, Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings containerSettings = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; resourceFiles = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; environmentSettings = null, Nullable&lt;TimeSpan&gt; maxWallClockTime = null, Nullable&lt;TimeSpan&gt; retentionTime = null, Microsoft.Azure.Batch.Protocol.Models.UserIdentity userIdentity = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string commandLine, string id, class Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings containerSettings, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; resourceFiles, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; environmentSettings, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; maxWallClockTime, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; retentionTime, class Microsoft.Azure.Batch.Protocol.Models.UserIdentity userIdentity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.#ctor(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.ResourceFile},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting},System.Nullable{System.TimeSpan},System.Nullable{System.TimeSpan},Microsoft.Azure.Batch.Protocol.Models.UserIdentity)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask : string * string * Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; * Nullable&lt;TimeSpan&gt; * Nullable&lt;TimeSpan&gt; * Microsoft.Azure.Batch.Protocol.Models.UserIdentity -&gt; Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask" Usage="new Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask (commandLine, id, containerSettings, resourceFiles, environmentSettings, maxWallClockTime, retentionTime, userIdentity)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="commandLine" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="containerSettings" Type="Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings" />
        <Parameter Name="resourceFiles" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt;" />
        <Parameter Name="environmentSettings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt;" />
        <Parameter Name="maxWallClockTime" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="retentionTime" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="userIdentity" Type="Microsoft.Azure.Batch.Protocol.Models.UserIdentity" />
      </Parameters>
      <Docs>
        <param name="commandLine"><span data-ttu-id="2ed4c-110">ジョブのリリース タスクのコマンドラインです。</span><span class="sxs-lookup"><span data-stu-id="2ed4c-110">The command line of the Job Release task.</span></span></param>
        <param name="id"><span data-ttu-id="2ed4c-111">ジョブ内のジョブのリリース タスクを一意に識別する文字列。</span><span class="sxs-lookup"><span data-stu-id="2ed4c-111">A string that uniquely identifies the Job Release task within the job.</span></span></param>
        <param name="containerSettings"><span data-ttu-id="2ed4c-112">ジョブのリリース タスクを実行するコンテナーの設定。</span><span class="sxs-lookup"><span data-stu-id="2ed4c-112">The settings for the container under which the Job Release task runs.</span></span></param>
        <param name="resourceFiles"><span data-ttu-id="2ed4c-113">バッチ サービスはコマンドラインを実行する前にコンピューティング ノードにダウンロードされるファイルの一覧。</span><span class="sxs-lookup"><span data-stu-id="2ed4c-113">A list of files that the Batch service will download to the compute node before running the command line.</span></span></param>
        <param name="environmentSettings"><span data-ttu-id="2ed4c-114">ジョブのリリース タスクに対する環境変数設定の一覧。</span><span class="sxs-lookup"><span data-stu-id="2ed4c-114">A list of environment variable settings for the Job Release task.</span></span></param>
        <param name="maxWallClockTime"><span data-ttu-id="2ed4c-115">ジョブのリリース タスクがタスクを実行時点から計測されます、特定のコンピューティング ノードで最大経過時間を開始します。</span><span class="sxs-lookup"><span data-stu-id="2ed4c-115">The maximum elapsed time that the Job Release task may run on a given compute node, measured from the time the task starts.</span></span> <span data-ttu-id="2ed4c-116">制限時間内にタスクが完了しない場合、Batch service によって終了します。</span><span class="sxs-lookup"><span data-stu-id="2ed4c-116">If the task does not complete within the time limit, the Batch service terminates it.</span></span> <span data-ttu-id="2ed4c-117">既定値は、15 分です。</span><span class="sxs-lookup"><span data-stu-id="2ed4c-117">The default value is 15 minutes.</span></span> <span data-ttu-id="2ed4c-118">15 分より長いタイムアウトを指定することはできません。</span><span class="sxs-lookup"><span data-stu-id="2ed4c-118">You may not specify a timeout longer than 15 minutes.</span></span> <span data-ttu-id="2ed4c-119">場合は、バッチ サービス拒否が次のエラーです。REST API を直接呼び出すが、HTTP ステータス コードは 400 (Bad Request) がします。</span><span class="sxs-lookup"><span data-stu-id="2ed4c-119">If you do, the Batch service rejects it with an error; if you are calling the REST API directly, the HTTP status code is 400 (Bad Request).</span></span></param>
        <param name="retentionTime"><span data-ttu-id="2ed4c-120">コンピューティング ノードでジョブのリリース タスクの作業ディレクトリを保持する最小期間。</span><span class="sxs-lookup"><span data-stu-id="2ed4c-120">The minimum time to retain the task directory for the Job Release task on the compute node.</span></span> <span data-ttu-id="2ed4c-121">この時刻より後は、作業ディレクトリとその内容はすべて、バッチ サービスは削除できます。</span><span class="sxs-lookup"><span data-stu-id="2ed4c-121">After this time, the Batch service may delete the task directory and all its contents.</span></span></param>
        <param name="userIdentity"><span data-ttu-id="2ed4c-122">ジョブのリリース タスクを実行するユーザー id。</span><span class="sxs-lookup"><span data-stu-id="2ed4c-122">The user identity under which the Job Release task runs.</span></span></param>
        <summary>
            <span data-ttu-id="2ed4c-123">JobReleaseTask クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2ed4c-123">Initializes a new instance of the JobReleaseTask class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommandLine">
      <MemberSignature Language="C#" Value="public string CommandLine { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CommandLine" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.CommandLine" />
      <MemberSignature Language="VB.NET" Value="Public Property CommandLine As String" />
      <MemberSignature Language="F#" Value="member this.CommandLine : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.CommandLine" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="commandLine")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2ed4c-124">取得またはジョブのリリース タスクのコマンドラインを設定します。</span><span class="sxs-lookup"><span data-stu-id="2ed4c-124">Gets or sets the command line of the Job Release task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="2ed4c-125">コマンド ライン シェルが動作しないためできません利用して環境変数の展開などのシェルの機能の。</span><span class="sxs-lookup"><span data-stu-id="2ed4c-125">The command line does not run under a shell, and therefore cannot take advantage of shell features such as environment variable expansion.</span></span> <span data-ttu-id="2ed4c-126">このような機能を利用する場合を呼び出すように、コマンド ライン シェルたとえば"cmd/c MyCommand"を使用して windows または"/bin/sh-c MyCommand"Linux でします。</span><span class="sxs-lookup"><span data-stu-id="2ed4c-126">If you want to take advantage of such features, you should invoke the shell in the command line, for example using "cmd /c MyCommand" in Windows or "/bin/sh -c MyCommand" in Linux.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings ContainerSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings ContainerSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.ContainerSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerSettings As TaskContainerSettings" />
      <MemberSignature Language="F#" Value="member this.ContainerSettings : Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.ContainerSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="containerSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2ed4c-127">取得またはジョブのリリース タスクを実行するコンテナーの設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="2ed4c-127">Gets or sets the settings for the container under which the Job Release task runs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="2ed4c-128">これを指定すると、AZ_BATCH_NODE_ROOT_DIR (ノードの Azure Batch のディレクトリのルート) の下のすべてのディレクトリに再帰的には、コンテナーにマップされて、すべてのタスクの環境変数が、コンテナーにマップおよびタスクのコマンドラインは、コンテナーで実行されます。</span><span class="sxs-lookup"><span data-stu-id="2ed4c-128">When this is specified, all directories recursively below the AZ_BATCH_NODE_ROOT_DIR (the root of Azure Batch directories on the node) are mapped into the container, all task environment variables are mapped into the container, and the task command line is executed in the container.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnvironmentSettings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; EnvironmentSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; EnvironmentSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.EnvironmentSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property EnvironmentSettings As IList(Of EnvironmentSetting)" />
      <MemberSignature Language="F#" Value="member this.EnvironmentSettings : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.EnvironmentSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="environmentSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2ed4c-129">取得またはジョブのリリース タスクに対する環境変数設定の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="2ed4c-129">Gets or sets a list of environment variable settings for the Job Release task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2ed4c-130">取得または、ジョブ内のジョブのリリース タスクを一意に識別する文字列を設定します。</span><span class="sxs-lookup"><span data-stu-id="2ed4c-130">Gets or sets a string that uniquely identifies the Job Release task within the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="2ed4c-131">ID は、ハイフンとアンダー スコアを含む、英数字の任意の組み合わせを含めることができ、64 を超える文字を含めることはできません。</span><span class="sxs-lookup"><span data-stu-id="2ed4c-131">The ID can contain any combination of alphanumeric characters including hyphens and underscores and cannot contain more than 64 characters.</span></span> <span data-ttu-id="2ed4c-132">このプロパティを指定しない場合、Batch service は、'jobrelease' の既定値を割り当てます。</span><span class="sxs-lookup"><span data-stu-id="2ed4c-132">If you do not specify this property, the Batch service assigns a default value of 'jobrelease'.</span></span> <span data-ttu-id="2ed4c-133">ジョブ内の他のタスクがジョブのリリース タスクと同じ ID を持つことはできません。</span><span class="sxs-lookup"><span data-stu-id="2ed4c-133">No other task in the job can have the same ID as the Job Release task.</span></span> <span data-ttu-id="2ed4c-134">同じ id を持つタスクを送信しようとすると、バッチ サービスはエラー コード TaskIdSameAsJobReleaseTask; で要求を拒否します。REST API を直接呼び出すが、HTTP ステータス コードが 409 (Conflict です)。</span><span class="sxs-lookup"><span data-stu-id="2ed4c-134">If you try to submit a task with the same id, the Batch service rejects the request with error code TaskIdSameAsJobReleaseTask; if you are calling the REST API directly, the HTTP status code is 409 (Conflict).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxWallClockTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; MaxWallClockTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; MaxWallClockTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.MaxWallClockTime" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxWallClockTime As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.MaxWallClockTime : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.MaxWallClockTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxWallClockTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2ed4c-135">取得またはジョブのリリース タスクに、タスクの開始時点から計測されます、特定のコンピューティング ノードで実行できる最大経過時間を設定します。</span><span class="sxs-lookup"><span data-stu-id="2ed4c-135">Gets or sets the maximum elapsed time that the Job Release task may run on a given compute node, measured from the time the task starts.</span></span> <span data-ttu-id="2ed4c-136">制限時間内にタスクが完了しない場合、Batch service によって終了します。</span><span class="sxs-lookup"><span data-stu-id="2ed4c-136">If the task does not complete within the time limit, the Batch service terminates it.</span></span> <span data-ttu-id="2ed4c-137">既定値は、15 分です。</span><span class="sxs-lookup"><span data-stu-id="2ed4c-137">The default value is 15 minutes.</span></span> <span data-ttu-id="2ed4c-138">15 分より長いタイムアウトを指定することはできません。</span><span class="sxs-lookup"><span data-stu-id="2ed4c-138">You may not specify a timeout longer than 15 minutes.</span></span> <span data-ttu-id="2ed4c-139">場合は、バッチ サービス拒否が次のエラーです。REST API を直接呼び出すが、HTTP ステータス コードは 400 (Bad Request) がします。</span><span class="sxs-lookup"><span data-stu-id="2ed4c-139">If you do, the Batch service rejects it with an error; if you are calling the REST API directly, the HTTP status code is 400 (Bad Request).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceFiles">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; ResourceFiles { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; ResourceFiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.ResourceFiles" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceFiles As IList(Of ResourceFile)" />
      <MemberSignature Language="F#" Value="member this.ResourceFiles : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.ResourceFiles" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceFiles")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2ed4c-140">取得またはコマンドラインを実行する前に、バッチ サービスをコンピューティング ノードにダウンロードするファイルの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="2ed4c-140">Gets or sets a list of files that the Batch service will download to the compute node before running the command line.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="2ed4c-141">この要素の下にリストされたファイルは、タスクの作業ディレクトリにあります。</span><span class="sxs-lookup"><span data-stu-id="2ed4c-141">Files listed under this element are located in the task's working directory.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; RetentionTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; RetentionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.RetentionTime" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionTime As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.RetentionTime : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.RetentionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="retentionTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2ed4c-142">取得または計算ノードでジョブのリリース タスクの作業ディレクトリを保持する時間の最小値を設定します。</span><span class="sxs-lookup"><span data-stu-id="2ed4c-142">Gets or sets the minimum time to retain the task directory for the Job Release task on the compute node.</span></span> <span data-ttu-id="2ed4c-143">この時刻より後は、作業ディレクトリとその内容はすべて、バッチ サービスは削除できます。</span><span class="sxs-lookup"><span data-stu-id="2ed4c-143">After this time, the Batch service may delete the task directory and all its contents.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="2ed4c-144">既定値が有限、コンピューティング ノードが削除または再イメージ化されるまでに、作業ディレクトリを保持するなどです。</span><span class="sxs-lookup"><span data-stu-id="2ed4c-144">The default is infinite, i.e. the task directory will be retained until the compute node is removed or reimaged.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UserIdentity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.UserIdentity UserIdentity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.UserIdentity UserIdentity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.UserIdentity" />
      <MemberSignature Language="VB.NET" Value="Public Property UserIdentity As UserIdentity" />
      <MemberSignature Language="F#" Value="member this.UserIdentity : Microsoft.Azure.Batch.Protocol.Models.UserIdentity with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.UserIdentity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="userIdentity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.UserIdentity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2ed4c-145">取得またはジョブのリリース タスクを実行するユーザー id を設定します。</span><span class="sxs-lookup"><span data-stu-id="2ed4c-145">Gets or sets the user identity under which the Job Release task runs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="2ed4c-146">省略した場合、そのタスクは、タスクに一意の非管理者のユーザーとして実行されます。</span><span class="sxs-lookup"><span data-stu-id="2ed4c-146">If omitted, the task runs as a non-administrative user unique to the task.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="jobReleaseTask.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2ed4c-147">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="2ed4c-147">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="2ed4c-148">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="2ed4c-148">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>