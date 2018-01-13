<Type Name="JobManagerTask" FullName="Microsoft.Azure.Batch.JobManagerTask">
  <TypeSignature Language="C#" Value="public class JobManagerTask" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobManagerTask extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.JobManagerTask" />
  <TypeSignature Language="VB.NET" Value="Public Class JobManagerTask" />
  <TypeSignature Language="F#" Value="type JobManagerTask = class&#xA;    interface ITransportObjectProvider&lt;JobManagerTask&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            <span data-ttu-id="d82c7-101">Azure Batch JobManager タスクを表します。</span><span class="sxs-lookup"><span data-stu-id="d82c7-101">Represents an Azure Batch JobManager task.</span></span> 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobManagerTask ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobManagerTask.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobManagerTask (string id, string commandLine);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string commandLine) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobManagerTask.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (id As String, commandLine As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.JobManagerTask : string * string -&gt; Microsoft.Azure.Batch.JobManagerTask" Usage="new Microsoft.Azure.Batch.JobManagerTask (id, commandLine)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="commandLine" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="d82c7-102">タスクの ID です。</span><span class="sxs-lookup"><span data-stu-id="d82c7-102">The id of the task.</span></span></param>
        <param name="commandLine"><span data-ttu-id="d82c7-103">タスクのコマンドラインです。</span><span class="sxs-lookup"><span data-stu-id="d82c7-103">The command line of the task.</span></span></param>
        <summary>
            <span data-ttu-id="d82c7-104"><see cref="T:Microsoft.Azure.Batch.JobManagerTask" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d82c7-104">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.JobManagerTask" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowLowPriorityNode">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; AllowLowPriorityNode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; AllowLowPriorityNode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobManagerTask.AllowLowPriorityNode" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowLowPriorityNode As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.AllowLowPriorityNode : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.JobManagerTask.AllowLowPriorityNode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d82c7-105">取得または、ジョブ マネージャー タスクは、優先度の低いコンピューティング ノードで実行するかどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="d82c7-105">Gets or sets whether the Job Manager task may run on a low-priority compute node.</span></span> <span data-ttu-id="d82c7-106">省略した場合、既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="d82c7-106">If omitted, the default is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationPackageReferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ApplicationPackageReference&gt; ApplicationPackageReferences { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.ApplicationPackageReference&gt; ApplicationPackageReferences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobManagerTask.ApplicationPackageReferences" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationPackageReferences As IList(Of ApplicationPackageReference)" />
      <MemberSignature Language="F#" Value="member this.ApplicationPackageReferences : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ApplicationPackageReference&gt; with get, set" Usage="Microsoft.Azure.Batch.JobManagerTask.ApplicationPackageReferences" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ApplicationPackageReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d82c7-107">取得またはコマンドラインを実行する前に、コンピューティング ノードに、バッチ サービスを展開するアプリケーション パッケージの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="d82c7-107">Gets or sets a list of application packages that the Batch service will deploy to the compute node before running the command line.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationTokenSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.AuthenticationTokenSettings AuthenticationTokenSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.AuthenticationTokenSettings AuthenticationTokenSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobManagerTask.AuthenticationTokenSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationTokenSettings As AuthenticationTokenSettings" />
      <MemberSignature Language="F#" Value="member this.AuthenticationTokenSettings : Microsoft.Azure.Batch.AuthenticationTokenSettings with get, set" Usage="Microsoft.Azure.Batch.JobManagerTask.AuthenticationTokenSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.AuthenticationTokenSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d82c7-108">取得またはバッチ サービス操作を実行するタスクが使用できる認証トークンの設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="d82c7-108">Gets or sets the settings for an authentication token that the task can use to perform Batch service operations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="d82c7-109">このプロパティが設定されている場合、バッチ サービスは、アカウント アクセス キーを必要とせず、Batch service 操作を認証するために使用する認証トークンを使用してタスクを提供します。</span><span class="sxs-lookup"><span data-stu-id="d82c7-109">If this property is set, the Batch service provides the task with an authentication token which can be used to authenticate Batch service operations without requiring an account access key.</span></span> <span data-ttu-id="d82c7-110">トークンが AZ_BATCH_AUTHENTICATION_TOKEN 環境変数を介して提供されます。</span><span class="sxs-lookup"><span data-stu-id="d82c7-110">The token is provided via the AZ_BATCH_AUTHENTICATION_TOKEN environment variable.</span></span> <span data-ttu-id="d82c7-111">トークンを使用して、タスクが実行できる操作は、設定によって決まります。</span><span class="sxs-lookup"><span data-stu-id="d82c7-111">The operations that the task can carry out using the token depend on the settings.</span></span> <span data-ttu-id="d82c7-112">たとえば、タスクは、ジョブを他のタスクを追加するか、または他のタスクのジョブの状態を確認するために、ジョブのアクセス許可を要求できます。</span><span class="sxs-lookup"><span data-stu-id="d82c7-112">For example, a task can request job permissions in order to add other tasks to the job, or check the status of the job or of other tasks.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CommandLine">
      <MemberSignature Language="C#" Value="public string CommandLine { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CommandLine" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobManagerTask.CommandLine" />
      <MemberSignature Language="VB.NET" Value="Public Property CommandLine As String" />
      <MemberSignature Language="F#" Value="member this.CommandLine : string with get, set" Usage="Microsoft.Azure.Batch.JobManagerTask.CommandLine" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d82c7-113">取得またはタスクのコマンドラインを設定します。</span><span class="sxs-lookup"><span data-stu-id="d82c7-113">Gets or sets the command line of the task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="d82c7-114">コマンド ライン シェルが動作しないためできません利用して環境変数の展開などのシェルの機能の。</span><span class="sxs-lookup"><span data-stu-id="d82c7-114">The command line does not run under a shell, and therefore cannot take advantage of shell features such as environment variable expansion.</span></span> <span data-ttu-id="d82c7-115">このような機能を利用する場合を呼び出すように、コマンド ライン シェルたとえば"cmd/c MyCommand"を使用して windows または"/bin/sh-c MyCommand"Linux でします。</span><span class="sxs-lookup"><span data-stu-id="d82c7-115">If you want to take advantage of such features, you should invoke the shell in the command line, for example using "cmd /c MyCommand" in Windows or "/bin/sh -c MyCommand" in Linux.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Constraints">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.TaskConstraints Constraints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.TaskConstraints Constraints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobManagerTask.Constraints" />
      <MemberSignature Language="VB.NET" Value="Public Property Constraints As TaskConstraints" />
      <MemberSignature Language="F#" Value="member this.Constraints : Microsoft.Azure.Batch.TaskConstraints with get, set" Usage="Microsoft.Azure.Batch.JobManagerTask.Constraints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.TaskConstraints</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d82c7-116">取得またはこの JobManager タスクの実行の制約を設定します。</span><span class="sxs-lookup"><span data-stu-id="d82c7-116">Gets or sets the execution constraints for this JobManager task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.TaskContainerSettings ContainerSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.TaskContainerSettings ContainerSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobManagerTask.ContainerSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerSettings As TaskContainerSettings" />
      <MemberSignature Language="F#" Value="member this.ContainerSettings : Microsoft.Azure.Batch.TaskContainerSettings with get, set" Usage="Microsoft.Azure.Batch.JobManagerTask.ContainerSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.TaskContainerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d82c7-117">取得またはタスクを実行するコンテナーの設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="d82c7-117">Gets or sets the settings for the container under which the task runs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="d82c7-118">このタスクを実行しているプールがある場合<see cref="P:Microsoft.Azure.Batch.VirtualMachineConfiguration.ContainerConfiguration" />設定すると、この設定する必要がなくです。</span><span class="sxs-lookup"><span data-stu-id="d82c7-118">If the pool that will run this task has <see cref="P:Microsoft.Azure.Batch.VirtualMachineConfiguration.ContainerConfiguration" /> set, this must be set as well.</span></span> <span data-ttu-id="d82c7-119">このタスクを実行しているプールがないかどうか<see cref="P:Microsoft.Azure.Batch.VirtualMachineConfiguration.ContainerConfiguration" />設定すると、この設定しないでください。</span><span class="sxs-lookup"><span data-stu-id="d82c7-119">If the pool that will run this task doesn't have <see cref="P:Microsoft.Azure.Batch.VirtualMachineConfiguration.ContainerConfiguration" /> set, this must not be set.</span></span> <span data-ttu-id="d82c7-120">これを指定すると、AZ_BATCH_NODE_ROOT_DIR (ノードの Azure Batch のディレクトリのルート) の下のすべてのディレクトリに再帰的には、コンテナーにマップされて、すべてのタスクの環境変数が、コンテナーにマップおよびタスクのコマンドラインは、コンテナーで実行されます。</span><span class="sxs-lookup"><span data-stu-id="d82c7-120">When this is specified, all directories recursively below the AZ_BATCH_NODE_ROOT_DIR (the root of Azure Batch directories on the node) are mapped into the container, all task environment variables are mapped into the container, and the task command line is executed in the container.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobManagerTask.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Batch.JobManagerTask.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d82c7-121">取得または JobManager タスクの表示名を設定します。</span><span class="sxs-lookup"><span data-stu-id="d82c7-121">Gets or sets the display name of the JobManager task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnvironmentSettings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.EnvironmentSetting&gt; EnvironmentSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.EnvironmentSetting&gt; EnvironmentSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobManagerTask.EnvironmentSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property EnvironmentSettings As IList(Of EnvironmentSetting)" />
      <MemberSignature Language="F#" Value="member this.EnvironmentSettings : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.EnvironmentSetting&gt; with get, set" Usage="Microsoft.Azure.Batch.JobManagerTask.EnvironmentSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.EnvironmentSetting&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d82c7-122">取得または JobManager タスクの環境設定のセットを設定します。</span><span class="sxs-lookup"><span data-stu-id="d82c7-122">Gets or sets a set of environment settings for the JobManager task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobManagerTask.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Batch.JobManagerTask.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d82c7-123">取得またはタスクの id を設定します。</span><span class="sxs-lookup"><span data-stu-id="d82c7-123">Gets or sets the id of the task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KillJobOnCompletion">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; KillJobOnCompletion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; KillJobOnCompletion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobManagerTask.KillJobOnCompletion" />
      <MemberSignature Language="VB.NET" Value="Public Property KillJobOnCompletion As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.KillJobOnCompletion : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.JobManagerTask.KillJobOnCompletion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d82c7-124">取得またはジョブのすべてのタスクを終了してから、ジョブ マネージャー タスクの完了時に、ジョブを完了するかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="d82c7-124">Gets or sets a value that indicates whether to terminate all tasks in the job and complete the job when the job manager task completes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutputFiles">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.OutputFile&gt; OutputFiles { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.OutputFile&gt; OutputFiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobManagerTask.OutputFiles" />
      <MemberSignature Language="VB.NET" Value="Public Property OutputFiles As IList(Of OutputFile)" />
      <MemberSignature Language="F#" Value="member this.OutputFiles : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.OutputFile&gt; with get, set" Usage="Microsoft.Azure.Batch.JobManagerTask.OutputFiles" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.OutputFile&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d82c7-125">取得または、Batch service は、コマンドラインの実行後にコンピューティング ノードからアップロードするファイルの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="d82c7-125">Gets or sets a list of files that the Batch service will upload from the compute node after running the command line.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceFiles">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ResourceFile&gt; ResourceFiles { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.ResourceFile&gt; ResourceFiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobManagerTask.ResourceFiles" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceFiles As IList(Of ResourceFile)" />
      <MemberSignature Language="F#" Value="member this.ResourceFiles : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ResourceFile&gt; with get, set" Usage="Microsoft.Azure.Batch.JobManagerTask.ResourceFiles" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ResourceFile&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d82c7-126">取得またはコマンドラインを実行する前に、バッチ サービスをコンピューティング ノードにダウンロードするファイルの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="d82c7-126">Gets or sets a list of files that the Batch service will download to the compute node before running the command line.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RunExclusive">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; RunExclusive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; RunExclusive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobManagerTask.RunExclusive" />
      <MemberSignature Language="VB.NET" Value="Public Property RunExclusive As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RunExclusive : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.JobManagerTask.RunExclusive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d82c7-127">取得またはが実行されるジョブ マネージャー タスクが、コンピューティング ノードの排他的な使用を必要とするかどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="d82c7-127">Gets or sets whether the Job Manager task requires exclusive use of the compute node where it runs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserIdentity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.UserIdentity UserIdentity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.UserIdentity UserIdentity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobManagerTask.UserIdentity" />
      <MemberSignature Language="VB.NET" Value="Public Property UserIdentity As UserIdentity" />
      <MemberSignature Language="F#" Value="member this.UserIdentity : Microsoft.Azure.Batch.UserIdentity with get, set" Usage="Microsoft.Azure.Batch.JobManagerTask.UserIdentity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.UserIdentity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d82c7-128">取得またはタスクを実行するユーザー id を設定します。</span><span class="sxs-lookup"><span data-stu-id="d82c7-128">Gets or sets the user identity under which the task runs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="d82c7-129">省略した場合、そのタスクは、タスクに一意の非管理者のユーザーとして実行されます。</span><span class="sxs-lookup"><span data-stu-id="d82c7-129">If omitted, the task runs as a non-administrative user unique to the task.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>