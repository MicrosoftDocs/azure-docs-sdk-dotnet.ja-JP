<Type Name="CloudTask" FullName="Microsoft.Azure.Batch.CloudTask">
  <TypeSignature Language="C#" Value="public class CloudTask : Microsoft.Azure.Batch.IInheritedBehaviors, Microsoft.Azure.Batch.IRefreshable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CloudTask extends System.Object implements class Microsoft.Azure.Batch.IInheritedBehaviors, class Microsoft.Azure.Batch.IRefreshable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.CloudTask" />
  <TypeSignature Language="VB.NET" Value="Public Class CloudTask&#xA;Implements IInheritedBehaviors, IRefreshable" />
  <TypeSignature Language="F#" Value="type CloudTask = class&#xA;    interface IRefreshable&#xA;    interface ITransportObjectProvider&lt;TaskAddParameter&gt;&#xA;    interface IInheritedBehaviors&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Batch.IInheritedBehaviors</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Batch.IRefreshable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="2b8bb-101">Azure Batch のタスクの場合。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-101">An Azure Batch task.</span></span>  <span data-ttu-id="2b8bb-102">タスクは、ジョブに関連付けられ、コンピューティング ノード上で動作する 1 つの処理です。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-102">A task is a piece of work that is associated with a job and runs on a compute node.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudTask (string id, string commandline);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string commandline) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudTask.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (id As String, commandline As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.CloudTask : string * string -&gt; Microsoft.Azure.Batch.CloudTask" Usage="new Microsoft.Azure.Batch.CloudTask (id, commandline)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="commandline" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="2b8bb-103">タスクの ID です。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-103">The id of the task.</span></span></param>
        <param name="commandline"><span data-ttu-id="2b8bb-104">タスクのコマンドラインです。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-104">The command line of the task.</span></span></param>
        <summary>
            <span data-ttu-id="2b8bb-105"><see cref="T:Microsoft.Azure.Batch.CloudTask" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-105">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.CloudTask" /> class.</span></span>
            </summary>
        <remarks><span data-ttu-id="2b8bb-106">新しく作成された CloudTask は最初に、バッチ サービスでの任意のタスクに関連付けします。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-106">The newly created CloudTask is initially not associated with any task in the Batch service.</span></span>
            <span data-ttu-id="2b8bb-107">ジョブに関連付ける、Batch service に送信してを使用して<see cref="M:Microsoft.Azure.Batch.JobOperations.AddTaskAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />です。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-107">To associate it with a job and submit it to the Batch service, use <see cref="M:Microsoft.Azure.Batch.JobOperations.AddTaskAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="AffinityInformation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.AffinityInformation AffinityInformation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.AffinityInformation AffinityInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudTask.AffinityInformation" />
      <MemberSignature Language="VB.NET" Value="Public Property AffinityInformation As AffinityInformation" />
      <MemberSignature Language="F#" Value="member this.AffinityInformation : Microsoft.Azure.Batch.AffinityInformation with get, set" Usage="Microsoft.Azure.Batch.CloudTask.AffinityInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.AffinityInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2b8bb-108">取得またはタスクを開始するノードを選択する、Batch service によって使用できる局所性のヒントを設定します。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-108">Gets or sets a locality hint that can be used by the Batch service to select a node on which to start the task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationPackageReferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ApplicationPackageReference&gt; ApplicationPackageReferences { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.ApplicationPackageReference&gt; ApplicationPackageReferences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudTask.ApplicationPackageReferences" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationPackageReferences As IList(Of ApplicationPackageReference)" />
      <MemberSignature Language="F#" Value="member this.ApplicationPackageReferences : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ApplicationPackageReference&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudTask.ApplicationPackageReferences" />
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
            <span data-ttu-id="2b8bb-109">取得またはコマンドラインを実行する前に、コンピューティング ノードに、バッチ サービスを展開するアプリケーション パッケージの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-109">Gets or sets a list of application packages that the Batch service will deploy to the compute node before running the command line.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationTokenSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.AuthenticationTokenSettings AuthenticationTokenSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.AuthenticationTokenSettings AuthenticationTokenSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudTask.AuthenticationTokenSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationTokenSettings As AuthenticationTokenSettings" />
      <MemberSignature Language="F#" Value="member this.AuthenticationTokenSettings : Microsoft.Azure.Batch.AuthenticationTokenSettings with get, set" Usage="Microsoft.Azure.Batch.CloudTask.AuthenticationTokenSettings" />
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
            <span data-ttu-id="2b8bb-110">取得またはバッチ サービス操作を実行するタスクが使用できる認証トークンの設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-110">Gets or sets the settings for an authentication token that the task can use to perform Batch service operations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="2b8bb-111">このプロパティが設定されている場合、バッチ サービスは、アカウント アクセス キーを必要とせず、Batch service 操作を認証するために使用する認証トークンを使用してタスクを提供します。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-111">If this property is set, the Batch service provides the task with an authentication token which can be used to authenticate Batch service operations without requiring an account access key.</span></span> <span data-ttu-id="2b8bb-112">トークンが AZ_BATCH_AUTHENTICATION_TOKEN 環境変数を介して提供されます。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-112">The token is provided via the AZ_BATCH_AUTHENTICATION_TOKEN environment variable.</span></span> <span data-ttu-id="2b8bb-113">トークンを使用して、タスクが実行できる操作は、設定によって決まります。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-113">The operations that the task can carry out using the token depend on the settings.</span></span> <span data-ttu-id="2b8bb-114">たとえば、タスクは、ジョブを他のタスクを追加するか、または他のタスクのジョブの状態を確認するために、ジョブのアクセス許可を要求できます。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-114">For example, a task can request job permissions in order to add other tasks to the job, or check the status of the job or of other tasks.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CommandLine">
      <MemberSignature Language="C#" Value="public string CommandLine { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CommandLine" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudTask.CommandLine" />
      <MemberSignature Language="VB.NET" Value="Public Property CommandLine As String" />
      <MemberSignature Language="F#" Value="member this.CommandLine : string with get, set" Usage="Microsoft.Azure.Batch.CloudTask.CommandLine" />
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
            <span data-ttu-id="2b8bb-115">取得またはタスクのコマンドラインを設定します。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-115">Gets or sets the command line of the task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="2b8bb-116">コマンド ライン シェルが動作しないためできません利用して環境変数の展開などのシェルの機能の。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-116">The command line does not run under a shell, and therefore cannot take advantage of shell features such as environment variable expansion.</span></span> <span data-ttu-id="2b8bb-117">このような機能を利用する場合を呼び出すように、コマンド ライン シェルたとえば"cmd/c MyCommand"を使用して windows または"/bin/sh-c MyCommand"Linux でします。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-117">If you want to take advantage of such features, you should invoke the shell in the command line, for example using "cmd /c MyCommand" in Windows or "/bin/sh -c MyCommand" in Linux.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Commit">
      <MemberSignature Language="C#" Value="public void Commit (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Commit(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudTask.Commit(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Commit (Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.Commit : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudTask.Commit additionalBehaviors" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="2b8bb-118">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudTask.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-118">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudTask.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="2b8bb-119">これをすべて保留中の変更をコミット<see cref="T:Microsoft.Azure.Batch.CloudTask" />Azure Batch のサービスにします。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-119">Commits all pending changes to this <see cref="T:Microsoft.Azure.Batch.CloudTask" /> to the Azure Batch service.</span></span>
            </summary>
        <returns><span data-ttu-id="2b8bb-120">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-120">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="2b8bb-121">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-121">This is a blocking operation.</span></span> <span data-ttu-id="2b8bb-122">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.CloudTask.CommitAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-122">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.CloudTask.CommitAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CommitAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CommitAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CommitAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudTask.CommitAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CommitAsync : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudTask.CommitAsync (additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CloudTask/&lt;CommitAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="2b8bb-123">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudTask.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-123">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudTask.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="2b8bb-124">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-124">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="2b8bb-125">これをすべて保留中の変更をコミット<see cref="T:Microsoft.Azure.Batch.CloudTask" />Azure Batch のサービスにします。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-125">Commits all pending changes to this <see cref="T:Microsoft.Azure.Batch.CloudTask" /> to the Azure Batch service.</span></span>
            </summary>
        <returns><span data-ttu-id="2b8bb-126">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-126">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="2b8bb-127">コミット操作が非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-127">The commit operation runs asynchronously.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ComputeNodeInformation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.ComputeNodeInformation ComputeNodeInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.ComputeNodeInformation ComputeNodeInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudTask.ComputeNodeInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ComputeNodeInformation As ComputeNodeInformation" />
      <MemberSignature Language="F#" Value="member this.ComputeNodeInformation : Microsoft.Azure.Batch.ComputeNodeInformation" Usage="Microsoft.Azure.Batch.CloudTask.ComputeNodeInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.ComputeNodeInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2b8bb-128">タスクが実行したコンピューティング ノードに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-128">Gets information about the compute node on which the task ran.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Constraints">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.TaskConstraints Constraints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.TaskConstraints Constraints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudTask.Constraints" />
      <MemberSignature Language="VB.NET" Value="Public Property Constraints As TaskConstraints" />
      <MemberSignature Language="F#" Value="member this.Constraints : Microsoft.Azure.Batch.TaskConstraints with get, set" Usage="Microsoft.Azure.Batch.CloudTask.Constraints" />
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
            <span data-ttu-id="2b8bb-129">取得または、このタスクに適用される実行制約を設定します。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-129">Gets or sets the execution constraints that apply to this task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.TaskContainerSettings ContainerSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.TaskContainerSettings ContainerSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudTask.ContainerSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerSettings As TaskContainerSettings" />
      <MemberSignature Language="F#" Value="member this.ContainerSettings : Microsoft.Azure.Batch.TaskContainerSettings with get, set" Usage="Microsoft.Azure.Batch.CloudTask.ContainerSettings" />
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
            <span data-ttu-id="2b8bb-130">取得またはタスクを実行するコンテナーの設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-130">Gets or sets the settings for the container under which the task runs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="2b8bb-131">このタスクを実行しているプールがある場合<see cref="P:Microsoft.Azure.Batch.VirtualMachineConfiguration.ContainerConfiguration" />設定すると、この設定する必要がなくです。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-131">If the pool that will run this task has <see cref="P:Microsoft.Azure.Batch.VirtualMachineConfiguration.ContainerConfiguration" /> set, this must be set as well.</span></span> <span data-ttu-id="2b8bb-132">このタスクを実行しているプールがないかどうか<see cref="P:Microsoft.Azure.Batch.VirtualMachineConfiguration.ContainerConfiguration" />設定すると、この設定しないでください。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-132">If the pool that will run this task doesn't have <see cref="P:Microsoft.Azure.Batch.VirtualMachineConfiguration.ContainerConfiguration" /> set, this must not be set.</span></span> <span data-ttu-id="2b8bb-133">これを指定すると、AZ_BATCH_NODE_ROOT_DIR (ノードの Azure Batch のディレクトリのルート) の下のすべてのディレクトリに再帰的には、コンテナーにマップされて、すべてのタスクの環境変数が、コンテナーにマップおよびタスクのコマンドラインは、コンテナーで実行されます。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-133">When this is specified, all directories recursively below the AZ_BATCH_NODE_ROOT_DIR (the root of Azure Batch directories on the node) are mapped into the container, all task environment variables are mapped into the container, and the task command line is executed in the container.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreationTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudTask.CreationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreationTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.CloudTask.CreationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2b8bb-134">タスクの作成時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-134">Gets the creation time of the task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomBehaviors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudTask.CustomBehaviors" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomBehaviors As IList(Of BatchClientBehavior)" />
      <MemberSignature Language="F#" Value="member this.CustomBehaviors : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudTask.CustomBehaviors" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.IInheritedBehaviors.CustomBehaviors</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2b8bb-135">取得または設定の動作を変更またはこれを介して行われる、Batch service への要求をカスタマイズするリスト<see cref="T:Microsoft.Azure.Batch.CloudTask" />です。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-135">Gets or sets a list of behaviors that modify or customize requests to the Batch service made via this <see cref="T:Microsoft.Azure.Batch.CloudTask" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para><span data-ttu-id="2b8bb-136">これらの動作は、子オブジェクトによって継承されます。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-136">These behaviors are inherited by child objects.</span></span></para>
          <para><span data-ttu-id="2b8bb-137">変更は、コレクションの順序で適用されます。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-137">Modifications are applied in the order of the collection.</span></span> <span data-ttu-id="2b8bb-138">最後には、wins を記述します。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-138">The last write wins.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public void Delete (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Delete(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudTask.Delete(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Delete (Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.Delete : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudTask.Delete additionalBehaviors" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="2b8bb-139">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudTask.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-139">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudTask.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="2b8bb-140">この <see cref="T:Microsoft.Azure.Batch.CloudTask" /> を削除します。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-140">Deletes this <see cref="T:Microsoft.Azure.Batch.CloudTask" />.</span></span>
            </summary>
        <remarks><span data-ttu-id="2b8bb-141">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-141">This is a blocking operation.</span></span> <span data-ttu-id="2b8bb-142">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.CloudTask.DeleteAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-142">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.CloudTask.DeleteAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudTask.DeleteAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteAsync : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudTask.DeleteAsync (additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="2b8bb-143">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudTask.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-143">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudTask.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="2b8bb-144">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-144">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="2b8bb-145">この <see cref="T:Microsoft.Azure.Batch.CloudTask" /> を削除します。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-145">Deletes this <see cref="T:Microsoft.Azure.Batch.CloudTask" />.</span></span>
            </summary>
        <returns><span data-ttu-id="2b8bb-146">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-146">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="2b8bb-147">削除操作は非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-147">The delete operation runs asynchronously.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="DependsOn">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.TaskDependencies DependsOn { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.TaskDependencies DependsOn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudTask.DependsOn" />
      <MemberSignature Language="VB.NET" Value="Public Property DependsOn As TaskDependencies" />
      <MemberSignature Language="F#" Value="member this.DependsOn : Microsoft.Azure.Batch.TaskDependencies with get, set" Usage="Microsoft.Azure.Batch.CloudTask.DependsOn" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.TaskDependencies</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2b8bb-148">その他のタスクの設定を取得またはこの<see cref="T:Microsoft.Azure.Batch.CloudTask" />によって異なります。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-148">Gets or sets any other tasks that this <see cref="T:Microsoft.Azure.Batch.CloudTask" /> depends on.</span></span> <span data-ttu-id="2b8bb-149">すべての依存関係のあるタスクが正常に完了するまで、タスクをスケジュールしないされます。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-149">The task will not be scheduled until all depended-on tasks have completed successfully.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="2b8bb-150">ジョブを設定する必要があります<see cref="P:Microsoft.Azure.Batch.CloudJob.UsesTaskDependencies" />タスクの依存関係を使用するために true にします。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-150">The job must set <see cref="P:Microsoft.Azure.Batch.CloudJob.UsesTaskDependencies" /> to true in order to use task dependencies.</span></span> <span data-ttu-id="2b8bb-151">UsesTaskDependencies が false の場合は (既定)、エラーで失敗依存関係を持つタスクを追加します。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-151">If UsesTaskDependencies is false (the default), adding a task with dependencies will fail with an error.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudTask.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Batch.CloudTask.DisplayName" />
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
            <span data-ttu-id="2b8bb-152">取得またはタスクの表示名を設定します。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-152">Gets or sets the display name of the task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnvironmentSettings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.EnvironmentSetting&gt; EnvironmentSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.EnvironmentSetting&gt; EnvironmentSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudTask.EnvironmentSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property EnvironmentSettings As IList(Of EnvironmentSetting)" />
      <MemberSignature Language="F#" Value="member this.EnvironmentSettings : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.EnvironmentSetting&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudTask.EnvironmentSettings" />
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
            <span data-ttu-id="2b8bb-153">取得またはタスクの環境変数設定の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-153">Gets or sets a list of environment variable settings for the task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudTask.ETag" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string" Usage="Microsoft.Azure.Batch.CloudTask.ETag" />
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
            <span data-ttu-id="2b8bb-154">タスクの ETag を取得します。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-154">Gets the ETag for the task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecutionInformation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.TaskExecutionInformation ExecutionInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.TaskExecutionInformation ExecutionInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudTask.ExecutionInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExecutionInformation As TaskExecutionInformation" />
      <MemberSignature Language="F#" Value="member this.ExecutionInformation : Microsoft.Azure.Batch.TaskExecutionInformation" Usage="Microsoft.Azure.Batch.CloudTask.ExecutionInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.TaskExecutionInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2b8bb-155">タスクの実行情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-155">Gets the execution information for the task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExitConditions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.ExitConditions ExitConditions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.ExitConditions ExitConditions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudTask.ExitConditions" />
      <MemberSignature Language="VB.NET" Value="Public Property ExitConditions As ExitConditions" />
      <MemberSignature Language="F#" Value="member this.ExitConditions : Microsoft.Azure.Batch.ExitConditions with get, set" Usage="Microsoft.Azure.Batch.CloudTask.ExitConditions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.ExitConditions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2b8bb-156">取得または設定、タスクが完了したときに、バッチ サービスがどのように対処する必要がありますか。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-156">Gets or sets how the Batch service should respond when the task completes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FilesToStage">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.FileStaging.IFileStagingProvider&gt; FilesToStage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.FileStaging.IFileStagingProvider&gt; FilesToStage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudTask.FilesToStage" />
      <MemberSignature Language="VB.NET" Value="Public Property FilesToStage As IList(Of IFileStagingProvider)" />
      <MemberSignature Language="F#" Value="member this.FilesToStage : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.FileStaging.IFileStagingProvider&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudTask.FilesToStage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.FileStaging.IFileStagingProvider&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2b8bb-157">取得またはタスクをステージングするファイルの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-157">Gets or sets a list of files to be staged for the task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNodeFile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.NodeFile GetNodeFile (string filePath, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.NodeFile GetNodeFile(string filePath, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudTask.GetNodeFile(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNodeFile (filePath As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null) As NodeFile" />
      <MemberSignature Language="F#" Value="member this.GetNodeFile : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.NodeFile" Usage="cloudTask.GetNodeFile (filePath, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.NodeFile</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="filePath"><span data-ttu-id="2b8bb-158">取得するファイルのパス。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-158">The path of the file to retrieve.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="2b8bb-159">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudTask.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-159">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudTask.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="2b8bb-160">指定された取得<see cref="T:Microsoft.Azure.Batch.NodeFile" />から、<see cref="T:Microsoft.Azure.Batch.CloudTask" />のコンピューティング ノードでディレクトリ。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-160">Gets the specified <see cref="T:Microsoft.Azure.Batch.NodeFile" /> from the <see cref="T:Microsoft.Azure.Batch.CloudTask" />'s directory on its compute node.</span></span>
            </summary>
        <returns><span data-ttu-id="2b8bb-161">A<see cref="T:Microsoft.Azure.Batch.NodeFile" />を表す、指定したファイルです。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-161">A <see cref="T:Microsoft.Azure.Batch.NodeFile" /> representing the specified file.</span></span></returns>
        <remarks><span data-ttu-id="2b8bb-162">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-162">This is a blocking operation.</span></span> <span data-ttu-id="2b8bb-163">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.CloudTask.GetNodeFileAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-163">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.CloudTask.GetNodeFileAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNodeFileAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.NodeFile&gt; GetNodeFileAsync (string filePath, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.NodeFile&gt; GetNodeFileAsync(string filePath, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudTask.GetNodeFileAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetNodeFileAsync : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.NodeFile&gt;" Usage="cloudTask.GetNodeFileAsync (filePath, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.NodeFile&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="filePath"><span data-ttu-id="2b8bb-164">取得するファイルのパス。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-164">The path of the file to retrieve.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="2b8bb-165">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudTask.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-165">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudTask.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="2b8bb-166">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-166">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="2b8bb-167">指定された取得<see cref="T:Microsoft.Azure.Batch.NodeFile" />から、<see cref="T:Microsoft.Azure.Batch.CloudTask" />のコンピューティング ノードでディレクトリ。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-167">Gets the specified <see cref="T:Microsoft.Azure.Batch.NodeFile" /> from the <see cref="T:Microsoft.Azure.Batch.CloudTask" />'s directory on its compute node.</span></span>
            </summary>
        <returns><span data-ttu-id="2b8bb-168">A<see cref="T:Microsoft.Azure.Batch.NodeFile" />を表す、指定したファイルです。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-168">A <see cref="T:Microsoft.Azure.Batch.NodeFile" /> representing the specified file.</span></span></returns>
        <remarks><span data-ttu-id="2b8bb-169">ファイルの取得操作は非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-169">The get file operation runs asynchronously.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudTask.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Batch.CloudTask.Id" />
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
            <span data-ttu-id="2b8bb-170">取得またはタスクの id を設定します。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-170">Gets or sets the id of the task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModified">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastModified { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastModified" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudTask.LastModified" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastModified As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastModified : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.CloudTask.LastModified" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2b8bb-171">タスクの最終更新時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-171">Gets the last modified time of the task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNodeFiles">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.NodeFile&gt; ListNodeFiles (Nullable&lt;bool&gt; recursive = null, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;class Microsoft.Azure.Batch.NodeFile&gt; ListNodeFiles(valuetype System.Nullable`1&lt;bool&gt; recursive, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudTask.ListNodeFiles(System.Nullable{System.Boolean},Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ListNodeFiles : Nullable&lt;bool&gt; * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.NodeFile&gt;" Usage="cloudTask.ListNodeFiles (recursive, detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.NodeFile&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="recursive"><span data-ttu-id="2b8bb-172">True の場合は、タスクのすべてのファイルの再帰的な一覧を実行します。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-172">If true, performs a recursive list of all files of the task.</span></span> <span data-ttu-id="2b8bb-173">False の場合は、タスクのルート ディレクトリにファイルのみを返します。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-173">If false, returns only the files in the root task directory.</span></span></param>
        <param name="detailLevel"><span data-ttu-id="2b8bb-174">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />一覧をフィルター処理し、サービスから取得するプロパティを制御するために使用します。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-174">A <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> used for filtering the list and for controlling which properties are retrieved from the service.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="2b8bb-175">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudTask.CustomBehaviors" />と<paramref name="detailLevel" />です。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-175">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudTask.CustomBehaviors" /> and <paramref name="detailLevel" />.</span></span></param>
        <summary>
            <span data-ttu-id="2b8bb-176">内のファイルを列挙、<see cref="T:Microsoft.Azure.Batch.CloudTask" />のコンピューティング ノードでディレクトリ。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-176">Enumerates the files in the <see cref="T:Microsoft.Azure.Batch.CloudTask" />'s directory on its compute node.</span></span>
            </summary>
        <returns><span data-ttu-id="2b8bb-177"><see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />ファイルを列挙する非同期的または同期的に使用できます。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-177">An <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> that can be used to enumerate files asynchronously or synchronously.</span></span></returns>
        <remarks><span data-ttu-id="2b8bb-178">このメソッドがすぐに戻るファイル データは、コレクションが列挙される場合にのみ、バッチ サービスから取得されます。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-178">This method returns immediately; the file data is retrieved from the Batch service only when the collection is enumerated.</span></span>
            <span data-ttu-id="2b8bb-179">検索は非アトミックなです。ファイル データは、コレクションの列挙中にページで取得されます。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-179">Retrieval is non-atomic; file data is retrieved in pages during enumeration of the collection.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSubtasks">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.SubtaskInformation&gt; ListSubtasks (Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;class Microsoft.Azure.Batch.SubtaskInformation&gt; ListSubtasks(class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudTask.ListSubtasks(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ListSubtasks : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.SubtaskInformation&gt;" Usage="cloudTask.ListSubtasks (detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.SubtaskInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="detailLevel"><span data-ttu-id="2b8bb-180">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />一覧をフィルター処理し、サービスから取得するプロパティを制御するために使用します。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-180">A <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> used for filtering the list and for controlling which properties are retrieved from the service.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="2b8bb-181">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudTask.CustomBehaviors" />と<paramref name="detailLevel" />です。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-181">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudTask.CustomBehaviors" /> and <paramref name="detailLevel" />.</span></span></param>
        <summary>
            <span data-ttu-id="2b8bb-182">複数のインスタンスのサブタスクを列挙<see cref="T:Microsoft.Azure.Batch.CloudTask" />です。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-182">Enumerates the subtasks of the multi-instance <see cref="T:Microsoft.Azure.Batch.CloudTask" />.</span></span>
            </summary>
        <returns><span data-ttu-id="2b8bb-183"><see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />ファイルを列挙する非同期的または同期的に使用できます。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-183">An <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> that can be used to enumerate files asynchronously or synchronously.</span></span></returns>
        <remarks><span data-ttu-id="2b8bb-184">このメソッドがすぐに戻るファイル データは、コレクションが列挙される場合にのみ、バッチ サービスから取得されます。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-184">This method returns immediately; the file data is retrieved from the Batch service only when the collection is enumerated.</span></span>
            <span data-ttu-id="2b8bb-185">検索は非アトミックなです。ファイル データは、コレクションの列挙中にページで取得されます。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-185">Retrieval is non-atomic; file data is retrieved in pages during enumeration of the collection.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="MultiInstanceSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.MultiInstanceSettings MultiInstanceSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.MultiInstanceSettings MultiInstanceSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudTask.MultiInstanceSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property MultiInstanceSettings As MultiInstanceSettings" />
      <MemberSignature Language="F#" Value="member this.MultiInstanceSettings : Microsoft.Azure.Batch.MultiInstanceSettings with get, set" Usage="Microsoft.Azure.Batch.CloudTask.MultiInstanceSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.MultiInstanceSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2b8bb-186">取得または複数のインスタンスのタスクを実行する方法に関する情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-186">Gets or sets information about how to run the multi-instance task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutputFiles">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.OutputFile&gt; OutputFiles { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.OutputFile&gt; OutputFiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudTask.OutputFiles" />
      <MemberSignature Language="VB.NET" Value="Public Property OutputFiles As IList(Of OutputFile)" />
      <MemberSignature Language="F#" Value="member this.OutputFiles : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.OutputFile&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudTask.OutputFiles" />
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
            <span data-ttu-id="2b8bb-187">取得または、Batch service は、コマンドラインの実行後にコンピューティング ノードからアップロードするファイルの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-187">Gets or sets a list of files that the Batch service will upload from the compute node after running the command line.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PreviousState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.TaskState&gt; PreviousState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.TaskState&gt; PreviousState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudTask.PreviousState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PreviousState As Nullable(Of TaskState)" />
      <MemberSignature Language="F#" Value="member this.PreviousState : Nullable&lt;Microsoft.Azure.Batch.Common.TaskState&gt;" Usage="Microsoft.Azure.Batch.CloudTask.PreviousState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.TaskState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2b8bb-188">タスクの以前の状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-188">Gets the previous state of the task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="2b8bb-189">タスクが、初期で場合<see cref="F:Microsoft.Azure.Batch.Common.TaskState.Active" />状態、PreviousState プロパティが定義されていません。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-189">If the task is in its initial <see cref="F:Microsoft.Azure.Batch.Common.TaskState.Active" /> state, the PreviousState property is not defined.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PreviousStateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; PreviousStateTransitionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; PreviousStateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudTask.PreviousStateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PreviousStateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.PreviousStateTransitionTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.CloudTask.PreviousStateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2b8bb-190">タスクが前の状態を入力する時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-190">Gets the time at which the task entered its previous state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="2b8bb-191">タスクが、初期で場合<see cref="F:Microsoft.Azure.Batch.Common.TaskState.Active" />状態、PreviousStateTransitionTime プロパティが定義されていません。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-191">If the task is in its initial <see cref="F:Microsoft.Azure.Batch.Common.TaskState.Active" /> state, the PreviousStateTransitionTime property is not defined.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Reactivate">
      <MemberSignature Language="C#" Value="public void Reactivate (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Reactivate(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudTask.Reactivate(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Reactivate (Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.Reactivate : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudTask.Reactivate additionalBehaviors" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="2b8bb-192">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudTask.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-192">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudTask.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="2b8bb-193">これを再アクティブ化<see cref="T:Microsoft.Azure.Batch.CloudTask" />での再試行回数が使い果たされた場合でも、もう一度実行を許可します。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-193">Reactivates this <see cref="T:Microsoft.Azure.Batch.CloudTask" />, allowing it to run again even if its retry count has been exhausted.</span></span>
            </summary>
        <remarks>
          <para>
            <span data-ttu-id="2b8bb-194">再アクティブ化では、タスクがその最大再試行回数まで再試行の対象となります。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-194">Reactivation makes a task eligible to be retried again up to its maximum retry count.</span></span>
            </para>
          <para>
            <span data-ttu-id="2b8bb-195">この操作は完了していない、または正常に (終了コード 0) の以前に完了したタスクを失敗します。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-195">This operation will fail for tasks that are not completed or that previously completed successfully (with an exit code of 0).</span></span>
            <span data-ttu-id="2b8bb-196">さらは失敗しますが、ジョブの場合、<see cref="F:Microsoft.Azure.Batch.Common.JobState.Completed" />または<see cref="F:Microsoft.Azure.Batch.Common.JobState.Terminating" />または<see cref="F:Microsoft.Azure.Batch.Common.JobState.Deleting" />状態です。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-196">Additionally, this will fail if the job is in the <see cref="F:Microsoft.Azure.Batch.Common.JobState.Completed" /> or <see cref="F:Microsoft.Azure.Batch.Common.JobState.Terminating" /> or <see cref="F:Microsoft.Azure.Batch.Common.JobState.Deleting" /> state.</span></span>
            </para>
          <para>
            <span data-ttu-id="2b8bb-197">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-197">This is a blocking operation.</span></span> <span data-ttu-id="2b8bb-198">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.CloudTask.ReactivateAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-198">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.CloudTask.ReactivateAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReactivateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ReactivateAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ReactivateAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudTask.ReactivateAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ReactivateAsync : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudTask.ReactivateAsync (additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="2b8bb-199">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudTask.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-199">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudTask.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="2b8bb-200">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-200">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="2b8bb-201">これを再アクティブ化<see cref="T:Microsoft.Azure.Batch.CloudTask" />での再試行回数が使い果たされた場合でも、もう一度実行を許可します。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-201">Reactivates this <see cref="T:Microsoft.Azure.Batch.CloudTask" />, allowing it to run again even if its retry count has been exhausted.</span></span>
            </summary>
        <returns><span data-ttu-id="2b8bb-202">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-202">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="2b8bb-203">再アクティブ化では、タスクがその最大再試行回数まで再試行の対象となります。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-203">Reactivation makes a task eligible to be retried again up to its maximum retry count.</span></span>
            </para>
          <para>
            <span data-ttu-id="2b8bb-204">この操作は完了していない、または正常に (終了コード 0) の以前に完了したタスクを失敗します。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-204">This operation will fail for tasks that are not completed or that previously completed successfully (with an exit code of 0).</span></span>
            <span data-ttu-id="2b8bb-205">さらは失敗しますが、ジョブの場合、<see cref="F:Microsoft.Azure.Batch.Common.JobState.Completed" />または<see cref="F:Microsoft.Azure.Batch.Common.JobState.Terminating" />または<see cref="F:Microsoft.Azure.Batch.Common.JobState.Deleting" />状態です。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-205">Additionally, this will fail if the job is in the <see cref="F:Microsoft.Azure.Batch.Common.JobState.Completed" /> or <see cref="F:Microsoft.Azure.Batch.Common.JobState.Terminating" /> or <see cref="F:Microsoft.Azure.Batch.Common.JobState.Deleting" /> state.</span></span>
            </para>
          <para>
            <span data-ttu-id="2b8bb-206">再アクティブ化操作が非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-206">The reactivate operation runs asynchronously.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Refresh">
      <MemberSignature Language="C#" Value="public void Refresh (Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Refresh(class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudTask.Refresh(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="abstract member Refresh : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit&#xA;override this.Refresh : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudTask.Refresh (detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Batch.IRefreshable.Refresh(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="detailLevel"><span data-ttu-id="2b8bb-207">最新の更新の詳細レベルです。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-207">The detail level for the refresh.</span></span>  <span data-ttu-id="2b8bb-208">詳細レベルを省略する場合、<see cref="P:Microsoft.Azure.Batch.CloudTask.Id" />プロパティを指定すると、更新は失敗します。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-208">If a detail level which omits the <see cref="P:Microsoft.Azure.Batch.CloudTask.Id" /> property is specified, refresh will fail.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="2b8bb-209">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudTask.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-209">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudTask.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="2b8bb-210">現在の更新<see cref="T:Microsoft.Azure.Batch.CloudTask" />です。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-210">Refreshes the current <see cref="T:Microsoft.Azure.Batch.CloudTask" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RefreshAsync (Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RefreshAsync(class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudTask.RefreshAsync(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RefreshAsync : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.RefreshAsync : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudTask.RefreshAsync (detailLevel, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Batch.IRefreshable.RefreshAsync(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CloudTask/&lt;RefreshAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="detailLevel"><span data-ttu-id="2b8bb-211">最新の更新の詳細レベルです。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-211">The detail level for the refresh.</span></span>  <span data-ttu-id="2b8bb-212">詳細レベルを省略する場合、<see cref="P:Microsoft.Azure.Batch.CloudTask.Id" />プロパティを指定すると、更新は失敗します。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-212">If a detail level which omits the <see cref="P:Microsoft.Azure.Batch.CloudTask.Id" /> property is specified, refresh will fail.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="2b8bb-213">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudTask.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-213">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudTask.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="2b8bb-214">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-214">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="2b8bb-215">現在の更新<see cref="T:Microsoft.Azure.Batch.CloudTask" />です。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-215">Refreshes the current <see cref="T:Microsoft.Azure.Batch.CloudTask" />.</span></span>
            </summary>
        <returns><span data-ttu-id="2b8bb-216">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-216">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceFiles">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ResourceFile&gt; ResourceFiles { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.ResourceFile&gt; ResourceFiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudTask.ResourceFiles" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceFiles As IList(Of ResourceFile)" />
      <MemberSignature Language="F#" Value="member this.ResourceFiles : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ResourceFile&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudTask.ResourceFiles" />
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
            <span data-ttu-id="2b8bb-217">取得またはコマンドラインを実行する前に、バッチ サービスをコンピューティング ノードにダウンロードするファイルの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-217">Gets or sets a list of files that the Batch service will download to the compute node before running the command line.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StageFiles">
      <MemberSignature Language="C#" Value="public System.Collections.Concurrent.ConcurrentDictionary&lt;Type,Microsoft.Azure.Batch.IFileStagingArtifact&gt; StageFiles ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Concurrent.ConcurrentDictionary`2&lt;class System.Type, class Microsoft.Azure.Batch.IFileStagingArtifact&gt; StageFiles() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudTask.StageFiles" />
      <MemberSignature Language="VB.NET" Value="Public Function StageFiles () As ConcurrentDictionary(Of Type, IFileStagingArtifact)" />
      <MemberSignature Language="F#" Value="member this.StageFiles : unit -&gt; System.Collections.Concurrent.ConcurrentDictionary&lt;Type, Microsoft.Azure.Batch.IFileStagingArtifact&gt;" Usage="cloudTask.StageFiles " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Concurrent.ConcurrentDictionary&lt;System.Type,Microsoft.Azure.Batch.IFileStagingArtifact&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2b8bb-218">示されているファイルがステージング、 <see cref="P:Microsoft.Azure.Batch.CloudTask.FilesToStage" />  ボックスの一覧です。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-218">Stages the files listed in the <see cref="P:Microsoft.Azure.Batch.CloudTask.FilesToStage" /> list.</span></span>
            </summary>
        <returns><span data-ttu-id="2b8bb-219">ステージング処理ファイルに関する情報のコレクション。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-219">A collection of information about the file staging process.</span></span>
            <span data-ttu-id="2b8bb-220">詳細については、「<see cref="T:Microsoft.Azure.Batch.IFileStagingArtifact" />」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-220">For more information see <see cref="T:Microsoft.Azure.Batch.IFileStagingArtifact" />.</span></span></returns>
        <remarks><span data-ttu-id="2b8bb-221">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-221">This is a blocking operation.</span></span> <span data-ttu-id="2b8bb-222">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.CloudTask.StageFilesAsync(System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact})" />です。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-222">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.CloudTask.StageFilesAsync(System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact})" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="StageFilesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StageFilesAsync (System.Collections.Concurrent.ConcurrentDictionary&lt;Type,Microsoft.Azure.Batch.IFileStagingArtifact&gt; allFileStagingArtifacts = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StageFilesAsync(class System.Collections.Concurrent.ConcurrentDictionary`2&lt;class System.Type, class Microsoft.Azure.Batch.IFileStagingArtifact&gt; allFileStagingArtifacts) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudTask.StageFilesAsync(System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact})" />
      <MemberSignature Language="VB.NET" Value="Public Function StageFilesAsync (Optional allFileStagingArtifacts As ConcurrentDictionary(Of Type, IFileStagingArtifact) = null) As Task" />
      <MemberSignature Language="F#" Value="member this.StageFilesAsync : System.Collections.Concurrent.ConcurrentDictionary&lt;Type, Microsoft.Azure.Batch.IFileStagingArtifact&gt; -&gt; System.Threading.Tasks.Task" Usage="cloudTask.StageFilesAsync allFileStagingArtifacts" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CloudTask/&lt;StageFilesAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="allFileStagingArtifacts" Type="System.Collections.Concurrent.ConcurrentDictionary&lt;System.Type,Microsoft.Azure.Batch.IFileStagingArtifact&gt;" />
      </Parameters>
      <Docs>
        <param name="allFileStagingArtifacts"><span data-ttu-id="2b8bb-223">カスタマイズし、ステージング処理ファイルに関する情報が表示される省略可能なコレクションです。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-223">An optional collection to customize and receive information about the file staging process.</span></span>
            <span data-ttu-id="2b8bb-224">詳細については、「<see cref="T:Microsoft.Azure.Batch.IFileStagingArtifact" />」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-224">For more information see <see cref="T:Microsoft.Azure.Batch.IFileStagingArtifact" />.</span></span></param>
        <summary>
            <span data-ttu-id="2b8bb-225">示されているファイルがステージング、 <see cref="P:Microsoft.Azure.Batch.CloudTask.FilesToStage" />  ボックスの一覧です。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-225">Stages the files listed in the <see cref="P:Microsoft.Azure.Batch.CloudTask.FilesToStage" /> list.</span></span>
            </summary>
        <returns><span data-ttu-id="2b8bb-226">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-226">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="2b8bb-227">ステージングの操作は非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-227">The staging operation runs asynchronously.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.TaskState&gt; State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.TaskState&gt; State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudTask.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As Nullable(Of TaskState)" />
      <MemberSignature Language="F#" Value="member this.State : Nullable&lt;Microsoft.Azure.Batch.Common.TaskState&gt;" Usage="Microsoft.Azure.Batch.CloudTask.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.TaskState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2b8bb-228">タスクの現在の状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-228">Gets the current state of the task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StateTransitionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudTask.StateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StateTransitionTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.CloudTask.StateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2b8bb-229">タスクが、現在の状態を入力する時間を取得します。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-229">Gets the time at which the task entered its current state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Statistics">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.TaskStatistics Statistics { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.TaskStatistics Statistics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudTask.Statistics" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Statistics As TaskStatistics" />
      <MemberSignature Language="F#" Value="member this.Statistics : Microsoft.Azure.Batch.TaskStatistics" Usage="Microsoft.Azure.Batch.CloudTask.Statistics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.TaskStatistics</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2b8bb-230">タスクのリソース使用状況の統計を取得します。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-230">Gets resource usage statistics for the task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="2b8bb-231">場合にのみ、このプロパティが設定されます、<see cref="T:Microsoft.Azure.Batch.CloudTask" />で取得した、 <see cref="P:Microsoft.Azure.Batch.ODATADetailLevel.ExpandClause" /> 'stats' 属性を含むそれ以外の場合は null を返します。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-231">This property is populated only if the <see cref="T:Microsoft.Azure.Batch.CloudTask" /> was retrieved with an <see cref="P:Microsoft.Azure.Batch.ODATADetailLevel.ExpandClause" /> including the 'stats' attribute; otherwise it is null.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Terminate">
      <MemberSignature Language="C#" Value="public void Terminate (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Terminate(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudTask.Terminate(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Terminate (Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.Terminate : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudTask.Terminate additionalBehaviors" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="2b8bb-232">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudTask.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-232">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudTask.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="2b8bb-233">これが終了<see cref="T:Microsoft.Azure.Batch.CloudTask" />、完了済みとしてマークすることです。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-233">Terminates this <see cref="T:Microsoft.Azure.Batch.CloudTask" />, marking it as completed.</span></span>
            </summary>
        <remarks><span data-ttu-id="2b8bb-234">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-234">This is a blocking operation.</span></span> <span data-ttu-id="2b8bb-235">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.CloudTask.TerminateAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-235">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.CloudTask.TerminateAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="TerminateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task TerminateAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task TerminateAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudTask.TerminateAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.TerminateAsync : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudTask.TerminateAsync (additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="2b8bb-236">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudTask.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-236">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudTask.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="2b8bb-237">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-237">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="2b8bb-238">これが終了<see cref="T:Microsoft.Azure.Batch.CloudTask" />、完了済みとしてマークすることです。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-238">Terminates this <see cref="T:Microsoft.Azure.Batch.CloudTask" />, marking it as completed.</span></span>
            </summary>
        <returns><span data-ttu-id="2b8bb-239">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-239">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="2b8bb-240">終了操作は非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-240">The terminate operation runs asynchronously.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudTask.Url" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string" Usage="Microsoft.Azure.Batch.CloudTask.Url" />
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
            <span data-ttu-id="2b8bb-241">タスクの URL を取得します。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-241">Gets the URL of the task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserIdentity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.UserIdentity UserIdentity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.UserIdentity UserIdentity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudTask.UserIdentity" />
      <MemberSignature Language="VB.NET" Value="Public Property UserIdentity As UserIdentity" />
      <MemberSignature Language="F#" Value="member this.UserIdentity : Microsoft.Azure.Batch.UserIdentity with get, set" Usage="Microsoft.Azure.Batch.CloudTask.UserIdentity" />
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
            <span data-ttu-id="2b8bb-242">取得またはタスクを実行するユーザー id を設定します。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-242">Gets or sets the user identity under which the task runs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="2b8bb-243">省略した場合、そのタスクは、タスクに一意の非管理者のユーザーとして実行されます。</span><span class="sxs-lookup"><span data-stu-id="2b8bb-243">If omitted, the task runs as a non-administrative user unique to the task.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>