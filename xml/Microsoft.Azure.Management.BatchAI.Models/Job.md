<Type Name="Job" FullName="Microsoft.Azure.Management.BatchAI.Models.Job">
  <TypeSignature Language="C#" Value="public class Job : Microsoft.Azure.Management.BatchAI.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Job extends Microsoft.Azure.Management.BatchAI.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.Job" />
  <TypeSignature Language="VB.NET" Value="Public Class Job&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type Job = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.BatchAI.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="10a5c-101">ジョブに関する情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="10a5c-101">Contains information about the job.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Job ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.Job.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="10a5c-102">Job クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="10a5c-102">Initializes a new instance of the Job class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Job (string id = null, string name = null, string type = null, string location = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string experimentName = null, Nullable&lt;int&gt; priority = null, Microsoft.Azure.Management.BatchAI.Models.ResourceId cluster = null, Nullable&lt;int&gt; nodeCount = null, Microsoft.Azure.Management.BatchAI.Models.ContainerSettings containerSettings = null, string toolType = null, Microsoft.Azure.Management.BatchAI.Models.CNTKsettings cntkSettings = null, Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings tensorFlowSettings = null, Microsoft.Azure.Management.BatchAI.Models.CaffeSettings caffeSettings = null, Microsoft.Azure.Management.BatchAI.Models.ChainerSettings chainerSettings = null, Microsoft.Azure.Management.BatchAI.Models.CustomToolkitSettings customToolkitSettings = null, Microsoft.Azure.Management.BatchAI.Models.JobPreparation jobPreparation = null, string stdOutErrPathPrefix = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.InputDirectory&gt; inputDirectories = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.OutputDirectory&gt; outputDirectories = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.EnvironmentSetting&gt; environmentVariables = null, Microsoft.Azure.Management.BatchAI.Models.JobPropertiesConstraints constraints = null, Nullable&lt;DateTime&gt; creationTime = null, Microsoft.Azure.Management.BatchAI.Models.ProvisioningState provisioningState = Microsoft.Azure.Management.BatchAI.Models.ProvisioningState.Creating, Nullable&lt;DateTime&gt; provisioningStateTransitionTime = null, Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.ExecutionState&gt; executionState = null, Nullable&lt;DateTime&gt; executionStateTransitionTime = null, Microsoft.Azure.Management.BatchAI.Models.JobPropertiesExecutionInfo executionInfo = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string experimentName, valuetype System.Nullable`1&lt;int32&gt; priority, class Microsoft.Azure.Management.BatchAI.Models.ResourceId cluster, valuetype System.Nullable`1&lt;int32&gt; nodeCount, class Microsoft.Azure.Management.BatchAI.Models.ContainerSettings containerSettings, string toolType, class Microsoft.Azure.Management.BatchAI.Models.CNTKsettings cntkSettings, class Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings tensorFlowSettings, class Microsoft.Azure.Management.BatchAI.Models.CaffeSettings caffeSettings, class Microsoft.Azure.Management.BatchAI.Models.ChainerSettings chainerSettings, class Microsoft.Azure.Management.BatchAI.Models.CustomToolkitSettings customToolkitSettings, class Microsoft.Azure.Management.BatchAI.Models.JobPreparation jobPreparation, string stdOutErrPathPrefix, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.BatchAI.Models.InputDirectory&gt; inputDirectories, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.BatchAI.Models.OutputDirectory&gt; outputDirectories, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.BatchAI.Models.EnvironmentSetting&gt; environmentVariables, class Microsoft.Azure.Management.BatchAI.Models.JobPropertiesConstraints constraints, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; creationTime, valuetype Microsoft.Azure.Management.BatchAI.Models.ProvisioningState provisioningState, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; provisioningStateTransitionTime, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.BatchAI.Models.ExecutionState&gt; executionState, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; executionStateTransitionTime, class Microsoft.Azure.Management.BatchAI.Models.JobPropertiesExecutionInfo executionInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.Job.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.Nullable{System.Int32},Microsoft.Azure.Management.BatchAI.Models.ResourceId,System.Nullable{System.Int32},Microsoft.Azure.Management.BatchAI.Models.ContainerSettings,System.String,Microsoft.Azure.Management.BatchAI.Models.CNTKsettings,Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings,Microsoft.Azure.Management.BatchAI.Models.CaffeSettings,Microsoft.Azure.Management.BatchAI.Models.ChainerSettings,Microsoft.Azure.Management.BatchAI.Models.CustomToolkitSettings,Microsoft.Azure.Management.BatchAI.Models.JobPreparation,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.BatchAI.Models.InputDirectory},System.Collections.Generic.IList{Microsoft.Azure.Management.BatchAI.Models.OutputDirectory},System.Collections.Generic.IList{Microsoft.Azure.Management.BatchAI.Models.EnvironmentSetting},Microsoft.Azure.Management.BatchAI.Models.JobPropertiesConstraints,System.Nullable{System.DateTime},Microsoft.Azure.Management.BatchAI.Models.ProvisioningState,System.Nullable{System.DateTime},System.Nullable{Microsoft.Azure.Management.BatchAI.Models.ExecutionState},System.Nullable{System.DateTime},Microsoft.Azure.Management.BatchAI.Models.JobPropertiesExecutionInfo)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.Job : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Nullable&lt;int&gt; * Microsoft.Azure.Management.BatchAI.Models.ResourceId * Nullable&lt;int&gt; * Microsoft.Azure.Management.BatchAI.Models.ContainerSettings * string * Microsoft.Azure.Management.BatchAI.Models.CNTKsettings * Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings * Microsoft.Azure.Management.BatchAI.Models.CaffeSettings * Microsoft.Azure.Management.BatchAI.Models.ChainerSettings * Microsoft.Azure.Management.BatchAI.Models.CustomToolkitSettings * Microsoft.Azure.Management.BatchAI.Models.JobPreparation * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.InputDirectory&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.OutputDirectory&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.EnvironmentSetting&gt; * Microsoft.Azure.Management.BatchAI.Models.JobPropertiesConstraints * Nullable&lt;DateTime&gt; * Microsoft.Azure.Management.BatchAI.Models.ProvisioningState * Nullable&lt;DateTime&gt; * Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.ExecutionState&gt; * Nullable&lt;DateTime&gt; * Microsoft.Azure.Management.BatchAI.Models.JobPropertiesExecutionInfo -&gt; Microsoft.Azure.Management.BatchAI.Models.Job" Usage="new Microsoft.Azure.Management.BatchAI.Models.Job (id, name, type, location, tags, experimentName, priority, cluster, nodeCount, containerSettings, toolType, cntkSettings, tensorFlowSettings, caffeSettings, chainerSettings, customToolkitSettings, jobPreparation, stdOutErrPathPrefix, inputDirectories, outputDirectories, environmentVariables, constraints, creationTime, provisioningState, provisioningStateTransitionTime, executionState, executionStateTransitionTime, executionInfo)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="experimentName" Type="System.String" />
        <Parameter Name="priority" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cluster" Type="Microsoft.Azure.Management.BatchAI.Models.ResourceId" />
        <Parameter Name="nodeCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="containerSettings" Type="Microsoft.Azure.Management.BatchAI.Models.ContainerSettings" />
        <Parameter Name="toolType" Type="System.String" />
        <Parameter Name="cntkSettings" Type="Microsoft.Azure.Management.BatchAI.Models.CNTKsettings" />
        <Parameter Name="tensorFlowSettings" Type="Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings" />
        <Parameter Name="caffeSettings" Type="Microsoft.Azure.Management.BatchAI.Models.CaffeSettings" />
        <Parameter Name="chainerSettings" Type="Microsoft.Azure.Management.BatchAI.Models.ChainerSettings" />
        <Parameter Name="customToolkitSettings" Type="Microsoft.Azure.Management.BatchAI.Models.CustomToolkitSettings" />
        <Parameter Name="jobPreparation" Type="Microsoft.Azure.Management.BatchAI.Models.JobPreparation" />
        <Parameter Name="stdOutErrPathPrefix" Type="System.String" />
        <Parameter Name="inputDirectories" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.InputDirectory&gt;" />
        <Parameter Name="outputDirectories" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.OutputDirectory&gt;" />
        <Parameter Name="environmentVariables" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.EnvironmentSetting&gt;" />
        <Parameter Name="constraints" Type="Microsoft.Azure.Management.BatchAI.Models.JobPropertiesConstraints" />
        <Parameter Name="creationTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="provisioningState" Type="Microsoft.Azure.Management.BatchAI.Models.ProvisioningState" />
        <Parameter Name="provisioningStateTransitionTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="executionState" Type="System.Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.ExecutionState&gt;" />
        <Parameter Name="executionStateTransitionTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="executionInfo" Type="Microsoft.Azure.Management.BatchAI.Models.JobPropertiesExecutionInfo" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="10a5c-103">リソースの ID</span><span class="sxs-lookup"><span data-stu-id="10a5c-103">The ID of the resource</span></span></param>
        <param name="name"><span data-ttu-id="10a5c-104">リソースの名前</span><span class="sxs-lookup"><span data-stu-id="10a5c-104">The name of the resource</span></span></param>
        <param name="type"><span data-ttu-id="10a5c-105">リソースの種類</span><span class="sxs-lookup"><span data-stu-id="10a5c-105">The type of the resource</span></span></param>
        <param name="location"><span data-ttu-id="10a5c-106">リソースの場所</span><span class="sxs-lookup"><span data-stu-id="10a5c-106">The location of the resource</span></span></param>
        <param name="tags"><span data-ttu-id="10a5c-107">リソースのタグ</span><span class="sxs-lookup"><span data-stu-id="10a5c-107">The tags of the resource</span></span></param>
        <param name="experimentName"><span data-ttu-id="10a5c-108">ジョブの情報を実験記述します。</span><span class="sxs-lookup"><span data-stu-id="10a5c-108">Describe the experiment information of the job</span></span></param>
        <param name="priority"><span data-ttu-id="10a5c-109">ジョブに関連付けられている優先度です。</span><span class="sxs-lookup"><span data-stu-id="10a5c-109">Priority associated with the job.</span></span></param>
        <param name="cluster"><span data-ttu-id="10a5c-110">このジョブを実行するクラスターの Id を指定します。</span><span class="sxs-lookup"><span data-stu-id="10a5c-110">Specifies the Id of the cluster on which this job will run.</span></span></param>
        <param name="nodeCount"><span data-ttu-id="10a5c-111">ジョブの実行にコンピューティング ノードの数。</span><span class="sxs-lookup"><span data-stu-id="10a5c-111">Number of compute nodes to run the job on.</span></span></param>
        <param name="containerSettings"><span data-ttu-id="10a5c-112">提供場合、指定されたコンテナー内のジョブが実行されます。</span><span class="sxs-lookup"><span data-stu-id="10a5c-112">If provided the job will run in the specified container.</span></span></param>
        <param name="toolType"><span data-ttu-id="10a5c-113">このジョブのツールキット型。</span><span class="sxs-lookup"><span data-stu-id="10a5c-113">The toolkit type of this job.</span></span></param>
        <param name="cntkSettings"><span data-ttu-id="10a5c-114">CNTK (Microsoft 認知 Toolkit aka) ジョブの設定を指定します。</span><span class="sxs-lookup"><span data-stu-id="10a5c-114">Specifies the settings for CNTK (aka Microsoft Cognitive Toolkit) job.</span></span></param>
        <param name="tensorFlowSettings"><span data-ttu-id="10a5c-115">ジョブのテンソル フローの設定を指定します。</span><span class="sxs-lookup"><span data-stu-id="10a5c-115">Specifies the settings for Tensor Flow job.</span></span></param>
        <param name="caffeSettings"><span data-ttu-id="10a5c-116">Caffe ジョブの設定を指定します。</span><span class="sxs-lookup"><span data-stu-id="10a5c-116">Specifies the settings for Caffe job.</span></span></param>
        <param name="chainerSettings"><span data-ttu-id="10a5c-117">チェイナーのジョブの設定を指定します。</span><span class="sxs-lookup"><span data-stu-id="10a5c-117">Specifies the settings for Chainer job.</span></span></param>
        <param name="customToolkitSettings"><span data-ttu-id="10a5c-118">カスタム ツール キットのジョブの設定を指定します。</span><span class="sxs-lookup"><span data-stu-id="10a5c-118">Specifies the settings for custom tool kit job.</span></span></param>
        <param name="jobPreparation"><span data-ttu-id="10a5c-119">ツール キットを起動する前に実行するアクションを指定します。</span><span class="sxs-lookup"><span data-stu-id="10a5c-119">Specifies the actions to be performed before tool kit is launched.</span></span></param>
        <param name="stdOutErrPathPrefix"><span data-ttu-id="10a5c-120">Stdout とジョブの stderror のバッチ AI サービスのアップロード場所のパスです。</span><span class="sxs-lookup"><span data-stu-id="10a5c-120">The path where the Batch AI service will upload stdout and stderror of the job.</span></span></param>
        <param name="inputDirectories"><span data-ttu-id="10a5c-121">ジョブの入力ディレクトリの一覧を指定します。</span><span class="sxs-lookup"><span data-stu-id="10a5c-121">Specifies the list of input directories for the Job.</span></span></param>
        <param name="outputDirectories"><span data-ttu-id="10a5c-122">モデルを作成する出力ディレクトリの一覧を指定します。</span><span class="sxs-lookup"><span data-stu-id="10a5c-122">Specifies the list of output directories where the models will be created.</span></span> <span data-ttu-id="10a5c-123">が必要です。</span><span class="sxs-lookup"><span data-stu-id="10a5c-123">.</span></span></param>
        <param name="environmentVariables"><span data-ttu-id="10a5c-124">ジョブに渡される追加の環境変数。</span><span class="sxs-lookup"><span data-stu-id="10a5c-124">Additional environment variables to be passed to the job.</span></span></param>
        <param name="constraints"><span data-ttu-id="10a5c-125">ジョブに関連付けられている制約。</span><span class="sxs-lookup"><span data-stu-id="10a5c-125">Constraints associated with the Job.</span></span></param>
        <param name="creationTime"><span data-ttu-id="10a5c-126">ジョブの作成時刻。</span><span class="sxs-lookup"><span data-stu-id="10a5c-126">The job creation time.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="10a5c-127">バッチ AI ジョブの準備済みの状態。</span><span class="sxs-lookup"><span data-stu-id="10a5c-127">The provisioned state of the Batch AI job.</span></span> <span data-ttu-id="10a5c-128">使用可能な値が含まれます: '作成中'、'成功'、''、' を削除できませんでした'</span><span class="sxs-lookup"><span data-stu-id="10a5c-128">Possible values include: 'creating', 'succeeded', 'failed', 'deleting'</span></span></param>
        <param name="provisioningStateTransitionTime"><span data-ttu-id="10a5c-129">ジョブが現在のプロビジョニング状態を入力する時刻。</span><span class="sxs-lookup"><span data-stu-id="10a5c-129">The time at which the job entered its current provisioning state.</span></span></param>
        <param name="executionState"><span data-ttu-id="10a5c-130">ジョブの現在の状態。</span><span class="sxs-lookup"><span data-stu-id="10a5c-130">The current state of the job.</span></span></param>
        <param name="executionStateTransitionTime"><span data-ttu-id="10a5c-131">ジョブが現在の実行状態を入力する時刻。</span><span class="sxs-lookup"><span data-stu-id="10a5c-131">The time at which the job entered its current execution state.</span></span></param>
        <param name="executionInfo"><span data-ttu-id="10a5c-132">Azure Batch のサービスでジョブの実行に関する情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="10a5c-132">Contains information about the execution of a job in the Azure Batch service.</span></span></param>
        <summary>
            <span data-ttu-id="10a5c-133">Job クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="10a5c-133">Initializes a new instance of the Job class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CaffeSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.CaffeSettings CaffeSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.CaffeSettings CaffeSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Job.CaffeSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property CaffeSettings As CaffeSettings" />
      <MemberSignature Language="F#" Value="member this.CaffeSettings : Microsoft.Azure.Management.BatchAI.Models.CaffeSettings with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Job.CaffeSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.caffeSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.CaffeSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="10a5c-134">取得または設定 Caffe ジョブの設定を指定します。</span><span class="sxs-lookup"><span data-stu-id="10a5c-134">Gets or sets specifies the settings for Caffe job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ChainerSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.ChainerSettings ChainerSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.ChainerSettings ChainerSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Job.ChainerSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property ChainerSettings As ChainerSettings" />
      <MemberSignature Language="F#" Value="member this.ChainerSettings : Microsoft.Azure.Management.BatchAI.Models.ChainerSettings with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Job.ChainerSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.chainerSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.ChainerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="10a5c-135">取得または設定は、チェーン元のジョブの設定を指定します。</span><span class="sxs-lookup"><span data-stu-id="10a5c-135">Gets or sets specifies the settings for Chainer job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Cluster">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.ResourceId Cluster { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.ResourceId Cluster" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Job.Cluster" />
      <MemberSignature Language="VB.NET" Value="Public Property Cluster As ResourceId" />
      <MemberSignature Language="F#" Value="member this.Cluster : Microsoft.Azure.Management.BatchAI.Models.ResourceId with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Job.Cluster" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.cluster")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.ResourceId</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="10a5c-136">取得または設定は、このジョブを実行するクラスターの Id を指定します。</span><span class="sxs-lookup"><span data-stu-id="10a5c-136">Gets or sets specifies the Id of the cluster on which this job will run.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CntkSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.CNTKsettings CntkSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.CNTKsettings CntkSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Job.CntkSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property CntkSettings As CNTKsettings" />
      <MemberSignature Language="F#" Value="member this.CntkSettings : Microsoft.Azure.Management.BatchAI.Models.CNTKsettings with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Job.CntkSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.cntkSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.CNTKsettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="10a5c-137">取得または設定 CNTK (Microsoft 認知 Toolkit aka) ジョブの設定を指定します。</span><span class="sxs-lookup"><span data-stu-id="10a5c-137">Gets or sets specifies the settings for CNTK (aka Microsoft Cognitive Toolkit) job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Constraints">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.JobPropertiesConstraints Constraints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.JobPropertiesConstraints Constraints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Job.Constraints" />
      <MemberSignature Language="VB.NET" Value="Public Property Constraints As JobPropertiesConstraints" />
      <MemberSignature Language="F#" Value="member this.Constraints : Microsoft.Azure.Management.BatchAI.Models.JobPropertiesConstraints with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Job.Constraints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.constraints")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.JobPropertiesConstraints</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="10a5c-138">取得またはジョブに関連付けられている制約を設定します。</span><span class="sxs-lookup"><span data-stu-id="10a5c-138">Gets or sets constraints associated with the Job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.ContainerSettings ContainerSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.ContainerSettings ContainerSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Job.ContainerSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerSettings As ContainerSettings" />
      <MemberSignature Language="F#" Value="member this.ContainerSettings : Microsoft.Azure.Management.BatchAI.Models.ContainerSettings with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Job.ContainerSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.containerSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.ContainerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="10a5c-139">取得または設定場合は、ジョブの指定されたコンテナーの実行時間を指定します。</span><span class="sxs-lookup"><span data-stu-id="10a5c-139">Gets or sets if provided the job will run in the specified container.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="10a5c-140">コンテナーがクラスターのセットアップの一部としてダウンロードした場合は、そのコンテナーのイメージが使用されます。</span><span class="sxs-lookup"><span data-stu-id="10a5c-140">If the container was downloaded as part of cluster setup then the same container image will be used.</span></span> <span data-ttu-id="10a5c-141">指定されていない場合、ジョブは、VM で実行されます。</span><span class="sxs-lookup"><span data-stu-id="10a5c-141">If not provided, the job will run on the VM.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreationTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Job.CreationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreationTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.BatchAI.Models.Job.CreationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.creationTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="10a5c-142">ジョブの作成時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="10a5c-142">Gets the job creation time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="10a5c-143">ジョブの作成時間。</span><span class="sxs-lookup"><span data-stu-id="10a5c-143">The creation time of the job.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomToolkitSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.CustomToolkitSettings CustomToolkitSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.CustomToolkitSettings CustomToolkitSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Job.CustomToolkitSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomToolkitSettings As CustomToolkitSettings" />
      <MemberSignature Language="F#" Value="member this.CustomToolkitSettings : Microsoft.Azure.Management.BatchAI.Models.CustomToolkitSettings with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Job.CustomToolkitSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.customToolkitSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.CustomToolkitSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="10a5c-144">取得または設定は、カスタム ツール キットのジョブの設定を指定します。</span><span class="sxs-lookup"><span data-stu-id="10a5c-144">Gets or sets specifies the settings for custom tool kit job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnvironmentVariables">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.EnvironmentSetting&gt; EnvironmentVariables { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.BatchAI.Models.EnvironmentSetting&gt; EnvironmentVariables" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Job.EnvironmentVariables" />
      <MemberSignature Language="VB.NET" Value="Public Property EnvironmentVariables As IList(Of EnvironmentSetting)" />
      <MemberSignature Language="F#" Value="member this.EnvironmentVariables : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.EnvironmentSetting&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Job.EnvironmentVariables" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.environmentVariables")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.EnvironmentSetting&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="10a5c-145">取得またはジョブに渡される追加の環境変数を設定します。</span><span class="sxs-lookup"><span data-stu-id="10a5c-145">Gets or sets additional environment variables to be passed to the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="10a5c-146">バッチ AI サービスは、すべてのジョブは、次の環境変数を設定します AZ_BATCHAI_INPUT_id、AZ_BATCHAI_OUTPUT_id、AZ_BATCHAI_NUM_GPUS_PER_NODE、分散の TensorFlow ジョブでは、次の追加の環境変数は、バッチ AI サービスによって設定されます。: AZ_BATCHAI_PS_HOSTS、AZ_BATCHAI_WORKER_HOSTS です。</span><span class="sxs-lookup"><span data-stu-id="10a5c-146">Batch AI services sets the following environment variables for all jobs: AZ_BATCHAI_INPUT_id, AZ_BATCHAI_OUTPUT_id, AZ_BATCHAI_NUM_GPUS_PER_NODE, For distributed TensorFlow jobs, following additional environment variables are set by the Batch AI Service: AZ_BATCHAI_PS_HOSTS, AZ_BATCHAI_WORKER_HOSTS.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecutionInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.JobPropertiesExecutionInfo ExecutionInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.JobPropertiesExecutionInfo ExecutionInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Job.ExecutionInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property ExecutionInfo As JobPropertiesExecutionInfo" />
      <MemberSignature Language="F#" Value="member this.ExecutionInfo : Microsoft.Azure.Management.BatchAI.Models.JobPropertiesExecutionInfo with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Job.ExecutionInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.executionInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.JobPropertiesExecutionInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="10a5c-147">取得または設定には、Azure Batch のサービスでジョブの実行に関する情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="10a5c-147">Gets or sets contains information about the execution of a job in the Azure Batch service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecutionState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.ExecutionState&gt; ExecutionState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.BatchAI.Models.ExecutionState&gt; ExecutionState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Job.ExecutionState" />
      <MemberSignature Language="VB.NET" Value="Public Property ExecutionState As Nullable(Of ExecutionState)" />
      <MemberSignature Language="F#" Value="member this.ExecutionState : Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.ExecutionState&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Job.ExecutionState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.executionState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.ExecutionState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="10a5c-148">取得またはジョブの現在の状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="10a5c-148">Gets or sets the current state of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="10a5c-149">ジョブの現在の状態。</span><span class="sxs-lookup"><span data-stu-id="10a5c-149">The current state of the job.</span></span> <span data-ttu-id="10a5c-150">指定できる値は: キュー - ジョブがキューに置かれたとを実行できません。</span><span class="sxs-lookup"><span data-stu-id="10a5c-150">Possible values are: queued - The job is queued and able to run.</span></span> <span data-ttu-id="10a5c-151">ジョブ状態は、その作成時に、または、失敗した実行後に再試行を待機しているときに使用します。</span><span class="sxs-lookup"><span data-stu-id="10a5c-151">A job enters this state when it is created, or when it is awaiting a retry after a failed run.</span></span> <span data-ttu-id="10a5c-152">実行</span><span class="sxs-lookup"><span data-stu-id="10a5c-152">running</span></span>
            - <span data-ttu-id="10a5c-153">ジョブは、計算クラスターで行われています。</span><span class="sxs-lookup"><span data-stu-id="10a5c-153">The job is running on a compute cluster.</span></span> <span data-ttu-id="10a5c-154">これには、ジョブ レベル準備リソース ファイルのダウンロードなどが含まれます。 または ジョブ - 指定されたコンテナーをセットアップ、必ずしもジョブ コマンドラインの実行が開始されたことです。</span><span class="sxs-lookup"><span data-stu-id="10a5c-154">This includes job-level preparation such as downloading resource files or set up container specified on the job - it does not necessarily mean that the job command line has started executing.</span></span> <span data-ttu-id="10a5c-155">終了して、ユーザーが、ジョブが終了した、終了操作が進行中です。</span><span class="sxs-lookup"><span data-stu-id="10a5c-155">terminating - The job is terminated by the user, the terminate operation is in progress.</span></span>
            <span data-ttu-id="10a5c-156">成功 - ジョブが実行中に正常に完了、終了コード 0 で終了しました。</span><span class="sxs-lookup"><span data-stu-id="10a5c-156">succeeded - The job has completed running succesfully and exited with exit code 0.</span></span> <span data-ttu-id="10a5c-157">失敗しました - ジョブが正常完了 (0 以外の終了コードで失敗しました)、再試行の制限が不足しています。</span><span class="sxs-lookup"><span data-stu-id="10a5c-157">failed - The job has finished unsuccessfully (failed with a non-zero exit code) and has exhausted its retry limit.</span></span> <span data-ttu-id="10a5c-158">ジョブには、ジョブの起動エラーが発生した場合は失敗としてもマークされます。</span><span class="sxs-lookup"><span data-stu-id="10a5c-158">A job is also marked as failed if an error occurred launching the job.</span></span> <span data-ttu-id="10a5c-159">使用可能な値が含まれます: 'queued'、'実行中'、'を終了して'、'成功'、'失敗'</span><span class="sxs-lookup"><span data-stu-id="10a5c-159">Possible values include: 'queued', 'running', 'terminating', 'succeeded', 'failed'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecutionStateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ExecutionStateTransitionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ExecutionStateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Job.ExecutionStateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExecutionStateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ExecutionStateTransitionTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.BatchAI.Models.Job.ExecutionStateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.executionStateTransitionTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="10a5c-160">ジョブが現在の実行状態を入力するされた時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="10a5c-160">Gets the time at which the job entered its current execution state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="10a5c-161">ジョブが現在の実行状態を入力する時刻。</span><span class="sxs-lookup"><span data-stu-id="10a5c-161">The time at which the job entered its current execution state.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ExperimentName">
      <MemberSignature Language="C#" Value="public string ExperimentName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ExperimentName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Job.ExperimentName" />
      <MemberSignature Language="VB.NET" Value="Public Property ExperimentName As String" />
      <MemberSignature Language="F#" Value="member this.ExperimentName : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Job.ExperimentName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.experimentName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="10a5c-162">取得または設定、ジョブの実験情報を記述します。</span><span class="sxs-lookup"><span data-stu-id="10a5c-162">Gets or sets describe the experiment information of the job</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InputDirectories">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.InputDirectory&gt; InputDirectories { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.BatchAI.Models.InputDirectory&gt; InputDirectories" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Job.InputDirectories" />
      <MemberSignature Language="VB.NET" Value="Public Property InputDirectories As IList(Of InputDirectory)" />
      <MemberSignature Language="F#" Value="member this.InputDirectories : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.InputDirectory&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Job.InputDirectories" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.inputDirectories")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.InputDirectory&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="10a5c-163">取得または設定は、ジョブの入力ディレクトリの一覧を指定します。</span><span class="sxs-lookup"><span data-stu-id="10a5c-163">Gets or sets specifies the list of input directories for the Job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobPreparation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.JobPreparation JobPreparation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.JobPreparation JobPreparation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Job.JobPreparation" />
      <MemberSignature Language="VB.NET" Value="Public Property JobPreparation As JobPreparation" />
      <MemberSignature Language="F#" Value="member this.JobPreparation : Microsoft.Azure.Management.BatchAI.Models.JobPreparation with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Job.JobPreparation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.jobPreparation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.JobPreparation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="10a5c-164">取得または設定は、ツール キットを起動する前に実行するアクションを指定します。</span><span class="sxs-lookup"><span data-stu-id="10a5c-164">Gets or sets specifies the actions to be performed before tool kit is launched.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="10a5c-165">指定したアクションは、ジョブの一部であるすべてのノードで実行されます。</span><span class="sxs-lookup"><span data-stu-id="10a5c-165">The specified actions will run on all the nodes that are part of the job</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; NodeCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; NodeCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Job.NodeCount" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.NodeCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Job.NodeCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.nodeCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="10a5c-166">取得または、ジョブを実行するコンピューティング ノードの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="10a5c-166">Gets or sets number of compute nodes to run the job on.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="10a5c-167">ジョブなりますスケジュール多軸には、多くのコンピューティング ノード</span><span class="sxs-lookup"><span data-stu-id="10a5c-167">The job will be gang scheduled on that many compute nodes</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OutputDirectories">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.OutputDirectory&gt; OutputDirectories { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.BatchAI.Models.OutputDirectory&gt; OutputDirectories" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Job.OutputDirectories" />
      <MemberSignature Language="VB.NET" Value="Public Property OutputDirectories As IList(Of OutputDirectory)" />
      <MemberSignature Language="F#" Value="member this.OutputDirectories : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.OutputDirectory&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Job.OutputDirectories" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.outputDirectories")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.OutputDirectory&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="10a5c-168">取得または設定は、モデルを作成する出力ディレクトリの一覧を指定します。</span><span class="sxs-lookup"><span data-stu-id="10a5c-168">Gets or sets specifies the list of output directories where the models will be created.</span></span> <span data-ttu-id="10a5c-169">が必要です。</span><span class="sxs-lookup"><span data-stu-id="10a5c-169">.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Priority">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Priority { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Priority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Job.Priority" />
      <MemberSignature Language="VB.NET" Value="Public Property Priority As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Priority : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Job.Priority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.priority")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="10a5c-170">取得またはジョブに関連付けられている優先度を設定します。</span><span class="sxs-lookup"><span data-stu-id="10a5c-170">Gets or sets priority associated with the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="10a5c-171">ジョブに関連付けられている優先度です。</span><span class="sxs-lookup"><span data-stu-id="10a5c-171">Priority associated with the job.</span></span> <span data-ttu-id="10a5c-172">優先順位の値の範囲は -1000 から 1000、-1000 が最も低い優先度と 1000 中優先順位が高いです。</span><span class="sxs-lookup"><span data-stu-id="10a5c-172">Priority values can range from -1000 to 1000, with -1000 being the lowest priority and 1000 being the highest priority.</span></span> <span data-ttu-id="10a5c-173">既定値は 0 です。</span><span class="sxs-lookup"><span data-stu-id="10a5c-173">The default value is 0.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.ProvisioningState ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.BatchAI.Models.ProvisioningState ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Job.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As ProvisioningState" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Microsoft.Azure.Management.BatchAI.Models.ProvisioningState" Usage="Microsoft.Azure.Management.BatchAI.Models.Job.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.ProvisioningState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="10a5c-174">バッチ AI ジョブの準備済みの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="10a5c-174">Gets the provisioned state of the Batch AI job.</span></span> <span data-ttu-id="10a5c-175">使用可能な値が含まれます: '作成中'、'成功'、''、' を削除できませんでした'</span><span class="sxs-lookup"><span data-stu-id="10a5c-175">Possible values include: 'creating', 'succeeded', 'failed', 'deleting'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningStateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ProvisioningStateTransitionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ProvisioningStateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Job.ProvisioningStateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningStateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ProvisioningStateTransitionTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.BatchAI.Models.Job.ProvisioningStateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningStateTransitionTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="10a5c-176">ジョブが現在のプロビジョニング状態を入力するされた時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="10a5c-176">Gets the time at which the job entered its current provisioning state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="10a5c-177">ジョブが現在のプロビジョニング状態を入力する時刻。</span><span class="sxs-lookup"><span data-stu-id="10a5c-177">The time at which the job entered its current provisioning state.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StdOutErrPathPrefix">
      <MemberSignature Language="C#" Value="public string StdOutErrPathPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StdOutErrPathPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Job.StdOutErrPathPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property StdOutErrPathPrefix As String" />
      <MemberSignature Language="F#" Value="member this.StdOutErrPathPrefix : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Job.StdOutErrPathPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.stdOutErrPathPrefix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="10a5c-178">取得または stdout とジョブの stderror のバッチ AI サービスのアップロード場所のパスを設定します。</span><span class="sxs-lookup"><span data-stu-id="10a5c-178">Gets or sets the path where the Batch AI service will upload stdout and stderror of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TensorFlowSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings TensorFlowSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings TensorFlowSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Job.TensorFlowSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property TensorFlowSettings As TensorFlowSettings" />
      <MemberSignature Language="F#" Value="member this.TensorFlowSettings : Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Job.TensorFlowSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.tensorFlowSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="10a5c-179">取得または設定は、ジョブのテンソル フローの設定を指定します。</span><span class="sxs-lookup"><span data-stu-id="10a5c-179">Gets or sets specifies the settings for Tensor Flow job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToolType">
      <MemberSignature Language="C#" Value="public string ToolType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ToolType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Job.ToolType" />
      <MemberSignature Language="VB.NET" Value="Public Property ToolType As String" />
      <MemberSignature Language="F#" Value="member this.ToolType : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Job.ToolType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.toolType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="10a5c-180">取得または、このジョブのツールキットの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="10a5c-180">Gets or sets the toolkit type of this job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="10a5c-181">指定できる値は: cntk、tensorflow、caffe、caffe2、チェーン元、カスタムです。</span><span class="sxs-lookup"><span data-stu-id="10a5c-181">Possible values are: cntk, tensorflow, caffe, caffe2, chainer, custom.</span></span> <span data-ttu-id="10a5c-182">使用可能な値が含まれます: 'cntk'、'tensorflow'、'caffe'、'caffe2'、'チェイナー'、'custom'</span><span class="sxs-lookup"><span data-stu-id="10a5c-182">Possible values include: 'cntk', 'tensorflow', 'caffe', 'caffe2', 'chainer', 'custom'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.Job.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="job.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="10a5c-183">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="10a5c-183">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="10a5c-184">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="10a5c-184">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>