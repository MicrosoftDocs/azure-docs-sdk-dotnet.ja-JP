<Type Name="JobPreparationTask" FullName="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask">
  <TypeSignature Language="C#" Value="public class JobPreparationTask" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobPreparationTask extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask" />
  <TypeSignature Language="VB.NET" Value="Public Class JobPreparationTask" />
  <TypeSignature Language="F#" Value="type JobPreparationTask = class" />
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
            <span data-ttu-id="08ce3-101">コンピューティング ノードのすべてのタスク上、特定のジョブの前に実行するジョブの準備タスク。</span><span class="sxs-lookup"><span data-stu-id="08ce3-101">A Job Preparation task to run before any tasks of the job on any given compute node.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="08ce3-102">ジョブのタスクを実行するコンピューティング ノードを準備するジョブの準備を行うこともできます。</span><span class="sxs-lookup"><span data-stu-id="08ce3-102">You can use Job Preparation to prepare a compute node to run tasks for the job.</span></span> <span data-ttu-id="08ce3-103">一般的に実行されるジョブの準備の活動が含まれます。 ジョブ内のすべてのタスクで使用される共通のリソース ファイルをダウンロードします。</span><span class="sxs-lookup"><span data-stu-id="08ce3-103">Activities commonly performed in Job Preparation include: Downloading common resource files used by all the tasks in the job.</span></span> <span data-ttu-id="08ce3-104">ジョブの準備タスクは、コンピューティング ノード上の共有場所にこれらの一般的なリソース ファイルをダウンロードできます。</span><span class="sxs-lookup"><span data-stu-id="08ce3-104">The Job Preparation task can download these common resource files to the shared location on the compute node.</span></span> <span data-ttu-id="08ce3-105">(AZ_BATCH_NODE_ROOT_DIR\shared)、またはそのジョブのすべてのタスクと通信できるように、コンピューティング ノード上でローカル サービスを開始します。</span><span class="sxs-lookup"><span data-stu-id="08ce3-105">(AZ_BATCH_NODE_ROOT_DIR\shared), or starting a local service on the compute node so that all tasks of that job can communicate with it.</span></span> <span data-ttu-id="08ce3-106">ジョブの準備タスク (つまり、その再試行回数は終了コード 0 で終了する前に枯渇) が失敗した場合のバッチのコンピューティング ノードで、このジョブのタスクは実行されません。</span><span class="sxs-lookup"><span data-stu-id="08ce3-106">If the Job Preparation task fails (that is, exhausts its retry count before exiting with exit code 0), Batch will not run tasks of this job on the compute node.</span></span> <span data-ttu-id="08ce3-107">ノードは、イメージが再作成されるまで、このジョブのタスクを実行する対象外です。</span><span class="sxs-lookup"><span data-stu-id="08ce3-107">The node remains ineligible to run tasks of this job until it is reimaged.</span></span> <span data-ttu-id="08ce3-108">ノードは、アクティブなままし、その他のジョブに使用できます。</span><span class="sxs-lookup"><span data-stu-id="08ce3-108">The node remains active and can be used for other jobs.</span></span> <span data-ttu-id="08ce3-109">ジョブの準備タスクは、同じコンピューティング ノード上で複数回を実行できます。</span><span class="sxs-lookup"><span data-stu-id="08ce3-109">The Job Preparation task can run multiple times on the same compute node.</span></span> <span data-ttu-id="08ce3-110">そのため、再実行を処理するジョブの準備タスクを記述する必要があります。</span><span class="sxs-lookup"><span data-stu-id="08ce3-110">Therefore, you should write the Job Preparation task to handle re-execution.</span></span> <span data-ttu-id="08ce3-111">コンピューティング ノードが再起動された場合、ジョブの準備タスクがもう一度ノードで実行 rerunOnNodeRebootAfterSuccess が true の場合、またはジョブの準備タスクが既に完了しなかった場合、ジョブの他のタスクをスケジュールする前にします。</span><span class="sxs-lookup"><span data-stu-id="08ce3-111">If the compute node is rebooted, the Job Preparation task is run again on the node before scheduling any other task of the job, if rerunOnNodeRebootAfterSuccess is true or if the Job Preparation task did not previously complete.</span></span> <span data-ttu-id="08ce3-112">コンピューティング ノードが再イメージ化されるジョブの準備タスクは、ジョブのいずれかのタスクをスケジュールする前にもう一度実行されます。</span><span class="sxs-lookup"><span data-stu-id="08ce3-112">If the compute node is reimaged, the Job Preparation task is run again before scheduling any task of the job.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobPreparationTask ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.#ctor" />
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
            <span data-ttu-id="08ce3-113">JobPreparationTask クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="08ce3-113">Initializes a new instance of the JobPreparationTask class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobPreparationTask (string commandLine, string id = null, Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings containerSettings = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; resourceFiles = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; environmentSettings = null, Microsoft.Azure.Batch.Protocol.Models.TaskConstraints constraints = null, Nullable&lt;bool&gt; waitForSuccess = null, Microsoft.Azure.Batch.Protocol.Models.UserIdentity userIdentity = null, Nullable&lt;bool&gt; rerunOnNodeRebootAfterSuccess = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string commandLine, string id, class Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings containerSettings, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; resourceFiles, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; environmentSettings, class Microsoft.Azure.Batch.Protocol.Models.TaskConstraints constraints, valuetype System.Nullable`1&lt;bool&gt; waitForSuccess, class Microsoft.Azure.Batch.Protocol.Models.UserIdentity userIdentity, valuetype System.Nullable`1&lt;bool&gt; rerunOnNodeRebootAfterSuccess) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.#ctor(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.ResourceFile},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting},Microsoft.Azure.Batch.Protocol.Models.TaskConstraints,System.Nullable{System.Boolean},Microsoft.Azure.Batch.Protocol.Models.UserIdentity,System.Nullable{System.Boolean})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask : string * string * Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; * Microsoft.Azure.Batch.Protocol.Models.TaskConstraints * Nullable&lt;bool&gt; * Microsoft.Azure.Batch.Protocol.Models.UserIdentity * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask" Usage="new Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask (commandLine, id, containerSettings, resourceFiles, environmentSettings, constraints, waitForSuccess, userIdentity, rerunOnNodeRebootAfterSuccess)" />
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
        <Parameter Name="constraints" Type="Microsoft.Azure.Batch.Protocol.Models.TaskConstraints" />
        <Parameter Name="waitForSuccess" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="userIdentity" Type="Microsoft.Azure.Batch.Protocol.Models.UserIdentity" />
        <Parameter Name="rerunOnNodeRebootAfterSuccess" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="commandLine"><span data-ttu-id="08ce3-114">ジョブの準備タスクのコマンドラインです。</span><span class="sxs-lookup"><span data-stu-id="08ce3-114">The command line of the Job Preparation task.</span></span></param>
        <param name="id"><span data-ttu-id="08ce3-115">ジョブ内のジョブの準備タスクを一意に識別する文字列。</span><span class="sxs-lookup"><span data-stu-id="08ce3-115">A string that uniquely identifies the Job Preparation task within the job.</span></span></param>
        <param name="containerSettings"><span data-ttu-id="08ce3-116">ジョブの準備タスクを実行するコンテナーの設定。</span><span class="sxs-lookup"><span data-stu-id="08ce3-116">The settings for the container under which the Job Preparation task runs.</span></span></param>
        <param name="resourceFiles"><span data-ttu-id="08ce3-117">バッチ サービスはコマンドラインを実行する前にコンピューティング ノードにダウンロードされるファイルの一覧。</span><span class="sxs-lookup"><span data-stu-id="08ce3-117">A list of files that the Batch service will download to the compute node before running the command line.</span></span></param>
        <param name="environmentSettings"><span data-ttu-id="08ce3-118">ジョブの準備タスクに対する環境変数設定の一覧。</span><span class="sxs-lookup"><span data-stu-id="08ce3-118">A list of environment variable settings for the Job Preparation task.</span></span></param>
        <param name="constraints"><span data-ttu-id="08ce3-119">ジョブの準備タスクに適用される制約します。</span><span class="sxs-lookup"><span data-stu-id="08ce3-119">Constraints that apply to the Job Preparation task.</span></span></param>
        <param name="waitForSuccess"><span data-ttu-id="08ce3-120">かどうか、バッチ サービスは、コンピューティング ノード上のジョブの他のタスクをスケジュールする前に正常に完了するジョブの準備タスクを待機する必要があります。</span><span class="sxs-lookup"><span data-stu-id="08ce3-120">Whether the Batch service should wait for the Job Preparation task to complete successfully before scheduling any other tasks of the job on the compute node.</span></span> <span data-ttu-id="08ce3-121">終了コード 0 で終了した場合、ジョブの準備タスクが正常に完了します。</span><span class="sxs-lookup"><span data-stu-id="08ce3-121">A Job Preparation task has completed successfully if it exits with exit code 0.</span></span></param>
        <param name="userIdentity"><span data-ttu-id="08ce3-122">ジョブの準備タスクを実行するユーザー id。</span><span class="sxs-lookup"><span data-stu-id="08ce3-122">The user identity under which the Job Preparation task runs.</span></span></param>
        <param name="rerunOnNodeRebootAfterSuccess"><span data-ttu-id="08ce3-123">かどうか、バッチ サービス再実行してください、ジョブの準備タスク コンピューティング ノードの後に再起動します。</span><span class="sxs-lookup"><span data-stu-id="08ce3-123">Whether the Batch service should rerun the Job Preparation task after a compute node reboots.</span></span></param>
        <summary>
            <span data-ttu-id="08ce3-124">JobPreparationTask クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="08ce3-124">Initializes a new instance of the JobPreparationTask class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommandLine">
      <MemberSignature Language="C#" Value="public string CommandLine { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CommandLine" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.CommandLine" />
      <MemberSignature Language="VB.NET" Value="Public Property CommandLine As String" />
      <MemberSignature Language="F#" Value="member this.CommandLine : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.CommandLine" />
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
            <span data-ttu-id="08ce3-125">取得またはジョブの準備タスクのコマンドラインを設定します。</span><span class="sxs-lookup"><span data-stu-id="08ce3-125">Gets or sets the command line of the Job Preparation task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="08ce3-126">コマンド ライン シェルが動作しないためできません利用して環境変数の展開などのシェルの機能の。</span><span class="sxs-lookup"><span data-stu-id="08ce3-126">The command line does not run under a shell, and therefore cannot take advantage of shell features such as environment variable expansion.</span></span> <span data-ttu-id="08ce3-127">このような機能を利用する場合を呼び出すように、コマンド ライン シェルたとえば"cmd/c MyCommand"を使用して windows または"/bin/sh-c MyCommand"Linux でします。</span><span class="sxs-lookup"><span data-stu-id="08ce3-127">If you want to take advantage of such features, you should invoke the shell in the command line, for example using "cmd /c MyCommand" in Windows or "/bin/sh -c MyCommand" in Linux.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Constraints">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskConstraints Constraints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskConstraints Constraints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.Constraints" />
      <MemberSignature Language="VB.NET" Value="Public Property Constraints As TaskConstraints" />
      <MemberSignature Language="F#" Value="member this.Constraints : Microsoft.Azure.Batch.Protocol.Models.TaskConstraints with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.Constraints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="constraints")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskConstraints</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="08ce3-128">取得またはジョブの準備タスクに適用される制約を設定します。</span><span class="sxs-lookup"><span data-stu-id="08ce3-128">Gets or sets constraints that apply to the Job Preparation task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings ContainerSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings ContainerSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.ContainerSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerSettings As TaskContainerSettings" />
      <MemberSignature Language="F#" Value="member this.ContainerSettings : Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.ContainerSettings" />
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
            <span data-ttu-id="08ce3-129">取得またはジョブの準備タスクを実行するコンテナーの設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="08ce3-129">Gets or sets the settings for the container under which the Job Preparation task runs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="08ce3-130">これを指定すると、AZ_BATCH_NODE_ROOT_DIR (ノードの Azure Batch のディレクトリのルート) の下のすべてのディレクトリに再帰的には、コンテナーにマップされて、すべてのタスクの環境変数が、コンテナーにマップおよびタスクのコマンドラインは、コンテナーで実行されます。</span><span class="sxs-lookup"><span data-stu-id="08ce3-130">When this is specified, all directories recursively below the AZ_BATCH_NODE_ROOT_DIR (the root of Azure Batch directories on the node) are mapped into the container, all task environment variables are mapped into the container, and the task command line is executed in the container.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnvironmentSettings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; EnvironmentSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; EnvironmentSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.EnvironmentSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property EnvironmentSettings As IList(Of EnvironmentSetting)" />
      <MemberSignature Language="F#" Value="member this.EnvironmentSettings : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.EnvironmentSettings" />
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
            <span data-ttu-id="08ce3-131">取得またはジョブの準備タスクに対する環境変数設定の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="08ce3-131">Gets or sets a list of environment variable settings for the Job Preparation task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.Id" />
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
            <span data-ttu-id="08ce3-132">取得または、ジョブ内のジョブの準備タスクを一意に識別する文字列を設定します。</span><span class="sxs-lookup"><span data-stu-id="08ce3-132">Gets or sets a string that uniquely identifies the Job Preparation task within the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="08ce3-133">ID は、ハイフンとアンダー スコアを含む、英数字の任意の組み合わせを含めることができ、64 を超える文字を含めることはできません。</span><span class="sxs-lookup"><span data-stu-id="08ce3-133">The ID can contain any combination of alphanumeric characters including hyphens and underscores and cannot contain more than 64 characters.</span></span> <span data-ttu-id="08ce3-134">このプロパティを指定しない場合、Batch service は、'jobpreparation' の既定値を割り当てます。</span><span class="sxs-lookup"><span data-stu-id="08ce3-134">If you do not specify this property, the Batch service assigns a default value of 'jobpreparation'.</span></span> <span data-ttu-id="08ce3-135">ジョブ内の他のタスクがジョブの準備タスクと同じ ID を持つことはできません。</span><span class="sxs-lookup"><span data-stu-id="08ce3-135">No other task in the job can have the same ID as the Job Preparation task.</span></span> <span data-ttu-id="08ce3-136">同じ id を持つタスクを送信しようとすると、バッチ サービスはエラー コード TaskIdSameAsJobPreparationTask; で要求を拒否します。REST API を直接呼び出すが、HTTP ステータス コードが 409 (Conflict です)。</span><span class="sxs-lookup"><span data-stu-id="08ce3-136">If you try to submit a task with the same id, the Batch service rejects the request with error code TaskIdSameAsJobPreparationTask; if you are calling the REST API directly, the HTTP status code is 409 (Conflict).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RerunOnNodeRebootAfterSuccess">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; RerunOnNodeRebootAfterSuccess { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; RerunOnNodeRebootAfterSuccess" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.RerunOnNodeRebootAfterSuccess" />
      <MemberSignature Language="VB.NET" Value="Public Property RerunOnNodeRebootAfterSuccess As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RerunOnNodeRebootAfterSuccess : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.RerunOnNodeRebootAfterSuccess" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="rerunOnNodeRebootAfterSuccess")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="08ce3-137">取得または Batch service コンピューティング ノードの再起動後に、ジョブの準備タスクを再実行するかどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="08ce3-137">Gets or sets whether the Batch service should rerun the Job Preparation task after a compute node reboots.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="08ce3-138">コンピューティング ノードが再イメージ化される場合、またはジョブの準備タスクが完了しなかった場合、ジョブの準備タスクが常に再実行 (例: タスクの実行中に再起動が発生したため)。</span><span class="sxs-lookup"><span data-stu-id="08ce3-138">The Job Preparation task is always rerun if a compute node is reimaged, or if the Job Preparation task did not complete (e.g. because the reboot occurred while the task was running).</span></span> <span data-ttu-id="08ce3-139">したがって、べき等になると、正常に動作する複数回実行した場合は、ジョブの準備タスクを作成する必要があります。</span><span class="sxs-lookup"><span data-stu-id="08ce3-139">Therefore, you should always write a Job Preparation task to be idempotent and to behave correctly if run multiple times.</span></span> <span data-ttu-id="08ce3-140">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="08ce3-140">The default value is true.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceFiles">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; ResourceFiles { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; ResourceFiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.ResourceFiles" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceFiles As IList(Of ResourceFile)" />
      <MemberSignature Language="F#" Value="member this.ResourceFiles : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.ResourceFiles" />
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
            <span data-ttu-id="08ce3-141">取得またはコマンドラインを実行する前に、バッチ サービスをコンピューティング ノードにダウンロードするファイルの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="08ce3-141">Gets or sets a list of files that the Batch service will download to the compute node before running the command line.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="08ce3-142">この要素の下にリストされたファイルは、タスクの作業ディレクトリにあります。</span><span class="sxs-lookup"><span data-stu-id="08ce3-142">Files listed under this element are located in the task's working directory.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UserIdentity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.UserIdentity UserIdentity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.UserIdentity UserIdentity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.UserIdentity" />
      <MemberSignature Language="VB.NET" Value="Public Property UserIdentity As UserIdentity" />
      <MemberSignature Language="F#" Value="member this.UserIdentity : Microsoft.Azure.Batch.Protocol.Models.UserIdentity with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.UserIdentity" />
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
            <span data-ttu-id="08ce3-143">取得またはジョブの準備タスクを実行するユーザー id を設定します。</span><span class="sxs-lookup"><span data-stu-id="08ce3-143">Gets or sets the user identity under which the Job Preparation task runs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="08ce3-144">省略した場合、タスクとして実行一意の非管理者のユーザーにタスク Windows ノードでは、または、Linux ノード上のプールに一意の非管理者のユーザーです。</span><span class="sxs-lookup"><span data-stu-id="08ce3-144">If omitted, the task runs as a non-administrative user unique to the task on Windows nodes, or a a non-administrative user unique to the pool on Linux nodes.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="jobPreparationTask.Validate " />
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
            <span data-ttu-id="08ce3-145">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="08ce3-145">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="08ce3-146">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="08ce3-146">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="WaitForSuccess">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; WaitForSuccess { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; WaitForSuccess" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.WaitForSuccess" />
      <MemberSignature Language="VB.NET" Value="Public Property WaitForSuccess As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.WaitForSuccess : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.WaitForSuccess" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="waitForSuccess")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="08ce3-147">取得またはバッチ サービスがコンピューティング ノード上のジョブの他のタスクをスケジュールする前に正常に完了するジョブの準備タスクを待機するかどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="08ce3-147">Gets or sets whether the Batch service should wait for the Job Preparation task to complete successfully before scheduling any other tasks of the job on the compute node.</span></span> <span data-ttu-id="08ce3-148">終了コード 0 で終了した場合、ジョブの準備タスクが正常に完了します。</span><span class="sxs-lookup"><span data-stu-id="08ce3-148">A Job Preparation task has completed successfully if it exits with exit code 0.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="08ce3-149">True で、ジョブの準備タスクは、コンピューティング ノードで失敗した場合、バッチ サービスは (制約要素で指定) と同じ場合は、その最大再試行回数までジョブの準備タスクを再試行します。</span><span class="sxs-lookup"><span data-stu-id="08ce3-149">If true and the Job Preparation task fails on a compute node, the Batch service retries the Job Preparation task up to its maximum retry count (as specified in the constraints element).</span></span> <span data-ttu-id="08ce3-150">タスクがまだ完了していない場合が正常にすべての再試行後に、バッチ サービスはコンピューティング ノードにジョブのタスクのスケジュールを設定できませんし、します。</span><span class="sxs-lookup"><span data-stu-id="08ce3-150">If the task has still not completed successfully after all retries, then the Batch service will not schedule tasks of the job to the compute node.</span></span> <span data-ttu-id="08ce3-151">コンピューティング ノードは、アクティブおよびその他のジョブのタスクを実行する対象となるは残ります。</span><span class="sxs-lookup"><span data-stu-id="08ce3-151">The compute node remains active and eligible to run tasks of other jobs.</span></span> <span data-ttu-id="08ce3-152">False の場合、バッチ サービスは、ジョブの準備タスクの完了を待機しません。</span><span class="sxs-lookup"><span data-stu-id="08ce3-152">If false, the Batch service will not wait for the Job Preparation task to complete.</span></span> <span data-ttu-id="08ce3-153">この例では、ジョブの他のタスクがジョブの準備タスクがまだ実行されているコンピューティング ノードで実行されているを開始することができます。コンティニュ ジョブの準備タスクが失敗した場合でも新しいタスクは、ノードにあるスケジュールします。</span><span class="sxs-lookup"><span data-stu-id="08ce3-153">In this case, other tasks of the job can start executing on the compute node while the Job Preparation task is still running; and even if the Job Preparation task fails, new tasks will continue to be scheduled on the node.</span></span> <span data-ttu-id="08ce3-154">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="08ce3-154">The default value is true.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>