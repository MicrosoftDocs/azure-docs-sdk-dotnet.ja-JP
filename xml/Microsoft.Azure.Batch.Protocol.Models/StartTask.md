<Type Name="StartTask" FullName="Microsoft.Azure.Batch.Protocol.Models.StartTask">
  <TypeSignature Language="C#" Value="public class StartTask" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StartTask extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.StartTask" />
  <TypeSignature Language="VB.NET" Value="Public Class StartTask" />
  <TypeSignature Language="F#" Value="type StartTask = class" />
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
            <span data-ttu-id="6b7c7-101">コンピューティング ノードがプールを Azure Batch サービスを参加させるときや、コンピューティング ノードが再起動または再イメージ化されるときに実行されるタスクです。</span><span class="sxs-lookup"><span data-stu-id="6b7c7-101">A task which is run when a compute node joins a pool in the Azure Batch service, or when the compute node is rebooted or reimaged.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StartTask ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.StartTask.#ctor" />
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
            <span data-ttu-id="6b7c7-102">StartTask クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6b7c7-102">Initializes a new instance of the StartTask class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StartTask (string commandLine, Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings containerSettings = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; resourceFiles = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; environmentSettings = null, Microsoft.Azure.Batch.Protocol.Models.UserIdentity userIdentity = null, Nullable&lt;int&gt; maxTaskRetryCount = null, Nullable&lt;bool&gt; waitForSuccess = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string commandLine, class Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings containerSettings, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; resourceFiles, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; environmentSettings, class Microsoft.Azure.Batch.Protocol.Models.UserIdentity userIdentity, valuetype System.Nullable`1&lt;int32&gt; maxTaskRetryCount, valuetype System.Nullable`1&lt;bool&gt; waitForSuccess) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.StartTask.#ctor(System.String,Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.ResourceFile},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting},Microsoft.Azure.Batch.Protocol.Models.UserIdentity,System.Nullable{System.Int32},System.Nullable{System.Boolean})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.StartTask : string * Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; * Microsoft.Azure.Batch.Protocol.Models.UserIdentity * Nullable&lt;int&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.StartTask" Usage="new Microsoft.Azure.Batch.Protocol.Models.StartTask (commandLine, containerSettings, resourceFiles, environmentSettings, userIdentity, maxTaskRetryCount, waitForSuccess)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="commandLine" Type="System.String" />
        <Parameter Name="containerSettings" Type="Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings" />
        <Parameter Name="resourceFiles" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt;" />
        <Parameter Name="environmentSettings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt;" />
        <Parameter Name="userIdentity" Type="Microsoft.Azure.Batch.Protocol.Models.UserIdentity" />
        <Parameter Name="maxTaskRetryCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="waitForSuccess" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="commandLine"><span data-ttu-id="6b7c7-103">開始タスクのコマンドラインです。</span><span class="sxs-lookup"><span data-stu-id="6b7c7-103">The command line of the start task.</span></span></param>
        <param name="containerSettings"><span data-ttu-id="6b7c7-104">開始タスクを実行するコンテナーの設定。</span><span class="sxs-lookup"><span data-stu-id="6b7c7-104">The settings for the container under which the start task runs.</span></span></param>
        <param name="resourceFiles"><span data-ttu-id="6b7c7-105">バッチ サービスはコマンドラインを実行する前にコンピューティング ノードにダウンロードされるファイルの一覧。</span><span class="sxs-lookup"><span data-stu-id="6b7c7-105">A list of files that the Batch service will download to the compute node before running the command line.</span></span></param>
        <param name="environmentSettings"><span data-ttu-id="6b7c7-106">開始タスクの環境変数設定の一覧。</span><span class="sxs-lookup"><span data-stu-id="6b7c7-106">A list of environment variable settings for the start task.</span></span></param>
        <param name="userIdentity"><span data-ttu-id="6b7c7-107">開始タスクを実行するユーザー id。</span><span class="sxs-lookup"><span data-stu-id="6b7c7-107">The user identity under which the start task runs.</span></span></param>
        <param name="maxTaskRetryCount"><span data-ttu-id="6b7c7-108">タスクを再試行できる最大回数。</span><span class="sxs-lookup"><span data-stu-id="6b7c7-108">The maximum number of times the task may be retried.</span></span></param>
        <param name="waitForSuccess"><span data-ttu-id="6b7c7-109">バッチ サービスは、開始タスクが正常に完了待機する必要があるかどうか (つまり、終了コード 0 で終了する)、コンピューティング ノード上のすべてのタスクをスケジュールする前にします。</span><span class="sxs-lookup"><span data-stu-id="6b7c7-109">Whether the Batch service should wait for the start task to complete successfully (that is, to exit with exit code 0) before scheduling any tasks on the compute node.</span></span></param>
        <summary>
            <span data-ttu-id="6b7c7-110">StartTask クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6b7c7-110">Initializes a new instance of the StartTask class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommandLine">
      <MemberSignature Language="C#" Value="public string CommandLine { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CommandLine" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.StartTask.CommandLine" />
      <MemberSignature Language="VB.NET" Value="Public Property CommandLine As String" />
      <MemberSignature Language="F#" Value="member this.CommandLine : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.StartTask.CommandLine" />
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
            <span data-ttu-id="6b7c7-111">取得または開始タスクのコマンドラインを設定します。</span><span class="sxs-lookup"><span data-stu-id="6b7c7-111">Gets or sets the command line of the start task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="6b7c7-112">コマンド ライン シェルが動作しないためできません利用して環境変数の展開などのシェルの機能の。</span><span class="sxs-lookup"><span data-stu-id="6b7c7-112">The command line does not run under a shell, and therefore cannot take advantage of shell features such as environment variable expansion.</span></span> <span data-ttu-id="6b7c7-113">このような機能を利用する場合を呼び出すように、コマンド ライン シェルたとえば"cmd/c MyCommand"を使用して windows または"/bin/sh-c MyCommand"Linux でします。</span><span class="sxs-lookup"><span data-stu-id="6b7c7-113">If you want to take advantage of such features, you should invoke the shell in the command line, for example using "cmd /c MyCommand" in Windows or "/bin/sh -c MyCommand" in Linux.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings ContainerSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings ContainerSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.StartTask.ContainerSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerSettings As TaskContainerSettings" />
      <MemberSignature Language="F#" Value="member this.ContainerSettings : Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.StartTask.ContainerSettings" />
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
            <span data-ttu-id="6b7c7-114">取得または開始タスクを実行するコンテナーの設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="6b7c7-114">Gets or sets the settings for the container under which the start task runs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="6b7c7-115">これを指定すると、AZ_BATCH_NODE_ROOT_DIR (ノードの Azure Batch のディレクトリのルート) の下のすべてのディレクトリに再帰的には、コンテナーにマップされて、すべてのタスクの環境変数が、コンテナーにマップおよびタスクのコマンドラインは、コンテナーで実行されます。</span><span class="sxs-lookup"><span data-stu-id="6b7c7-115">When this is specified, all directories recursively below the AZ_BATCH_NODE_ROOT_DIR (the root of Azure Batch directories on the node) are mapped into the container, all task environment variables are mapped into the container, and the task command line is executed in the container.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnvironmentSettings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; EnvironmentSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; EnvironmentSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.StartTask.EnvironmentSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property EnvironmentSettings As IList(Of EnvironmentSetting)" />
      <MemberSignature Language="F#" Value="member this.EnvironmentSettings : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.StartTask.EnvironmentSettings" />
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
            <span data-ttu-id="6b7c7-116">取得または開始タスクの環境変数設定の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="6b7c7-116">Gets or sets a list of environment variable settings for the start task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxTaskRetryCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxTaskRetryCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxTaskRetryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.StartTask.MaxTaskRetryCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxTaskRetryCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxTaskRetryCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.StartTask.MaxTaskRetryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxTaskRetryCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6b7c7-117">取得または、タスクが再試行される最大回数を設定します。</span><span class="sxs-lookup"><span data-stu-id="6b7c7-117">Gets or sets the maximum number of times the task may be retried.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="6b7c7-118">Batch サービスは、終了コードが 0 以外の場合にタスクを再試行します。</span><span class="sxs-lookup"><span data-stu-id="6b7c7-118">The Batch service retries a task if its exit code is nonzero.</span></span> <span data-ttu-id="6b7c7-119">この値によって再試行の回数が限定されますのでご注意ください。</span><span class="sxs-lookup"><span data-stu-id="6b7c7-119">Note that this value specifically controls the number of retries.</span></span> <span data-ttu-id="6b7c7-120">Batch サービスはタスクを 1 回試行してから、上限に達するまで再試行できます。</span><span class="sxs-lookup"><span data-stu-id="6b7c7-120">The Batch service will try the task once, and may then retry up to this limit.</span></span> <span data-ttu-id="6b7c7-121">たとえば、最大再試行回数が 3 の場合は、バッチを試みるタスクには最大 4 倍 (最初の試行が 1 回と 3 回)。</span><span class="sxs-lookup"><span data-stu-id="6b7c7-121">For example, if the maximum retry count is 3, Batch tries the task up to 4 times (one initial try and 3 retries).</span></span> <span data-ttu-id="6b7c7-122">最大再試行回数が 0 の場合、Batch service は、タスクを再試行しません。</span><span class="sxs-lookup"><span data-stu-id="6b7c7-122">If the maximum retry count is 0, the Batch service does not retry the task.</span></span> <span data-ttu-id="6b7c7-123">最大再試行回数場合は-1、バッチ サービスの再試行制限がないタスクです。</span><span class="sxs-lookup"><span data-stu-id="6b7c7-123">If the maximum retry count is -1, the Batch service retries the task without limit.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceFiles">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; ResourceFiles { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; ResourceFiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.StartTask.ResourceFiles" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceFiles As IList(Of ResourceFile)" />
      <MemberSignature Language="F#" Value="member this.ResourceFiles : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.StartTask.ResourceFiles" />
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
            <span data-ttu-id="6b7c7-124">取得またはコマンドラインを実行する前に、バッチ サービスをコンピューティング ノードにダウンロードするファイルの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="6b7c7-124">Gets or sets a list of files that the Batch service will download to the compute node before running the command line.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="6b7c7-125">この要素の下にリストされたファイルは、タスクの作業ディレクトリにあります。</span><span class="sxs-lookup"><span data-stu-id="6b7c7-125">Files listed under this element are located in the task's working directory.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UserIdentity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.UserIdentity UserIdentity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.UserIdentity UserIdentity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.StartTask.UserIdentity" />
      <MemberSignature Language="VB.NET" Value="Public Property UserIdentity As UserIdentity" />
      <MemberSignature Language="F#" Value="member this.UserIdentity : Microsoft.Azure.Batch.Protocol.Models.UserIdentity with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.StartTask.UserIdentity" />
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
            <span data-ttu-id="6b7c7-126">取得または開始タスクを実行するユーザー id を設定します。</span><span class="sxs-lookup"><span data-stu-id="6b7c7-126">Gets or sets the user identity under which the start task runs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="6b7c7-127">省略した場合、そのタスクは、タスクに一意の非管理者のユーザーとして実行されます。</span><span class="sxs-lookup"><span data-stu-id="6b7c7-127">If omitted, the task runs as a non-administrative user unique to the task.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.StartTask.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="startTask.Validate " />
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
            <span data-ttu-id="6b7c7-128">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="6b7c7-128">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6b7c7-129">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b7c7-129">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="WaitForSuccess">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; WaitForSuccess { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; WaitForSuccess" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.StartTask.WaitForSuccess" />
      <MemberSignature Language="VB.NET" Value="Public Property WaitForSuccess As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.WaitForSuccess : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.StartTask.WaitForSuccess" />
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
            <span data-ttu-id="6b7c7-130">取得または設定、バッチ サービスは、開始タスクが正常に完了を待つ必要があるかどうか (つまり、終了コード 0 で終了する)、コンピューティング ノード上のすべてのタスクをスケジュールする前にします。</span><span class="sxs-lookup"><span data-stu-id="6b7c7-130">Gets or sets whether the Batch service should wait for the start task to complete successfully (that is, to exit with exit code 0) before scheduling any tasks on the compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="6b7c7-131">True で、開始タスクは、コンピューティング ノードで失敗した場合、バッチ サービスは、その最大再試行回数 (maxTaskRetryCount) まで開始タスクを再試行します。</span><span class="sxs-lookup"><span data-stu-id="6b7c7-131">If true and the start task fails on a compute node, the Batch service retries the start task up to its maximum retry count (maxTaskRetryCount).</span></span> <span data-ttu-id="6b7c7-132">タスクしている場合もない正常に完了し、すべての再試行、バッチ サービス マークした後、コンピューティング ノードを使用できない場合にタスクのスケジュールがありません。</span><span class="sxs-lookup"><span data-stu-id="6b7c7-132">If the task has still not completed successfully after all retries, then the Batch service marks the compute node unusable, and will not schedule tasks to it.</span></span> <span data-ttu-id="6b7c7-133">この条件は、ノードの状態とエラー情報の詳細を使用して検出できます。</span><span class="sxs-lookup"><span data-stu-id="6b7c7-133">This condition can be detected via the node state and failure info details.</span></span> <span data-ttu-id="6b7c7-134">False の場合、バッチ サービスは、開始タスクの完了を待機しません。</span><span class="sxs-lookup"><span data-stu-id="6b7c7-134">If false, the Batch service will not wait for the start task to complete.</span></span> <span data-ttu-id="6b7c7-135">この例では、その他のタスクが、開始タスクがまだ実行されているコンピューティング ノードで実行されているを開始することができます。され、開始タスクが失敗した場合でも新しいタスクがノードにあるスケジュール続行されます。</span><span class="sxs-lookup"><span data-stu-id="6b7c7-135">In this case, other tasks can start executing on the compute node while the start task is still running; and even if the start task fails, new tasks will continue to be scheduled on the node.</span></span> <span data-ttu-id="6b7c7-136">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="6b7c7-136">The default is false.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>