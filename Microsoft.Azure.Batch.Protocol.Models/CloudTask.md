<Type Name="CloudTask" FullName="Microsoft.Azure.Batch.Protocol.Models.CloudTask">
  <TypeSignature Language="C#" Value="public class CloudTask" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CloudTask extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.CloudTask" />
  <TypeSignature Language="VB.NET" Value="Public Class CloudTask" />
  <TypeSignature Language="F#" Value="type CloudTask = class" />
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
            <span data-ttu-id="a2e06-101">Azure Batch のタスクの場合。</span><span class="sxs-lookup"><span data-stu-id="a2e06-101">An Azure Batch task.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudTask ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.CloudTask.#ctor" />
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
            <span data-ttu-id="a2e06-102">CloudTask クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a2e06-102">Initializes a new instance of the CloudTask class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudTask (string id = null, string displayName = null, string url = null, string eTag = null, Nullable&lt;DateTime&gt; lastModified = null, Nullable&lt;DateTime&gt; creationTime = null, Microsoft.Azure.Batch.Protocol.Models.ExitConditions exitConditions = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskState&gt; state = null, Nullable&lt;DateTime&gt; stateTransitionTime = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskState&gt; previousState = null, Nullable&lt;DateTime&gt; previousStateTransitionTime = null, string commandLine = null, Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings containerSettings = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; resourceFiles = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.OutputFile&gt; outputFiles = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; environmentSettings = null, Microsoft.Azure.Batch.Protocol.Models.AffinityInformation affinityInfo = null, Microsoft.Azure.Batch.Protocol.Models.TaskConstraints constraints = null, Microsoft.Azure.Batch.Protocol.Models.UserIdentity userIdentity = null, Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation executionInfo = null, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeInformation nodeInfo = null, Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings multiInstanceSettings = null, Microsoft.Azure.Batch.Protocol.Models.TaskStatistics stats = null, Microsoft.Azure.Batch.Protocol.Models.TaskDependencies dependsOn = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; applicationPackageReferences = null, Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings authenticationTokenSettings = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string displayName, string url, string eTag, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastModified, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; creationTime, class Microsoft.Azure.Batch.Protocol.Models.ExitConditions exitConditions, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.TaskState&gt; state, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; stateTransitionTime, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.TaskState&gt; previousState, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; previousStateTransitionTime, string commandLine, class Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings containerSettings, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; resourceFiles, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.OutputFile&gt; outputFiles, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; environmentSettings, class Microsoft.Azure.Batch.Protocol.Models.AffinityInformation affinityInfo, class Microsoft.Azure.Batch.Protocol.Models.TaskConstraints constraints, class Microsoft.Azure.Batch.Protocol.Models.UserIdentity userIdentity, class Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation executionInfo, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeInformation nodeInfo, class Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings multiInstanceSettings, class Microsoft.Azure.Batch.Protocol.Models.TaskStatistics stats, class Microsoft.Azure.Batch.Protocol.Models.TaskDependencies dependsOn, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; applicationPackageReferences, class Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings authenticationTokenSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.CloudTask.#ctor(System.String,System.String,System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},Microsoft.Azure.Batch.Protocol.Models.ExitConditions,System.Nullable{Microsoft.Azure.Batch.Protocol.Models.TaskState},System.Nullable{System.DateTime},System.Nullable{Microsoft.Azure.Batch.Protocol.Models.TaskState},System.Nullable{System.DateTime},System.String,Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.ResourceFile},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.OutputFile},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting},Microsoft.Azure.Batch.Protocol.Models.AffinityInformation,Microsoft.Azure.Batch.Protocol.Models.TaskConstraints,Microsoft.Azure.Batch.Protocol.Models.UserIdentity,Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeInformation,Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings,Microsoft.Azure.Batch.Protocol.Models.TaskStatistics,Microsoft.Azure.Batch.Protocol.Models.TaskDependencies,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference},Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.CloudTask : string * string * string * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Microsoft.Azure.Batch.Protocol.Models.ExitConditions * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskState&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskState&gt; * Nullable&lt;DateTime&gt; * string * Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.OutputFile&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; * Microsoft.Azure.Batch.Protocol.Models.AffinityInformation * Microsoft.Azure.Batch.Protocol.Models.TaskConstraints * Microsoft.Azure.Batch.Protocol.Models.UserIdentity * Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeInformation * Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings * Microsoft.Azure.Batch.Protocol.Models.TaskStatistics * Microsoft.Azure.Batch.Protocol.Models.TaskDependencies * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; * Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings -&gt; Microsoft.Azure.Batch.Protocol.Models.CloudTask" Usage="new Microsoft.Azure.Batch.Protocol.Models.CloudTask (id, displayName, url, eTag, lastModified, creationTime, exitConditions, state, stateTransitionTime, previousState, previousStateTransitionTime, commandLine, containerSettings, resourceFiles, outputFiles, environmentSettings, affinityInfo, constraints, userIdentity, executionInfo, nodeInfo, multiInstanceSettings, stats, dependsOn, applicationPackageReferences, authenticationTokenSettings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="url" Type="System.String" />
        <Parameter Name="eTag" Type="System.String" />
        <Parameter Name="lastModified" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="creationTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="exitConditions" Type="Microsoft.Azure.Batch.Protocol.Models.ExitConditions" />
        <Parameter Name="state" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskState&gt;" />
        <Parameter Name="stateTransitionTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="previousState" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskState&gt;" />
        <Parameter Name="previousStateTransitionTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="commandLine" Type="System.String" />
        <Parameter Name="containerSettings" Type="Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings" />
        <Parameter Name="resourceFiles" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt;" />
        <Parameter Name="outputFiles" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.OutputFile&gt;" />
        <Parameter Name="environmentSettings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt;" />
        <Parameter Name="affinityInfo" Type="Microsoft.Azure.Batch.Protocol.Models.AffinityInformation" />
        <Parameter Name="constraints" Type="Microsoft.Azure.Batch.Protocol.Models.TaskConstraints" />
        <Parameter Name="userIdentity" Type="Microsoft.Azure.Batch.Protocol.Models.UserIdentity" />
        <Parameter Name="executionInfo" Type="Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation" />
        <Parameter Name="nodeInfo" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeInformation" />
        <Parameter Name="multiInstanceSettings" Type="Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings" />
        <Parameter Name="stats" Type="Microsoft.Azure.Batch.Protocol.Models.TaskStatistics" />
        <Parameter Name="dependsOn" Type="Microsoft.Azure.Batch.Protocol.Models.TaskDependencies" />
        <Parameter Name="applicationPackageReferences" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt;" />
        <Parameter Name="authenticationTokenSettings" Type="Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="a2e06-103">ジョブ内のタスクを一意に識別する文字列。</span><span class="sxs-lookup"><span data-stu-id="a2e06-103">A string that uniquely identifies the task within the job.</span></span></param>
        <param name="displayName"><span data-ttu-id="a2e06-104">タスクの表示名。</span><span class="sxs-lookup"><span data-stu-id="a2e06-104">A display name for the task.</span></span></param>
        <param name="url"><span data-ttu-id="a2e06-105">タスクの URL です。</span><span class="sxs-lookup"><span data-stu-id="a2e06-105">The URL of the task.</span></span></param>
        <param name="eTag"><span data-ttu-id="a2e06-106">タスクの ETag です。</span><span class="sxs-lookup"><span data-stu-id="a2e06-106">The ETag of the task.</span></span></param>
        <param name="lastModified"><span data-ttu-id="a2e06-107">最終は、タスクの時間を更新します。</span><span class="sxs-lookup"><span data-stu-id="a2e06-107">The last modified time of the task.</span></span></param>
        <param name="creationTime"><span data-ttu-id="a2e06-108">タスクの作成時間。</span><span class="sxs-lookup"><span data-stu-id="a2e06-108">The creation time of the task.</span></span></param>
        <param name="exitConditions"><span data-ttu-id="a2e06-109">バッチ サービスの応答方法、タスクが完了したときにします。</span><span class="sxs-lookup"><span data-stu-id="a2e06-109">How the Batch service should respond when the task completes.</span></span></param>
        <param name="state"><span data-ttu-id="a2e06-110">タスクの現在の状態。</span><span class="sxs-lookup"><span data-stu-id="a2e06-110">The current state of the task.</span></span></param>
        <param name="stateTransitionTime"><span data-ttu-id="a2e06-111">タスクが、現在の状態を入力する時刻。</span><span class="sxs-lookup"><span data-stu-id="a2e06-111">The time at which the task entered its current state.</span></span></param>
        <param name="previousState"><span data-ttu-id="a2e06-112">タスクの以前の状態。</span><span class="sxs-lookup"><span data-stu-id="a2e06-112">The previous state of the task.</span></span></param>
        <param name="previousStateTransitionTime"><span data-ttu-id="a2e06-113">その前の状態、タスクになった時刻。</span><span class="sxs-lookup"><span data-stu-id="a2e06-113">The time at which the task entered its previous state.</span></span></param>
        <param name="commandLine"><span data-ttu-id="a2e06-114">タスクのコマンドラインです。</span><span class="sxs-lookup"><span data-stu-id="a2e06-114">The command line of the task.</span></span></param>
        <param name="containerSettings"><span data-ttu-id="a2e06-115">タスクを実行するコンテナーの設定。</span><span class="sxs-lookup"><span data-stu-id="a2e06-115">The settings for the container under which the task runs.</span></span></param>
        <param name="resourceFiles"><span data-ttu-id="a2e06-116">バッチ サービスはコマンドラインを実行する前にコンピューティング ノードにダウンロードされるファイルの一覧。</span><span class="sxs-lookup"><span data-stu-id="a2e06-116">A list of files that the Batch service will download to the compute node before running the command line.</span></span></param>
        <param name="outputFiles"><span data-ttu-id="a2e06-117">バッチ サービスはコマンドラインの実行後にコンピューティング ノードからアップロードするファイルの一覧です。</span><span class="sxs-lookup"><span data-stu-id="a2e06-117">A list of files that the Batch service will upload from the compute node after running the command line.</span></span></param>
        <param name="environmentSettings"><span data-ttu-id="a2e06-118">タスクの環境変数設定の一覧。</span><span class="sxs-lookup"><span data-stu-id="a2e06-118">A list of environment variable settings for the task.</span></span></param>
        <param name="affinityInfo"><span data-ttu-id="a2e06-119">新しいタスクを開始するコンピューティング ノードを選択する、Batch service によって使用できる局所性のヒント。</span><span class="sxs-lookup"><span data-stu-id="a2e06-119">A locality hint that can be used by the Batch service to select a compute node on which to start the new task.</span></span></param>
        <param name="constraints"><span data-ttu-id="a2e06-120">このタスクに適用される実行の制約。</span><span class="sxs-lookup"><span data-stu-id="a2e06-120">The execution constraints that apply to this task.</span></span></param>
        <param name="userIdentity"><span data-ttu-id="a2e06-121">タスクを実行するユーザー id。</span><span class="sxs-lookup"><span data-stu-id="a2e06-121">The user identity under which the task runs.</span></span></param>
        <param name="executionInfo"><span data-ttu-id="a2e06-122">タスクの実行に関する情報です。</span><span class="sxs-lookup"><span data-stu-id="a2e06-122">Information about the execution of the task.</span></span></param>
        <param name="nodeInfo"><span data-ttu-id="a2e06-123">タスクが実行された計算ノードに関する情報です。</span><span class="sxs-lookup"><span data-stu-id="a2e06-123">Information about the compute node on which the task ran.</span></span></param>
        <param name="multiInstanceSettings"><span data-ttu-id="a2e06-124">タスクが複数のインスタンス、タスクは、複数インスタンスのタスクを実行する方法に関する情報を格納であることを示すオブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="a2e06-124">An object that indicates that the task is a multi-instance task, and contains information about how to run the multi-instance task.</span></span></param>
        <param name="stats"><span data-ttu-id="a2e06-125">タスクのリソース使用状況の統計。</span><span class="sxs-lookup"><span data-stu-id="a2e06-125">Resource usage statistics for the task.</span></span></param>
        <param name="dependsOn"><span data-ttu-id="a2e06-126">このタスクは、このタスクに依存します。</span><span class="sxs-lookup"><span data-stu-id="a2e06-126">The tasks that this task depends on.</span></span></param>
        <param name="applicationPackageReferences"><span data-ttu-id="a2e06-127">バッチ サービスは、コマンドラインを実行する前に、コンピューティング ノードに配置するアプリケーション パッケージの一覧。</span><span class="sxs-lookup"><span data-stu-id="a2e06-127">A list of application packages that the Batch service will deploy to the compute node before running the command line.</span></span></param>
        <param name="authenticationTokenSettings"><span data-ttu-id="a2e06-128">バッチを実行するタスクを使用する認証トークンの設定は、操作を処理します。</span><span class="sxs-lookup"><span data-stu-id="a2e06-128">The settings for an authentication token that the task can use to perform Batch service operations.</span></span></param>
        <summary>
            <span data-ttu-id="a2e06-129">CloudTask クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a2e06-129">Initializes a new instance of the CloudTask class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AffinityInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.AffinityInformation AffinityInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.AffinityInformation AffinityInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudTask.AffinityInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property AffinityInfo As AffinityInformation" />
      <MemberSignature Language="F#" Value="member this.AffinityInfo : Microsoft.Azure.Batch.Protocol.Models.AffinityInformation with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudTask.AffinityInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="affinityInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.AffinityInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a2e06-130">取得または新しいタスクを開始するコンピューティング ノードを選択する、Batch service によって使用できる局所性のヒントを設定します。</span><span class="sxs-lookup"><span data-stu-id="a2e06-130">Gets or sets a locality hint that can be used by the Batch service to select a compute node on which to start the new task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationPackageReferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; ApplicationPackageReferences { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; ApplicationPackageReferences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudTask.ApplicationPackageReferences" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationPackageReferences As IList(Of ApplicationPackageReference)" />
      <MemberSignature Language="F#" Value="member this.ApplicationPackageReferences : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudTask.ApplicationPackageReferences" />
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
            <span data-ttu-id="a2e06-131">取得またはコマンドラインを実行する前に、コンピューティング ノードに、バッチ サービスを展開するアプリケーション パッケージの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="a2e06-131">Gets or sets a list of application packages that the Batch service will deploy to the compute node before running the command line.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="a2e06-132">アプリケーション パッケージがダウンロードされ、作業ディレクトリのタスクではない、共有ディレクトリに配置します。</span><span class="sxs-lookup"><span data-stu-id="a2e06-132">Application packages are downloaded and deployed to a shared directory, not the task working directory.</span></span> <span data-ttu-id="a2e06-133">そのため、参照されているパッケージは既にコンピューティング ノードでありは最新の状態場合、し、これは再ダウンロードされません;コンピューティング ノードで、既存のコピーが使用されます。</span><span class="sxs-lookup"><span data-stu-id="a2e06-133">Therefore, if a referenced package is already on the compute node, and is up to date, then it is not re-downloaded; the existing copy on the compute node is used.</span></span> <span data-ttu-id="a2e06-134">参照先のアプリケーション パッケージをインストールできない場合、例については、パッケージが削除されたか、ダウンロードが失敗したため、タスクが失敗したためです。</span><span class="sxs-lookup"><span data-stu-id="a2e06-134">If a referenced application package cannot be installed, for example because the package has been deleted or because download failed, the task fails.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationTokenSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings AuthenticationTokenSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings AuthenticationTokenSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudTask.AuthenticationTokenSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationTokenSettings As AuthenticationTokenSettings" />
      <MemberSignature Language="F#" Value="member this.AuthenticationTokenSettings : Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudTask.AuthenticationTokenSettings" />
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
            <span data-ttu-id="a2e06-135">取得またはバッチ サービス操作を実行するタスクが使用できる認証トークンの設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="a2e06-135">Gets or sets the settings for an authentication token that the task can use to perform Batch service operations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="a2e06-136">このプロパティが設定されている場合、バッチ サービスは、アカウント アクセス キーを必要とせず、Batch service 操作を認証するために使用する認証トークンを使用してタスクを提供します。</span><span class="sxs-lookup"><span data-stu-id="a2e06-136">If this property is set, the Batch service provides the task with an authentication token which can be used to authenticate Batch service operations without requiring an account access key.</span></span> <span data-ttu-id="a2e06-137">トークンが AZ_BATCH_AUTHENTICATION_TOKEN 環境変数を介して提供されます。</span><span class="sxs-lookup"><span data-stu-id="a2e06-137">The token is provided via the AZ_BATCH_AUTHENTICATION_TOKEN environment variable.</span></span> <span data-ttu-id="a2e06-138">トークンを使用して、タスクが実行できる操作は、設定によって決まります。</span><span class="sxs-lookup"><span data-stu-id="a2e06-138">The operations that the task can carry out using the token depend on the settings.</span></span> <span data-ttu-id="a2e06-139">たとえば、タスクは、ジョブを他のタスクを追加するか、またはその他のタスクは、ジョブのジョブの状態を確認するために、ジョブのアクセス許可を要求できます。</span><span class="sxs-lookup"><span data-stu-id="a2e06-139">For example, a task can request job permissions in order to add other tasks to the job, or check the status of the job or of other tasks under the job.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CommandLine">
      <MemberSignature Language="C#" Value="public string CommandLine { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CommandLine" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudTask.CommandLine" />
      <MemberSignature Language="VB.NET" Value="Public Property CommandLine As String" />
      <MemberSignature Language="F#" Value="member this.CommandLine : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudTask.CommandLine" />
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
            <span data-ttu-id="a2e06-140">取得またはタスクのコマンドラインを設定します。</span><span class="sxs-lookup"><span data-stu-id="a2e06-140">Gets or sets the command line of the task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="a2e06-141">マルチ インスタンスのタスクの主要なタスクとサブタスクをすべての調整のコマンドラインの実行が完了した後、コマンドラインは、主要なタスクとして実行されます。</span><span class="sxs-lookup"><span data-stu-id="a2e06-141">For multi-instance tasks, the command line is executed as the primary task, after the primary task and all subtasks have finished executing the coordination command line.</span></span> <span data-ttu-id="a2e06-142">コマンド ライン シェルが動作しないためできません利用して環境変数の展開などのシェルの機能の。</span><span class="sxs-lookup"><span data-stu-id="a2e06-142">The command line does not run under a shell, and therefore cannot take advantage of shell features such as environment variable expansion.</span></span> <span data-ttu-id="a2e06-143">このような機能を利用する場合を呼び出すように、コマンド ライン シェルたとえば"cmd/c MyCommand"を使用して windows または"/bin/sh-c MyCommand"Linux でします。</span><span class="sxs-lookup"><span data-stu-id="a2e06-143">If you want to take advantage of such features, you should invoke the shell in the command line, for example using "cmd /c MyCommand" in Windows or "/bin/sh -c MyCommand" in Linux.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Constraints">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskConstraints Constraints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskConstraints Constraints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudTask.Constraints" />
      <MemberSignature Language="VB.NET" Value="Public Property Constraints As TaskConstraints" />
      <MemberSignature Language="F#" Value="member this.Constraints : Microsoft.Azure.Batch.Protocol.Models.TaskConstraints with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudTask.Constraints" />
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
            <span data-ttu-id="a2e06-144">取得または、このタスクに適用される実行制約を設定します。</span><span class="sxs-lookup"><span data-stu-id="a2e06-144">Gets or sets the execution constraints that apply to this task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings ContainerSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings ContainerSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudTask.ContainerSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerSettings As TaskContainerSettings" />
      <MemberSignature Language="F#" Value="member this.ContainerSettings : Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudTask.ContainerSettings" />
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
            <span data-ttu-id="a2e06-145">取得またはタスクを実行するコンテナーの設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="a2e06-145">Gets or sets the settings for the container under which the task runs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="a2e06-146">このタスクを実行している、プールに containerConfiguration 設定がある場合は、これはも設定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="a2e06-146">If the pool that will run this task has containerConfiguration set, this must be set as well.</span></span> <span data-ttu-id="a2e06-147">このタスクを実行している、プールには、設定 containerConfiguration が割り当てられていない、これを設定しないでください。</span><span class="sxs-lookup"><span data-stu-id="a2e06-147">If the pool that will run this task doesn't have containerConfiguration set, this must not be set.</span></span> <span data-ttu-id="a2e06-148">これを指定すると、AZ_BATCH_NODE_ROOT_DIR (ノードの Azure Batch のディレクトリのルート) の下のすべてのディレクトリに再帰的には、コンテナーにマップされて、すべてのタスクの環境変数が、コンテナーにマップおよびタスクのコマンドラインは、コンテナーで実行されます。</span><span class="sxs-lookup"><span data-stu-id="a2e06-148">When this is specified, all directories recursively below the AZ_BATCH_NODE_ROOT_DIR (the root of Azure Batch directories on the node) are mapped into the container, all task environment variables are mapped into the container, and the task command line is executed in the container.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreationTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudTask.CreationTime" />
      <MemberSignature Language="VB.NET" Value="Public Property CreationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreationTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudTask.CreationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="creationTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a2e06-149">取得またはタスクの作成時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="a2e06-149">Gets or sets the creation time of the task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DependsOn">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskDependencies DependsOn { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskDependencies DependsOn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudTask.DependsOn" />
      <MemberSignature Language="VB.NET" Value="Public Property DependsOn As TaskDependencies" />
      <MemberSignature Language="F#" Value="member this.DependsOn : Microsoft.Azure.Batch.Protocol.Models.TaskDependencies with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudTask.DependsOn" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dependsOn")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskDependencies</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a2e06-150">取得または、このタスクが依存しているタスクを設定します。</span><span class="sxs-lookup"><span data-stu-id="a2e06-150">Gets or sets the tasks that this task depends on.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="a2e06-151">依存しているすべてのタスクが正常に完了するまで、このタスクはスケジュールされません。</span><span class="sxs-lookup"><span data-stu-id="a2e06-151">This task will not be scheduled until all tasks that it depends on have completed successfully.</span></span> <span data-ttu-id="a2e06-152">失敗の再試行カウントを使い果たすそれらのタスクのいずれかの場合は、このタスクがスケジュールされることはありません。</span><span class="sxs-lookup"><span data-stu-id="a2e06-152">If any of those tasks fail and exhaust their retry counts, this task will never be scheduled.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudTask.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudTask.DisplayName" />
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
            <span data-ttu-id="a2e06-153">取得またはタスクの表示名を設定します。</span><span class="sxs-lookup"><span data-stu-id="a2e06-153">Gets or sets a display name for the task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="a2e06-154">表示名は一意でない必要があり、最大で 1,024 の最大長の Unicode 文字を含めることができます。</span><span class="sxs-lookup"><span data-stu-id="a2e06-154">The display name need not be unique and can contain any Unicode characters up to a maximum length of 1024.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnvironmentSettings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; EnvironmentSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; EnvironmentSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudTask.EnvironmentSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property EnvironmentSettings As IList(Of EnvironmentSetting)" />
      <MemberSignature Language="F#" Value="member this.EnvironmentSettings : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudTask.EnvironmentSettings" />
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
            <span data-ttu-id="a2e06-155">取得またはタスクの環境変数設定の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="a2e06-155">Gets or sets a list of environment variable settings for the task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudTask.ETag" />
      <MemberSignature Language="VB.NET" Value="Public Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudTask.ETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="eTag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a2e06-156">取得またはタスクの ETag を設定します。</span><span class="sxs-lookup"><span data-stu-id="a2e06-156">Gets or sets the ETag of the task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="a2e06-157">これは、不透明な文字列です。</span><span class="sxs-lookup"><span data-stu-id="a2e06-157">This is an opaque string.</span></span> <span data-ttu-id="a2e06-158">要求間で、タスクが変更されたかどうかを検出するために使用できます。</span><span class="sxs-lookup"><span data-stu-id="a2e06-158">You can use it to detect whether the task has changed between requests.</span></span> <span data-ttu-id="a2e06-159">特にには、変更内容が反映されるその他のユーザーが変更、タスク間の場合にのみを指定するタスクを更新する場合に ETag を渡すことができます。</span><span class="sxs-lookup"><span data-stu-id="a2e06-159">In particular, you can be pass the ETag when updating a task to specify that your changes should take effect only if nobody else has modified the task in the meantime.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecutionInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation ExecutionInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation ExecutionInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudTask.ExecutionInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property ExecutionInfo As TaskExecutionInformation" />
      <MemberSignature Language="F#" Value="member this.ExecutionInfo : Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudTask.ExecutionInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="executionInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a2e06-160">取得またはタスクの実行に関する情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="a2e06-160">Gets or sets information about the execution of the task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExitConditions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.ExitConditions ExitConditions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.ExitConditions ExitConditions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudTask.ExitConditions" />
      <MemberSignature Language="VB.NET" Value="Public Property ExitConditions As ExitConditions" />
      <MemberSignature Language="F#" Value="member this.ExitConditions : Microsoft.Azure.Batch.Protocol.Models.ExitConditions with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudTask.ExitConditions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="exitConditions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ExitConditions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a2e06-161">取得または設定、タスクが完了したときに、バッチ サービスがどのように対処する必要がありますか。</span><span class="sxs-lookup"><span data-stu-id="a2e06-161">Gets or sets how the Batch service should respond when the task completes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudTask.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudTask.Id" />
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
            <span data-ttu-id="a2e06-162">取得または、ジョブ内のタスクを一意に識別する文字列を設定します。</span><span class="sxs-lookup"><span data-stu-id="a2e06-162">Gets or sets a string that uniquely identifies the task within the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="a2e06-163">ID は、ハイフン、アンダー スコアを含む、英数字の任意の組み合わせを含めることができ、64 を超える文字を含めることはできません。</span><span class="sxs-lookup"><span data-stu-id="a2e06-163">The ID can contain any combination of alphanumeric characters including hyphens and underscores, and cannot contain more than 64 characters.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModified">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastModified { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastModified" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudTask.LastModified" />
      <MemberSignature Language="VB.NET" Value="Public Property LastModified As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastModified : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudTask.LastModified" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastModified")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a2e06-164">取得またはタスクの最終更新時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="a2e06-164">Gets or sets the last modified time of the task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MultiInstanceSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings MultiInstanceSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings MultiInstanceSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudTask.MultiInstanceSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property MultiInstanceSettings As MultiInstanceSettings" />
      <MemberSignature Language="F#" Value="member this.MultiInstanceSettings : Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudTask.MultiInstanceSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="multiInstanceSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a2e06-165">取得または設定があること示しタスク複数インスタンスのタスクでは、複数インスタンスのタスクを実行する方法に関する情報を格納するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="a2e06-165">Gets or sets an object that indicates that the task is a multi-instance task, and contains information about how to run the multi-instance task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.ComputeNodeInformation NodeInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeInformation NodeInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudTask.NodeInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeInfo As ComputeNodeInformation" />
      <MemberSignature Language="F#" Value="member this.NodeInfo : Microsoft.Azure.Batch.Protocol.Models.ComputeNodeInformation with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudTask.NodeInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nodeInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ComputeNodeInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a2e06-166">取得またはタスクが実行したコンピューティング ノードに関する情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="a2e06-166">Gets or sets information about the compute node on which the task ran.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutputFiles">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.OutputFile&gt; OutputFiles { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.OutputFile&gt; OutputFiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudTask.OutputFiles" />
      <MemberSignature Language="VB.NET" Value="Public Property OutputFiles As IList(Of OutputFile)" />
      <MemberSignature Language="F#" Value="member this.OutputFiles : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.OutputFile&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudTask.OutputFiles" />
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
            <span data-ttu-id="a2e06-167">取得または、Batch service は、コマンドラインの実行後にコンピューティング ノードからアップロードするファイルの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="a2e06-167">Gets or sets a list of files that the Batch service will upload from the compute node after running the command line.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="a2e06-168">複数インスタンスのタスク、主要なタスクを実行するコンピューティング ノードから、ファイルのみアップロードされます。</span><span class="sxs-lookup"><span data-stu-id="a2e06-168">For multi-instance tasks, the files will only be uploaded from the compute node on which the primary task is executed.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PreviousState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskState&gt; PreviousState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.TaskState&gt; PreviousState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudTask.PreviousState" />
      <MemberSignature Language="VB.NET" Value="Public Property PreviousState As Nullable(Of TaskState)" />
      <MemberSignature Language="F#" Value="member this.PreviousState : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskState&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudTask.PreviousState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="previousState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a2e06-169">取得またはタスクの以前の状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="a2e06-169">Gets or sets the previous state of the task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="a2e06-170">タスクが初期のアクティブな状態にある場合、このプロパティは設定されません。</span><span class="sxs-lookup"><span data-stu-id="a2e06-170">This property is not set if the task is in its initial Active state.</span></span> <span data-ttu-id="a2e06-171">使用可能な値が含まれます: 'active'、'準備'、'実行中'、'完了'</span><span class="sxs-lookup"><span data-stu-id="a2e06-171">Possible values include: 'active', 'preparing', 'running', 'completed'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PreviousStateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; PreviousStateTransitionTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; PreviousStateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudTask.PreviousStateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public Property PreviousStateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.PreviousStateTransitionTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudTask.PreviousStateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="previousStateTransitionTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a2e06-172">取得またはタスクが前の状態を入力する時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="a2e06-172">Gets or sets the time at which the task entered its previous state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="a2e06-173">タスクが初期のアクティブな状態にある場合、このプロパティは設定されません。</span><span class="sxs-lookup"><span data-stu-id="a2e06-173">This property is not set if the task is in its initial Active state.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceFiles">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; ResourceFiles { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; ResourceFiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudTask.ResourceFiles" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceFiles As IList(Of ResourceFile)" />
      <MemberSignature Language="F#" Value="member this.ResourceFiles : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudTask.ResourceFiles" />
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
            <span data-ttu-id="a2e06-174">取得またはコマンドラインを実行する前に、バッチ サービスをコンピューティング ノードにダウンロードするファイルの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="a2e06-174">Gets or sets a list of files that the Batch service will download to the compute node before running the command line.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="a2e06-175">マルチ インスタンスのタスクを主なタスクを実行するコンピューティング ノードにリソース ファイルのみダウンロードされます。</span><span class="sxs-lookup"><span data-stu-id="a2e06-175">For multi-instance tasks, the resource files will only be downloaded to the compute node on which the primary task is executed.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskState&gt; State { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.TaskState&gt; State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudTask.State" />
      <MemberSignature Language="VB.NET" Value="Public Property State As Nullable(Of TaskState)" />
      <MemberSignature Language="F#" Value="member this.State : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskState&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudTask.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a2e06-176">取得またはタスクの現在の状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="a2e06-176">Gets or sets the current state of the task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="a2e06-177">使用可能な値が含まれます: 'active'、'準備'、'実行中'、'完了'</span><span class="sxs-lookup"><span data-stu-id="a2e06-177">Possible values include: 'active', 'preparing', 'running', 'completed'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StateTransitionTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudTask.StateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StateTransitionTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudTask.StateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="stateTransitionTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a2e06-178">取得またはタスクが、現在の状態を入力する時間を設定します。</span><span class="sxs-lookup"><span data-stu-id="a2e06-178">Gets or sets the time at which the task entered its current state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Stats">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskStatistics Stats { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskStatistics Stats" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudTask.Stats" />
      <MemberSignature Language="VB.NET" Value="Public Property Stats As TaskStatistics" />
      <MemberSignature Language="F#" Value="member this.Stats : Microsoft.Azure.Batch.Protocol.Models.TaskStatistics with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudTask.Stats" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="stats")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskStatistics</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a2e06-179">取得またはタスクのリソース使用状況の統計を設定します。</span><span class="sxs-lookup"><span data-stu-id="a2e06-179">Gets or sets resource usage statistics for the task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudTask.Url" />
      <MemberSignature Language="VB.NET" Value="Public Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudTask.Url" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="url")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a2e06-180">取得またはタスクの URL を設定します。</span><span class="sxs-lookup"><span data-stu-id="a2e06-180">Gets or sets the URL of the task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserIdentity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.UserIdentity UserIdentity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.UserIdentity UserIdentity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudTask.UserIdentity" />
      <MemberSignature Language="VB.NET" Value="Public Property UserIdentity As UserIdentity" />
      <MemberSignature Language="F#" Value="member this.UserIdentity : Microsoft.Azure.Batch.Protocol.Models.UserIdentity with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudTask.UserIdentity" />
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
            <span data-ttu-id="a2e06-181">取得またはタスクを実行するユーザー id を設定します。</span><span class="sxs-lookup"><span data-stu-id="a2e06-181">Gets or sets the user identity under which the task runs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="a2e06-182">省略した場合、そのタスクは、タスクに一意の非管理者のユーザーとして実行されます。</span><span class="sxs-lookup"><span data-stu-id="a2e06-182">If omitted, the task runs as a non-administrative user unique to the task.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.CloudTask.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="cloudTask.Validate " />
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
            <span data-ttu-id="a2e06-183">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="a2e06-183">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a2e06-184">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a2e06-184">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>