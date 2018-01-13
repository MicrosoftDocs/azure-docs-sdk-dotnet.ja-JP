<Type Name="JobManagerTask" FullName="Microsoft.Azure.Batch.Protocol.Models.JobManagerTask">
  <TypeSignature Language="C#" Value="public class JobManagerTask" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobManagerTask extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.JobManagerTask" />
  <TypeSignature Language="VB.NET" Value="Public Class JobManagerTask" />
  <TypeSignature Language="F#" Value="type JobManagerTask = class" />
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
            <span data-ttu-id="c8a0f-101">ジョブ マネージャー タスクの詳細を指定します。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-101">Specifies details of a Job Manager task.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="c8a0f-102">ジョブ マネージャー タスクは、ジョブを作成するときに自動的に開始します。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-102">The Job Manager task is automatically started when the job is created.</span></span>
            <span data-ttu-id="c8a0f-103">バッチ サービスは、ジョブ内の他のタスクの前に、ジョブ マネージャー タスクのスケジュールを設定しようとします。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-103">The Batch service tries to schedule the Job Manager task before any other tasks in the job.</span></span> <span data-ttu-id="c8a0f-104">プールを圧縮するには、バッチ サービスはできるだけ長く ('normal' 実行中のタスクがジョブ マネージャー タスクを実行しているノードの前に削除されたノード) のジョブ マネージャー タスクが実行されているコンピューティング ノードを保持しようとします。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-104">When shrinking a pool, the Batch service tries to preserve compute nodes where Job Manager tasks are running for as long as possible (that is, nodes running 'normal' tasks are removed before nodes running Job Manager tasks).</span></span> <span data-ttu-id="c8a0f-105">ジョブ マネージャー タスクは失敗し、再起動する必要がある、ときに、システムは、最も優先度でスケジュールしようとします。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-105">When a Job Manager task fails and needs to be restarted, the system tries to schedule it at the highest priority.</span></span> <span data-ttu-id="c8a0f-106">アイドル状態のノードがない場合は、システム可能性があります、プールの実行中のタスクのいずれかの終了を再起動するジョブ マネージャー タスクのスペースを確保するためにキューに戻されます。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-106">If there are no idle nodes available, the system may terminate one of the running tasks in the pool and return it to the queue in order to make room for the Job Manager task to restart.</span></span> <span data-ttu-id="c8a0f-107">1 つのジョブのジョブ マネージャー タスクのタスクの他のジョブに、優先度がないことに注意してください。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-107">Note that a Job Manager task in one job does not have priority over tasks in other jobs.</span></span> <span data-ttu-id="c8a0f-108">ジョブ全体で、のみジョブ レベルの優先度が適用されます。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-108">Across jobs, only job level priorities are observed.</span></span> <span data-ttu-id="c8a0f-109">たとえば、優先度 0 ジョブでジョブ マネージャーを再起動する必要がある場合はいない置き換えること優先度 1 のジョブのタスクです。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-109">For example, if a Job Manager in a priority 0 job needs to be restarted, it will not displace tasks of a priority 1 job.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobManagerTask ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.#ctor" />
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
            <span data-ttu-id="c8a0f-110">JobManagerTask クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-110">Initializes a new instance of the JobManagerTask class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobManagerTask (string id, string commandLine, string displayName = null, Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings containerSettings = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; resourceFiles = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.OutputFile&gt; outputFiles = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; environmentSettings = null, Microsoft.Azure.Batch.Protocol.Models.TaskConstraints constraints = null, Nullable&lt;bool&gt; killJobOnCompletion = null, Microsoft.Azure.Batch.Protocol.Models.UserIdentity userIdentity = null, Nullable&lt;bool&gt; runExclusive = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; applicationPackageReferences = null, Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings authenticationTokenSettings = null, Nullable&lt;bool&gt; allowLowPriorityNode = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string commandLine, string displayName, class Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings containerSettings, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; resourceFiles, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.OutputFile&gt; outputFiles, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; environmentSettings, class Microsoft.Azure.Batch.Protocol.Models.TaskConstraints constraints, valuetype System.Nullable`1&lt;bool&gt; killJobOnCompletion, class Microsoft.Azure.Batch.Protocol.Models.UserIdentity userIdentity, valuetype System.Nullable`1&lt;bool&gt; runExclusive, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; applicationPackageReferences, class Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings authenticationTokenSettings, valuetype System.Nullable`1&lt;bool&gt; allowLowPriorityNode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.#ctor(System.String,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.ResourceFile},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.OutputFile},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting},Microsoft.Azure.Batch.Protocol.Models.TaskConstraints,System.Nullable{System.Boolean},Microsoft.Azure.Batch.Protocol.Models.UserIdentity,System.Nullable{System.Boolean},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference},Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings,System.Nullable{System.Boolean})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.JobManagerTask : string * string * string * Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.OutputFile&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; * Microsoft.Azure.Batch.Protocol.Models.TaskConstraints * Nullable&lt;bool&gt; * Microsoft.Azure.Batch.Protocol.Models.UserIdentity * Nullable&lt;bool&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; * Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.JobManagerTask" Usage="new Microsoft.Azure.Batch.Protocol.Models.JobManagerTask (id, commandLine, displayName, containerSettings, resourceFiles, outputFiles, environmentSettings, constraints, killJobOnCompletion, userIdentity, runExclusive, applicationPackageReferences, authenticationTokenSettings, allowLowPriorityNode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="commandLine" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="containerSettings" Type="Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings" />
        <Parameter Name="resourceFiles" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt;" />
        <Parameter Name="outputFiles" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.OutputFile&gt;" />
        <Parameter Name="environmentSettings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt;" />
        <Parameter Name="constraints" Type="Microsoft.Azure.Batch.Protocol.Models.TaskConstraints" />
        <Parameter Name="killJobOnCompletion" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="userIdentity" Type="Microsoft.Azure.Batch.Protocol.Models.UserIdentity" />
        <Parameter Name="runExclusive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="applicationPackageReferences" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt;" />
        <Parameter Name="authenticationTokenSettings" Type="Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings" />
        <Parameter Name="allowLowPriorityNode" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="c8a0f-111">ジョブ内のジョブ マネージャー タスクを一意に識別する文字列。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-111">A string that uniquely identifies the Job Manager task within the job.</span></span></param>
        <param name="commandLine"><span data-ttu-id="c8a0f-112">ジョブ マネージャー タスクのコマンドラインです。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-112">The command line of the Job Manager task.</span></span></param>
        <param name="displayName"><span data-ttu-id="c8a0f-113">ジョブ マネージャー タスクの表示名。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-113">The display name of the Job Manager task.</span></span></param>
        <param name="containerSettings"><span data-ttu-id="c8a0f-114">ジョブ マネージャー タスクを実行するコンテナーの設定。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-114">The settings for the container under which the Job Manager task runs.</span></span></param>
        <param name="resourceFiles"><span data-ttu-id="c8a0f-115">バッチ サービスはコマンドラインを実行する前にコンピューティング ノードにダウンロードされるファイルの一覧。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-115">A list of files that the Batch service will download to the compute node before running the command line.</span></span></param>
        <param name="outputFiles"><span data-ttu-id="c8a0f-116">バッチ サービスはコマンドラインの実行後にコンピューティング ノードからアップロードするファイルの一覧です。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-116">A list of files that the Batch service will upload from the compute node after running the command line.</span></span></param>
        <param name="environmentSettings"><span data-ttu-id="c8a0f-117">ジョブ マネージャー タスクの環境変数設定の一覧。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-117">A list of environment variable settings for the Job Manager task.</span></span></param>
        <param name="constraints"><span data-ttu-id="c8a0f-118">ジョブ マネージャー タスクに適用される制約します。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-118">Constraints that apply to the Job Manager task.</span></span></param>
        <param name="killJobOnCompletion"><span data-ttu-id="c8a0f-119">かどうか、ジョブ マネージャー タスクの完了は、全体のジョブの完了を示します。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-119">Whether completion of the Job Manager task signifies completion of the entire job.</span></span></param>
        <param name="userIdentity"><span data-ttu-id="c8a0f-120">ジョブ マネージャー タスクを実行するユーザー id。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-120">The user identity under which the Job Manager task runs.</span></span></param>
        <param name="runExclusive"><span data-ttu-id="c8a0f-121">かどうか、ジョブ マネージャー タスクには、それが実行されているコンピューティング ノードの排他的な使用が必要です。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-121">Whether the Job Manager task requires exclusive use of the compute node where it runs.</span></span></param>
        <param name="applicationPackageReferences"><span data-ttu-id="c8a0f-122">バッチ サービスは、コマンドラインを実行する前に、コンピューティング ノードに配置するアプリケーション パッケージの一覧。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-122">A list of application packages that the Batch service will deploy to the compute node before running the command line.</span></span></param>
        <param name="authenticationTokenSettings"><span data-ttu-id="c8a0f-123">バッチを実行するタスクを使用する認証トークンの設定は、操作を処理します。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-123">The settings for an authentication token that the task can use to perform Batch service operations.</span></span></param>
        <param name="allowLowPriorityNode"><span data-ttu-id="c8a0f-124">かどうか、ジョブ マネージャー タスクは、優先度の低いコンピューティング ノードで実行可能性があります。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-124">Whether the Job Manager task may run on a low-priority compute node.</span></span></param>
        <summary>
            <span data-ttu-id="c8a0f-125">JobManagerTask クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-125">Initializes a new instance of the JobManagerTask class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowLowPriorityNode">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; AllowLowPriorityNode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; AllowLowPriorityNode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.AllowLowPriorityNode" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowLowPriorityNode As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.AllowLowPriorityNode : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.AllowLowPriorityNode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="allowLowPriorityNode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c8a0f-126">取得または、ジョブ マネージャー タスクは、優先度の低いコンピューティング ノードで実行するかどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-126">Gets or sets whether the Job Manager task may run on a low-priority compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="c8a0f-127">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-127">The default value is false.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationPackageReferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; ApplicationPackageReferences { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; ApplicationPackageReferences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.ApplicationPackageReferences" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationPackageReferences As IList(Of ApplicationPackageReference)" />
      <MemberSignature Language="F#" Value="member this.ApplicationPackageReferences : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.ApplicationPackageReferences" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="applicationPackageReferences")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c8a0f-128">取得またはコマンドラインを実行する前に、コンピューティング ノードに、バッチ サービスを展開するアプリケーション パッケージの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-128">Gets or sets a list of application packages that the Batch service will deploy to the compute node before running the command line.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="c8a0f-129">アプリケーション パッケージがダウンロードされ、作業ディレクトリのタスクではない、共有ディレクトリに配置します。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-129">Application packages are downloaded and deployed to a shared directory, not the task working directory.</span></span> <span data-ttu-id="c8a0f-130">そのため、参照されているパッケージは既にコンピューティング ノードでありは最新の状態場合、し、これは再ダウンロードされません;コンピューティング ノードで、既存のコピーが使用されます。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-130">Therefore, if a referenced package is already on the compute node, and is up to date, then it is not re-downloaded; the existing copy on the compute node is used.</span></span> <span data-ttu-id="c8a0f-131">参照先のアプリケーション パッケージをインストールできない場合、例については、パッケージが削除されたか、ダウンロードが失敗したため、タスクが失敗したためです。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-131">If a referenced application package cannot be installed, for example because the package has been deleted or because download failed, the task fails.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationTokenSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings AuthenticationTokenSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings AuthenticationTokenSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.AuthenticationTokenSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationTokenSettings As AuthenticationTokenSettings" />
      <MemberSignature Language="F#" Value="member this.AuthenticationTokenSettings : Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.AuthenticationTokenSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="authenticationTokenSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c8a0f-132">取得またはバッチ サービス操作を実行するタスクが使用できる認証トークンの設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-132">Gets or sets the settings for an authentication token that the task can use to perform Batch service operations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="c8a0f-133">このプロパティが設定されている場合、バッチ サービスは、アカウント アクセス キーを必要とせず、Batch service 操作を認証するために使用する認証トークンを使用してタスクを提供します。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-133">If this property is set, the Batch service provides the task with an authentication token which can be used to authenticate Batch service operations without requiring an account access key.</span></span> <span data-ttu-id="c8a0f-134">トークンが AZ_BATCH_AUTHENTICATION_TOKEN 環境変数を介して提供されます。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-134">The token is provided via the AZ_BATCH_AUTHENTICATION_TOKEN environment variable.</span></span> <span data-ttu-id="c8a0f-135">トークンを使用して、タスクが実行できる操作は、設定によって決まります。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-135">The operations that the task can carry out using the token depend on the settings.</span></span> <span data-ttu-id="c8a0f-136">たとえば、タスクは、ジョブを他のタスクを追加するか、またはその他のタスクは、ジョブのジョブの状態を確認するために、ジョブのアクセス許可を要求できます。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-136">For example, a task can request job permissions in order to add other tasks to the job, or check the status of the job or of other tasks under the job.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CommandLine">
      <MemberSignature Language="C#" Value="public string CommandLine { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CommandLine" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.CommandLine" />
      <MemberSignature Language="VB.NET" Value="Public Property CommandLine As String" />
      <MemberSignature Language="F#" Value="member this.CommandLine : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.CommandLine" />
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
            <span data-ttu-id="c8a0f-137">取得または、ジョブ マネージャー タスクのコマンドラインを設定します。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-137">Gets or sets the command line of the Job Manager task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="c8a0f-138">コマンド ライン シェルが動作しないためできません利用して環境変数の展開などのシェルの機能の。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-138">The command line does not run under a shell, and therefore cannot take advantage of shell features such as environment variable expansion.</span></span> <span data-ttu-id="c8a0f-139">このような機能を利用する場合を呼び出すように、コマンド ライン シェルたとえば"cmd/c MyCommand"を使用して windows または"/bin/sh-c MyCommand"Linux でします。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-139">If you want to take advantage of such features, you should invoke the shell in the command line, for example using "cmd /c MyCommand" in Windows or "/bin/sh -c MyCommand" in Linux.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Constraints">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskConstraints Constraints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskConstraints Constraints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.Constraints" />
      <MemberSignature Language="VB.NET" Value="Public Property Constraints As TaskConstraints" />
      <MemberSignature Language="F#" Value="member this.Constraints : Microsoft.Azure.Batch.Protocol.Models.TaskConstraints with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.Constraints" />
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
            <span data-ttu-id="c8a0f-140">取得または、ジョブ マネージャー タスクに適用される制約を設定します。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-140">Gets or sets constraints that apply to the Job Manager task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings ContainerSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings ContainerSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.ContainerSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerSettings As TaskContainerSettings" />
      <MemberSignature Language="F#" Value="member this.ContainerSettings : Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.ContainerSettings" />
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
            <span data-ttu-id="c8a0f-141">取得または、ジョブ マネージャー タスクを実行するコンテナーの設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-141">Gets or sets the settings for the container under which the Job Manager task runs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="c8a0f-142">このタスクを実行している、プールに containerConfiguration 設定がある場合は、これはも設定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-142">If the pool that will run this task has containerConfiguration set, this must be set as well.</span></span> <span data-ttu-id="c8a0f-143">このタスクを実行している、プールには、設定 containerConfiguration が割り当てられていない、これを設定しないでください。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-143">If the pool that will run this task doesn't have containerConfiguration set, this must not be set.</span></span> <span data-ttu-id="c8a0f-144">これを指定すると、AZ_BATCH_NODE_ROOT_DIR (ノードの Azure Batch のディレクトリのルート) の下のすべてのディレクトリに再帰的には、コンテナーにマップされて、すべてのタスクの環境変数が、コンテナーにマップおよびタスクのコマンドラインは、コンテナーで実行されます。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-144">When this is specified, all directories recursively below the AZ_BATCH_NODE_ROOT_DIR (the root of Azure Batch directories on the node) are mapped into the container, all task environment variables are mapped into the container, and the task command line is executed in the container.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="displayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c8a0f-145">取得または、ジョブ マネージャー タスクの表示名を設定します。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-145">Gets or sets the display name of the Job Manager task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="c8a0f-146">一意でない必要があるし、最大で 1,024 の最大長の Unicode 文字を含めることができます。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-146">It need not be unique and can contain any Unicode characters up to a maximum length of 1024.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnvironmentSettings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; EnvironmentSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; EnvironmentSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.EnvironmentSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property EnvironmentSettings As IList(Of EnvironmentSetting)" />
      <MemberSignature Language="F#" Value="member this.EnvironmentSettings : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.EnvironmentSettings" />
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
            <span data-ttu-id="c8a0f-147">取得または、ジョブ マネージャー タスクの環境変数設定の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-147">Gets or sets a list of environment variable settings for the Job Manager task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.Id" />
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
            <span data-ttu-id="c8a0f-148">取得または、ジョブ内のジョブ マネージャー タスクを一意に識別する文字列を設定します。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-148">Gets or sets a string that uniquely identifies the Job Manager task within the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="c8a0f-149">ID は、ハイフンとアンダー スコアを含む、英数字の任意の組み合わせを含めることができ、64 を超える文字を含めることはできません。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-149">The ID can contain any combination of alphanumeric characters including hyphens and underscores and cannot contain more than 64 characters.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="KillJobOnCompletion">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; KillJobOnCompletion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; KillJobOnCompletion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.KillJobOnCompletion" />
      <MemberSignature Language="VB.NET" Value="Public Property KillJobOnCompletion As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.KillJobOnCompletion : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.KillJobOnCompletion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="killJobOnCompletion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c8a0f-150">取得または、ジョブ マネージャー タスクの完了がジョブ全体の完了を示すかどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-150">Gets or sets whether completion of the Job Manager task signifies completion of the entire job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="c8a0f-151">True の場合、ジョブ マネージャー タスクが完了すると、バッチ サービス マークとしてジョブを完了します。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-151">If true, when the Job Manager task completes, the Batch service marks the job as complete.</span></span> <span data-ttu-id="c8a0f-152">すべてのタスクがまだ (以外のジョブのリリース) には、この時点で実行している場合は、それらのタスクが終了します。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-152">If any tasks are still running at this time (other than Job Release), those tasks are terminated.</span></span> <span data-ttu-id="c8a0f-153">False の場合、ジョブ マネージャー タスクの完了には、ジョブの状態は変わりません。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-153">If false, the completion of the Job Manager task does not affect the job status.</span></span> <span data-ttu-id="c8a0f-154">ここでは、する必要があります onAllTasksComplete 属性を使用して、ジョブを終了するか、クライアントまたはユーザーのジョブを明示的に終了します。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-154">In this case, you should either use the onAllTasksComplete attribute to terminate the job, or have a client or user terminate the job explicitly.</span></span> <span data-ttu-id="c8a0f-155">この例は、ジョブ マネージャーが、一連のタスクを作成しますでそれらの実行でさらにロールし、使用しないかどうかです。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-155">An example of this is if the Job Manager creates a set of tasks but then takes no further role in their execution.</span></span> <span data-ttu-id="c8a0f-156">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-156">The default value is true.</span></span> <span data-ttu-id="c8a0f-157">コントロールのジョブの有効期間、およびジョブ マネージャー タスクを使用して、ジョブ (いない進行状況を監視) のタスクを作成するには、のみ onAllTasksComplete と onTaskFailure 属性を使用している場合は、killJobOnCompletion を false に設定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-157">If you are using the onAllTasksComplete and onTaskFailure attributes to control job lifetime, and using the Job Manager task only to create the tasks for the job (not to monitor progress), then it is important to set killJobOnCompletion to false.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OutputFiles">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.OutputFile&gt; OutputFiles { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.OutputFile&gt; OutputFiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.OutputFiles" />
      <MemberSignature Language="VB.NET" Value="Public Property OutputFiles As IList(Of OutputFile)" />
      <MemberSignature Language="F#" Value="member this.OutputFiles : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.OutputFile&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.OutputFiles" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="outputFiles")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.OutputFile&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c8a0f-158">取得または、Batch service は、コマンドラインの実行後にコンピューティング ノードからアップロードするファイルの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-158">Gets or sets a list of files that the Batch service will upload from the compute node after running the command line.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="c8a0f-159">複数インスタンスのタスク、主要なタスクを実行するコンピューティング ノードから、ファイルのみアップロードされます。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-159">For multi-instance tasks, the files will only be uploaded from the compute node on which the primary task is executed.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceFiles">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; ResourceFiles { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; ResourceFiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.ResourceFiles" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceFiles As IList(Of ResourceFile)" />
      <MemberSignature Language="F#" Value="member this.ResourceFiles : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.ResourceFiles" />
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
            <span data-ttu-id="c8a0f-160">取得またはコマンドラインを実行する前に、バッチ サービスをコンピューティング ノードにダウンロードするファイルの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-160">Gets or sets a list of files that the Batch service will download to the compute node before running the command line.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="c8a0f-161">この要素の下にリストされたファイルは、タスクの作業ディレクトリにあります。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-161">Files listed under this element are located in the task's working directory.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RunExclusive">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; RunExclusive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; RunExclusive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.RunExclusive" />
      <MemberSignature Language="VB.NET" Value="Public Property RunExclusive As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RunExclusive : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.RunExclusive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="runExclusive")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c8a0f-162">取得またはが実行されるジョブ マネージャー タスクが、コンピューティング ノードの排他的な使用を必要とするかどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-162">Gets or sets whether the Job Manager task requires exclusive use of the compute node where it runs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="c8a0f-163">True の場合、ジョブ マネージャーが実行されている限り、同じコンピューティング ノードでの他のタスクは実行されません。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-163">If true, no other tasks will run on the same compute node for as long as the Job Manager is running.</span></span> <span data-ttu-id="c8a0f-164">False の場合、他のタスクできますで同時に実行、ジョブ マネージャーでコンピューティング ノードです。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-164">If false, other tasks can run simultaneously with the Job Manager on a compute node.</span></span> <span data-ttu-id="c8a0f-165">ジョブ マネージャー タスクは、これは、関連するノードが複数の同時実行タスクを許可する場合のみ、ノードの同時実行タスクの制限に照らし合わせて通常カウントします。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-165">The Job Manager task counts normally against the node's concurrent task limit, so this is only relevant if the node allows multiple concurrent tasks.</span></span> <span data-ttu-id="c8a0f-166">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-166">The default value is true.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UserIdentity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.UserIdentity UserIdentity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.UserIdentity UserIdentity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.UserIdentity" />
      <MemberSignature Language="VB.NET" Value="Public Property UserIdentity As UserIdentity" />
      <MemberSignature Language="F#" Value="member this.UserIdentity : Microsoft.Azure.Batch.Protocol.Models.UserIdentity with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.UserIdentity" />
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
            <span data-ttu-id="c8a0f-167">取得または、ジョブ マネージャー タスクを実行するユーザー id を設定します。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-167">Gets or sets the user identity under which the Job Manager task runs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="c8a0f-168">省略した場合、そのタスクは、タスクに一意の非管理者のユーザーとして実行されます。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-168">If omitted, the task runs as a non-administrative user unique to the task.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="jobManagerTask.Validate " />
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
            <span data-ttu-id="c8a0f-169">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-169">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c8a0f-170">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c8a0f-170">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>