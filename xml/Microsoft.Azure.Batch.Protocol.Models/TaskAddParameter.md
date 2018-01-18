<Type Name="TaskAddParameter" FullName="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter">
  <TypeSignature Language="C#" Value="public class TaskAddParameter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskAddParameter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskAddParameter" />
  <TypeSignature Language="F#" Value="type TaskAddParameter = class" />
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
            <span data-ttu-id="01228-101">追加する Azure のバッチ タスクです。</span><span class="sxs-lookup"><span data-stu-id="01228-101">An Azure Batch task to add.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskAddParameter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.#ctor" />
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
            <span data-ttu-id="01228-102">TaskAddParameter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="01228-102">Initializes a new instance of the TaskAddParameter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskAddParameter (string id, string commandLine, string displayName = null, Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings containerSettings = null, Microsoft.Azure.Batch.Protocol.Models.ExitConditions exitConditions = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; resourceFiles = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.OutputFile&gt; outputFiles = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; environmentSettings = null, Microsoft.Azure.Batch.Protocol.Models.AffinityInformation affinityInfo = null, Microsoft.Azure.Batch.Protocol.Models.TaskConstraints constraints = null, Microsoft.Azure.Batch.Protocol.Models.UserIdentity userIdentity = null, Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings multiInstanceSettings = null, Microsoft.Azure.Batch.Protocol.Models.TaskDependencies dependsOn = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; applicationPackageReferences = null, Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings authenticationTokenSettings = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string commandLine, string displayName, class Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings containerSettings, class Microsoft.Azure.Batch.Protocol.Models.ExitConditions exitConditions, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; resourceFiles, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.OutputFile&gt; outputFiles, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; environmentSettings, class Microsoft.Azure.Batch.Protocol.Models.AffinityInformation affinityInfo, class Microsoft.Azure.Batch.Protocol.Models.TaskConstraints constraints, class Microsoft.Azure.Batch.Protocol.Models.UserIdentity userIdentity, class Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings multiInstanceSettings, class Microsoft.Azure.Batch.Protocol.Models.TaskDependencies dependsOn, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; applicationPackageReferences, class Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings authenticationTokenSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.#ctor(System.String,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings,Microsoft.Azure.Batch.Protocol.Models.ExitConditions,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.ResourceFile},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.OutputFile},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting},Microsoft.Azure.Batch.Protocol.Models.AffinityInformation,Microsoft.Azure.Batch.Protocol.Models.TaskConstraints,Microsoft.Azure.Batch.Protocol.Models.UserIdentity,Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings,Microsoft.Azure.Batch.Protocol.Models.TaskDependencies,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference},Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter : string * string * string * Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings * Microsoft.Azure.Batch.Protocol.Models.ExitConditions * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.OutputFile&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; * Microsoft.Azure.Batch.Protocol.Models.AffinityInformation * Microsoft.Azure.Batch.Protocol.Models.TaskConstraints * Microsoft.Azure.Batch.Protocol.Models.UserIdentity * Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings * Microsoft.Azure.Batch.Protocol.Models.TaskDependencies * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; * Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter" Usage="new Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter (id, commandLine, displayName, containerSettings, exitConditions, resourceFiles, outputFiles, environmentSettings, affinityInfo, constraints, userIdentity, multiInstanceSettings, dependsOn, applicationPackageReferences, authenticationTokenSettings)" />
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
        <Parameter Name="exitConditions" Type="Microsoft.Azure.Batch.Protocol.Models.ExitConditions" />
        <Parameter Name="resourceFiles" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt;" />
        <Parameter Name="outputFiles" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.OutputFile&gt;" />
        <Parameter Name="environmentSettings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt;" />
        <Parameter Name="affinityInfo" Type="Microsoft.Azure.Batch.Protocol.Models.AffinityInformation" />
        <Parameter Name="constraints" Type="Microsoft.Azure.Batch.Protocol.Models.TaskConstraints" />
        <Parameter Name="userIdentity" Type="Microsoft.Azure.Batch.Protocol.Models.UserIdentity" />
        <Parameter Name="multiInstanceSettings" Type="Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings" />
        <Parameter Name="dependsOn" Type="Microsoft.Azure.Batch.Protocol.Models.TaskDependencies" />
        <Parameter Name="applicationPackageReferences" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt;" />
        <Parameter Name="authenticationTokenSettings" Type="Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="01228-103">ジョブ内のタスクを一意に識別する文字列。</span><span class="sxs-lookup"><span data-stu-id="01228-103">A string that uniquely identifies the task within the job.</span></span></param>
        <param name="commandLine"><span data-ttu-id="01228-104">タスクのコマンドラインです。</span><span class="sxs-lookup"><span data-stu-id="01228-104">The command line of the task.</span></span></param>
        <param name="displayName"><span data-ttu-id="01228-105">タスクの表示名。</span><span class="sxs-lookup"><span data-stu-id="01228-105">A display name for the task.</span></span></param>
        <param name="containerSettings"><span data-ttu-id="01228-106">タスクを実行するコンテナーの設定。</span><span class="sxs-lookup"><span data-stu-id="01228-106">The settings for the container under which the task runs.</span></span></param>
        <param name="exitConditions"><span data-ttu-id="01228-107">バッチ サービスの応答方法、タスクが完了したときにします。</span><span class="sxs-lookup"><span data-stu-id="01228-107">How the Batch service should respond when the task completes.</span></span></param>
        <param name="resourceFiles"><span data-ttu-id="01228-108">バッチ サービスはコマンドラインを実行する前にコンピューティング ノードにダウンロードされるファイルの一覧。</span><span class="sxs-lookup"><span data-stu-id="01228-108">A list of files that the Batch service will download to the compute node before running the command line.</span></span></param>
        <param name="outputFiles"><span data-ttu-id="01228-109">バッチ サービスはコマンドラインの実行後にコンピューティング ノードからアップロードするファイルの一覧です。</span><span class="sxs-lookup"><span data-stu-id="01228-109">A list of files that the Batch service will upload from the compute node after running the command line.</span></span></param>
        <param name="environmentSettings"><span data-ttu-id="01228-110">タスクの環境変数設定の一覧。</span><span class="sxs-lookup"><span data-stu-id="01228-110">A list of environment variable settings for the task.</span></span></param>
        <param name="affinityInfo"><span data-ttu-id="01228-111">新しいタスクを開始するコンピューティング ノードを選択する、Batch service によって使用できる局所性のヒント。</span><span class="sxs-lookup"><span data-stu-id="01228-111">A locality hint that can be used by the Batch service to select a compute node on which to start the new task.</span></span></param>
        <param name="constraints"><span data-ttu-id="01228-112">このタスクに適用される実行の制約。</span><span class="sxs-lookup"><span data-stu-id="01228-112">The execution constraints that apply to this task.</span></span></param>
        <param name="userIdentity"><span data-ttu-id="01228-113">タスクを実行するユーザー id。</span><span class="sxs-lookup"><span data-stu-id="01228-113">The user identity under which the task runs.</span></span></param>
        <param name="multiInstanceSettings"><span data-ttu-id="01228-114">タスクが複数のインスタンス、タスクは、複数インスタンスのタスクを実行する方法に関する情報を格納であることを示すオブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="01228-114">An object that indicates that the task is a multi-instance task, and contains information about how to run the multi-instance task.</span></span></param>
        <param name="dependsOn"><span data-ttu-id="01228-115">このタスクは、このタスクに依存します。</span><span class="sxs-lookup"><span data-stu-id="01228-115">The tasks that this task depends on.</span></span></param>
        <param name="applicationPackageReferences"><span data-ttu-id="01228-116">バッチ サービスは、コマンドラインを実行する前に、コンピューティング ノードに配置するアプリケーション パッケージの一覧。</span><span class="sxs-lookup"><span data-stu-id="01228-116">A list of application packages that the Batch service will deploy to the compute node before running the command line.</span></span></param>
        <param name="authenticationTokenSettings"><span data-ttu-id="01228-117">バッチを実行するタスクを使用する認証トークンの設定は、操作を処理します。</span><span class="sxs-lookup"><span data-stu-id="01228-117">The settings for an authentication token that the task can use to perform Batch service operations.</span></span></param>
        <summary>
            <span data-ttu-id="01228-118">TaskAddParameter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="01228-118">Initializes a new instance of the TaskAddParameter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AffinityInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.AffinityInformation AffinityInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.AffinityInformation AffinityInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.AffinityInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property AffinityInfo As AffinityInformation" />
      <MemberSignature Language="F#" Value="member this.AffinityInfo : Microsoft.Azure.Batch.Protocol.Models.AffinityInformation with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.AffinityInfo" />
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
            <span data-ttu-id="01228-119">取得または新しいタスクを開始するコンピューティング ノードを選択する、Batch service によって使用できる局所性のヒントを設定します。</span><span class="sxs-lookup"><span data-stu-id="01228-119">Gets or sets a locality hint that can be used by the Batch service to select a compute node on which to start the new task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationPackageReferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; ApplicationPackageReferences { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; ApplicationPackageReferences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.ApplicationPackageReferences" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationPackageReferences As IList(Of ApplicationPackageReference)" />
      <MemberSignature Language="F#" Value="member this.ApplicationPackageReferences : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.ApplicationPackageReferences" />
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
            <span data-ttu-id="01228-120">取得またはコマンドラインを実行する前に、コンピューティング ノードに、バッチ サービスを展開するアプリケーション パッケージの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="01228-120">Gets or sets a list of application packages that the Batch service will deploy to the compute node before running the command line.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="01228-121">アプリケーション パッケージがダウンロードされ、作業ディレクトリのタスクではない、共有ディレクトリに配置します。</span><span class="sxs-lookup"><span data-stu-id="01228-121">Application packages are downloaded and deployed to a shared directory, not the task working directory.</span></span> <span data-ttu-id="01228-122">そのため、参照されているパッケージは既にコンピューティング ノードでありは最新の状態場合、し、これは再ダウンロードされません;コンピューティング ノードで、既存のコピーが使用されます。</span><span class="sxs-lookup"><span data-stu-id="01228-122">Therefore, if a referenced package is already on the compute node, and is up to date, then it is not re-downloaded; the existing copy on the compute node is used.</span></span> <span data-ttu-id="01228-123">参照先のアプリケーション パッケージをインストールできない場合、例については、パッケージが削除されたか、ダウンロードが失敗したため、タスクが失敗したためです。</span><span class="sxs-lookup"><span data-stu-id="01228-123">If a referenced application package cannot be installed, for example because the package has been deleted or because download failed, the task fails.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationTokenSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings AuthenticationTokenSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings AuthenticationTokenSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.AuthenticationTokenSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationTokenSettings As AuthenticationTokenSettings" />
      <MemberSignature Language="F#" Value="member this.AuthenticationTokenSettings : Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.AuthenticationTokenSettings" />
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
            <span data-ttu-id="01228-124">取得またはバッチ サービス操作を実行するタスクが使用できる認証トークンの設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="01228-124">Gets or sets the settings for an authentication token that the task can use to perform Batch service operations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="01228-125">このプロパティが設定されている場合、バッチ サービスは、アカウント アクセス キーを必要とせず、Batch service 操作を認証するために使用する認証トークンを使用してタスクを提供します。</span><span class="sxs-lookup"><span data-stu-id="01228-125">If this property is set, the Batch service provides the task with an authentication token which can be used to authenticate Batch service operations without requiring an account access key.</span></span> <span data-ttu-id="01228-126">トークンが AZ_BATCH_AUTHENTICATION_TOKEN 環境変数を介して提供されます。</span><span class="sxs-lookup"><span data-stu-id="01228-126">The token is provided via the AZ_BATCH_AUTHENTICATION_TOKEN environment variable.</span></span> <span data-ttu-id="01228-127">トークンを使用して、タスクが実行できる操作は、設定によって決まります。</span><span class="sxs-lookup"><span data-stu-id="01228-127">The operations that the task can carry out using the token depend on the settings.</span></span> <span data-ttu-id="01228-128">たとえば、タスクは、ジョブを他のタスクを追加するか、またはその他のタスクは、ジョブのジョブの状態を確認するために、ジョブのアクセス許可を要求できます。</span><span class="sxs-lookup"><span data-stu-id="01228-128">For example, a task can request job permissions in order to add other tasks to the job, or check the status of the job or of other tasks under the job.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CommandLine">
      <MemberSignature Language="C#" Value="public string CommandLine { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CommandLine" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.CommandLine" />
      <MemberSignature Language="VB.NET" Value="Public Property CommandLine As String" />
      <MemberSignature Language="F#" Value="member this.CommandLine : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.CommandLine" />
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
            <span data-ttu-id="01228-129">取得またはタスクのコマンドラインを設定します。</span><span class="sxs-lookup"><span data-stu-id="01228-129">Gets or sets the command line of the task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="01228-130">マルチ インスタンスのタスクの主要なタスクとサブタスクをすべての調整のコマンドラインの実行が完了した後、コマンドラインは、主要なタスクとして実行されます。</span><span class="sxs-lookup"><span data-stu-id="01228-130">For multi-instance tasks, the command line is executed as the primary task, after the primary task and all subtasks have finished executing the coordination command line.</span></span> <span data-ttu-id="01228-131">コマンド ライン シェルが動作しないためできません利用して環境変数の展開などのシェルの機能の。</span><span class="sxs-lookup"><span data-stu-id="01228-131">The command line does not run under a shell, and therefore cannot take advantage of shell features such as environment variable expansion.</span></span> <span data-ttu-id="01228-132">このような機能を利用する場合を呼び出すように、コマンド ライン シェルたとえば"cmd/c MyCommand"を使用して windows または"/bin/sh-c MyCommand"Linux でします。</span><span class="sxs-lookup"><span data-stu-id="01228-132">If you want to take advantage of such features, you should invoke the shell in the command line, for example using "cmd /c MyCommand" in Windows or "/bin/sh -c MyCommand" in Linux.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Constraints">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskConstraints Constraints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskConstraints Constraints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.Constraints" />
      <MemberSignature Language="VB.NET" Value="Public Property Constraints As TaskConstraints" />
      <MemberSignature Language="F#" Value="member this.Constraints : Microsoft.Azure.Batch.Protocol.Models.TaskConstraints with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.Constraints" />
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
            <span data-ttu-id="01228-133">取得または、このタスクに適用される実行制約を設定します。</span><span class="sxs-lookup"><span data-stu-id="01228-133">Gets or sets the execution constraints that apply to this task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="01228-134">制約を指定しない場合、maxTaskRetryCount ジョブでは、指定された maxTaskRetryCount は、maxWallClockTime と retentionTime は有限です。</span><span class="sxs-lookup"><span data-stu-id="01228-134">If you do not specify constraints, the maxTaskRetryCount is the maxTaskRetryCount specified for the job, and the maxWallClockTime and retentionTime are infinite.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings ContainerSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings ContainerSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.ContainerSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerSettings As TaskContainerSettings" />
      <MemberSignature Language="F#" Value="member this.ContainerSettings : Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.ContainerSettings" />
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
            <span data-ttu-id="01228-135">取得またはタスクを実行するコンテナーの設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="01228-135">Gets or sets the settings for the container under which the task runs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="01228-136">このタスクを実行している、プールに containerConfiguration 設定がある場合は、これはも設定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="01228-136">If the pool that will run this task has containerConfiguration set, this must be set as well.</span></span> <span data-ttu-id="01228-137">このタスクを実行している、プールには、設定 containerConfiguration が割り当てられていない、これを設定しないでください。</span><span class="sxs-lookup"><span data-stu-id="01228-137">If the pool that will run this task doesn't have containerConfiguration set, this must not be set.</span></span> <span data-ttu-id="01228-138">これを指定すると、AZ_BATCH_NODE_ROOT_DIR (ノードの Azure Batch のディレクトリのルート) の下のすべてのディレクトリに再帰的には、コンテナーにマップされて、すべてのタスクの環境変数が、コンテナーにマップおよびタスクのコマンドラインは、コンテナーで実行されます。</span><span class="sxs-lookup"><span data-stu-id="01228-138">When this is specified, all directories recursively below the AZ_BATCH_NODE_ROOT_DIR (the root of Azure Batch directories on the node) are mapped into the container, all task environment variables are mapped into the container, and the task command line is executed in the container.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DependsOn">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskDependencies DependsOn { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskDependencies DependsOn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.DependsOn" />
      <MemberSignature Language="VB.NET" Value="Public Property DependsOn As TaskDependencies" />
      <MemberSignature Language="F#" Value="member this.DependsOn : Microsoft.Azure.Batch.Protocol.Models.TaskDependencies with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.DependsOn" />
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
            <span data-ttu-id="01228-139">取得または、このタスクが依存しているタスクを設定します。</span><span class="sxs-lookup"><span data-stu-id="01228-139">Gets or sets the tasks that this task depends on.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="01228-140">依存しているすべてのタスクが正常に完了するまで、このタスクはスケジュールされません。</span><span class="sxs-lookup"><span data-stu-id="01228-140">This task will not be scheduled until all tasks that it depends on have completed successfully.</span></span> <span data-ttu-id="01228-141">失敗の再試行カウントを使い果たすそれらのタスクのいずれかの場合は、このタスクがスケジュールされることはありません。</span><span class="sxs-lookup"><span data-stu-id="01228-141">If any of those tasks fail and exhaust their retry counts, this task will never be scheduled.</span></span> <span data-ttu-id="01228-142">ジョブがない場合は、usesTaskDependencies true で、この要素に設定が存在、要求がエラー コード TaskDependenciesNotSpecifiedOnJob です。</span><span class="sxs-lookup"><span data-stu-id="01228-142">If the job does not have usesTaskDependencies set to true, and this element is present, the request fails with error code TaskDependenciesNotSpecifiedOnJob.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.DisplayName" />
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
            <span data-ttu-id="01228-143">取得またはタスクの表示名を設定します。</span><span class="sxs-lookup"><span data-stu-id="01228-143">Gets or sets a display name for the task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="01228-144">表示名は一意でない必要があり、最大で 1,024 の最大長の Unicode 文字を含めることができます。</span><span class="sxs-lookup"><span data-stu-id="01228-144">The display name need not be unique and can contain any Unicode characters up to a maximum length of 1024.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnvironmentSettings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; EnvironmentSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; EnvironmentSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.EnvironmentSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property EnvironmentSettings As IList(Of EnvironmentSetting)" />
      <MemberSignature Language="F#" Value="member this.EnvironmentSettings : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.EnvironmentSettings" />
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
            <span data-ttu-id="01228-145">取得またはタスクの環境変数設定の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="01228-145">Gets or sets a list of environment variable settings for the task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExitConditions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.ExitConditions ExitConditions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.ExitConditions ExitConditions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.ExitConditions" />
      <MemberSignature Language="VB.NET" Value="Public Property ExitConditions As ExitConditions" />
      <MemberSignature Language="F#" Value="member this.ExitConditions : Microsoft.Azure.Batch.Protocol.Models.ExitConditions with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.ExitConditions" />
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
            <span data-ttu-id="01228-146">取得または設定、タスクが完了したときに、バッチ サービスがどのように対処する必要がありますか。</span><span class="sxs-lookup"><span data-stu-id="01228-146">Gets or sets how the Batch service should respond when the task completes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.Id" />
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
            <span data-ttu-id="01228-147">取得または、ジョブ内のタスクを一意に識別する文字列を設定します。</span><span class="sxs-lookup"><span data-stu-id="01228-147">Gets or sets a string that uniquely identifies the task within the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="01228-148">ID は、ハイフン、アンダー スコアを含む、英数字の任意の組み合わせを含めることができ、64 を超える文字を含めることはできません。</span><span class="sxs-lookup"><span data-stu-id="01228-148">The ID can contain any combination of alphanumeric characters including hyphens and underscores, and cannot contain more than 64 characters.</span></span> <span data-ttu-id="01228-149">ID は大文字と小文字を区別 (つまり、大文字と小文字が異なるのみ、ジョブ内の 2 つの Id はない必要があります)。</span><span class="sxs-lookup"><span data-stu-id="01228-149">The ID is case-preserving and case-insensitive (that is, you may not have two IDs within a job that differ only by case).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MultiInstanceSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings MultiInstanceSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings MultiInstanceSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.MultiInstanceSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property MultiInstanceSettings As MultiInstanceSettings" />
      <MemberSignature Language="F#" Value="member this.MultiInstanceSettings : Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.MultiInstanceSettings" />
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
            <span data-ttu-id="01228-150">取得または設定があること示しタスク複数インスタンスのタスクでは、複数インスタンスのタスクを実行する方法に関する情報を格納するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="01228-150">Gets or sets an object that indicates that the task is a multi-instance task, and contains information about how to run the multi-instance task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutputFiles">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.OutputFile&gt; OutputFiles { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.OutputFile&gt; OutputFiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.OutputFiles" />
      <MemberSignature Language="VB.NET" Value="Public Property OutputFiles As IList(Of OutputFile)" />
      <MemberSignature Language="F#" Value="member this.OutputFiles : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.OutputFile&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.OutputFiles" />
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
            <span data-ttu-id="01228-151">取得または、Batch service は、コマンドラインの実行後にコンピューティング ノードからアップロードするファイルの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="01228-151">Gets or sets a list of files that the Batch service will upload from the compute node after running the command line.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="01228-152">複数インスタンスのタスク、主要なタスクを実行するコンピューティング ノードから、ファイルのみアップロードされます。</span><span class="sxs-lookup"><span data-stu-id="01228-152">For multi-instance tasks, the files will only be uploaded from the compute node on which the primary task is executed.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceFiles">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; ResourceFiles { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; ResourceFiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.ResourceFiles" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceFiles As IList(Of ResourceFile)" />
      <MemberSignature Language="F#" Value="member this.ResourceFiles : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.ResourceFiles" />
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
            <span data-ttu-id="01228-153">取得またはコマンドラインを実行する前に、バッチ サービスをコンピューティング ノードにダウンロードするファイルの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="01228-153">Gets or sets a list of files that the Batch service will download to the compute node before running the command line.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="01228-154">マルチ インスタンスのタスクを主なタスクを実行するコンピューティング ノードにリソース ファイルのみダウンロードされます。</span><span class="sxs-lookup"><span data-stu-id="01228-154">For multi-instance tasks, the resource files will only be downloaded to the compute node on which the primary task is executed.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UserIdentity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.UserIdentity UserIdentity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.UserIdentity UserIdentity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.UserIdentity" />
      <MemberSignature Language="VB.NET" Value="Public Property UserIdentity As UserIdentity" />
      <MemberSignature Language="F#" Value="member this.UserIdentity : Microsoft.Azure.Batch.Protocol.Models.UserIdentity with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.UserIdentity" />
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
            <span data-ttu-id="01228-155">取得またはタスクを実行するユーザー id を設定します。</span><span class="sxs-lookup"><span data-stu-id="01228-155">Gets or sets the user identity under which the task runs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="01228-156">省略した場合、そのタスクは、タスクに一意の非管理者のユーザーとして実行されます。</span><span class="sxs-lookup"><span data-stu-id="01228-156">If omitted, the task runs as a non-administrative user unique to the task.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="taskAddParameter.Validate " />
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
            <span data-ttu-id="01228-157">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="01228-157">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="01228-158">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="01228-158">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>