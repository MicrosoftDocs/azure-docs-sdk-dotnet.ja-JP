<Type Name="PoolSpecification" FullName="Microsoft.Azure.Batch.Protocol.Models.PoolSpecification">
  <TypeSignature Language="C#" Value="public class PoolSpecification" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PoolSpecification extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.PoolSpecification" />
  <TypeSignature Language="VB.NET" Value="Public Class PoolSpecification" />
  <TypeSignature Language="F#" Value="type PoolSpecification = class" />
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
            <span data-ttu-id="3ca49-101">新しいプールを作成するを指定します。</span><span class="sxs-lookup"><span data-stu-id="3ca49-101">Specification for creating a new pool.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolSpecification ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.#ctor" />
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
            <span data-ttu-id="3ca49-102">PoolSpecification クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3ca49-102">Initializes a new instance of the PoolSpecification class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolSpecification (string vmSize, string displayName = null, Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration cloudServiceConfiguration = null, Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration virtualMachineConfiguration = null, Nullable&lt;int&gt; maxTasksPerNode = null, Microsoft.Azure.Batch.Protocol.Models.TaskSchedulingPolicy taskSchedulingPolicy = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, Nullable&lt;int&gt; targetDedicatedNodes = null, Nullable&lt;int&gt; targetLowPriorityNodes = null, Nullable&lt;bool&gt; enableAutoScale = null, string autoScaleFormula = null, Nullable&lt;TimeSpan&gt; autoScaleEvaluationInterval = null, Nullable&lt;bool&gt; enableInterNodeCommunication = null, Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration networkConfiguration = null, Microsoft.Azure.Batch.Protocol.Models.StartTask startTask = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; certificateReferences = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; applicationPackageReferences = null, System.Collections.Generic.IList&lt;string&gt; applicationLicenses = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.UserAccount&gt; userAccounts = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; metadata = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string vmSize, string displayName, class Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration cloudServiceConfiguration, class Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration virtualMachineConfiguration, valuetype System.Nullable`1&lt;int32&gt; maxTasksPerNode, class Microsoft.Azure.Batch.Protocol.Models.TaskSchedulingPolicy taskSchedulingPolicy, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, valuetype System.Nullable`1&lt;int32&gt; targetDedicatedNodes, valuetype System.Nullable`1&lt;int32&gt; targetLowPriorityNodes, valuetype System.Nullable`1&lt;bool&gt; enableAutoScale, string autoScaleFormula, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; autoScaleEvaluationInterval, valuetype System.Nullable`1&lt;bool&gt; enableInterNodeCommunication, class Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration networkConfiguration, class Microsoft.Azure.Batch.Protocol.Models.StartTask startTask, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; certificateReferences, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; applicationPackageReferences, class System.Collections.Generic.IList`1&lt;string&gt; applicationLicenses, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.UserAccount&gt; userAccounts, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; metadata) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.#ctor(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration,Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration,System.Nullable{System.Int32},Microsoft.Azure.Batch.Protocol.Models.TaskSchedulingPolicy,System.Nullable{System.TimeSpan},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Boolean},System.String,System.Nullable{System.TimeSpan},System.Nullable{System.Boolean},Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration,Microsoft.Azure.Batch.Protocol.Models.StartTask,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.CertificateReference},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference},System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.UserAccount},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.MetadataItem})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.PoolSpecification : string * string * Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration * Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration * Nullable&lt;int&gt; * Microsoft.Azure.Batch.Protocol.Models.TaskSchedulingPolicy * Nullable&lt;TimeSpan&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;bool&gt; * string * Nullable&lt;TimeSpan&gt; * Nullable&lt;bool&gt; * Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration * Microsoft.Azure.Batch.Protocol.Models.StartTask * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.UserAccount&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.PoolSpecification" Usage="new Microsoft.Azure.Batch.Protocol.Models.PoolSpecification (vmSize, displayName, cloudServiceConfiguration, virtualMachineConfiguration, maxTasksPerNode, taskSchedulingPolicy, resizeTimeout, targetDedicatedNodes, targetLowPriorityNodes, enableAutoScale, autoScaleFormula, autoScaleEvaluationInterval, enableInterNodeCommunication, networkConfiguration, startTask, certificateReferences, applicationPackageReferences, applicationLicenses, userAccounts, metadata)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="vmSize" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="cloudServiceConfiguration" Type="Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration" />
        <Parameter Name="virtualMachineConfiguration" Type="Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration" />
        <Parameter Name="maxTasksPerNode" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="taskSchedulingPolicy" Type="Microsoft.Azure.Batch.Protocol.Models.TaskSchedulingPolicy" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="targetDedicatedNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="targetLowPriorityNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="enableAutoScale" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="autoScaleFormula" Type="System.String" />
        <Parameter Name="autoScaleEvaluationInterval" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="enableInterNodeCommunication" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="networkConfiguration" Type="Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration" />
        <Parameter Name="startTask" Type="Microsoft.Azure.Batch.Protocol.Models.StartTask" />
        <Parameter Name="certificateReferences" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt;" />
        <Parameter Name="applicationPackageReferences" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt;" />
        <Parameter Name="applicationLicenses" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="userAccounts" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.UserAccount&gt;" />
        <Parameter Name="metadata" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt;" />
      </Parameters>
      <Docs>
        <param name="vmSize"><span data-ttu-id="3ca49-103">プール内の仮想マシンのサイズ。</span><span class="sxs-lookup"><span data-stu-id="3ca49-103">The size of the virtual machines in the pool.</span></span>
            <span data-ttu-id="3ca49-104">プール内の仮想マシンのサイズはすべて同じです。</span><span class="sxs-lookup"><span data-stu-id="3ca49-104">All virtual machines in a pool are the same size.</span></span></param>
        <param name="displayName"><span data-ttu-id="3ca49-105">プールの表示名。</span><span class="sxs-lookup"><span data-stu-id="3ca49-105">The display name for the pool.</span></span></param>
        <param name="cloudServiceConfiguration"><span data-ttu-id="3ca49-106">プールのクラウドサービス構成。</span><span class="sxs-lookup"><span data-stu-id="3ca49-106">The cloud service configuration for the pool.</span></span></param>
        <param name="virtualMachineConfiguration"><span data-ttu-id="3ca49-107">プールの仮想マシン構成。</span><span class="sxs-lookup"><span data-stu-id="3ca49-107">The virtual machine configuration for the pool.</span></span></param>
        <param name="maxTasksPerNode"><span data-ttu-id="3ca49-108">プール内の単一コンピューティング ノードで同時に実行できるタスクの最大数。</span><span class="sxs-lookup"><span data-stu-id="3ca49-108">The maximum number of tasks that can run concurrently on a single compute node in the pool.</span></span></param>
        <param name="taskSchedulingPolicy"><span data-ttu-id="3ca49-109">どのタスクはプール内のコンピューティング ノード間で分散されます。</span><span class="sxs-lookup"><span data-stu-id="3ca49-109">How tasks are distributed across compute nodes in a pool.</span></span></param>
        <param name="resizeTimeout"><span data-ttu-id="3ca49-110">プールにコンピューティング ノードの割り当てのタイムアウト。</span><span class="sxs-lookup"><span data-stu-id="3ca49-110">The timeout for allocation of compute nodes to the pool.</span></span></param>
        <param name="targetDedicatedNodes"><span data-ttu-id="3ca49-111">専用の目的の数は、プール内のノードを計算します。</span><span class="sxs-lookup"><span data-stu-id="3ca49-111">The desired number of dedicated compute nodes in the pool.</span></span></param>
        <param name="targetLowPriorityNodes"><span data-ttu-id="3ca49-112">目的の優先度の低い数は、プール内のノードを計算します。</span><span class="sxs-lookup"><span data-stu-id="3ca49-112">The desired number of low-priority compute nodes in the pool.</span></span></param>
        <param name="enableAutoScale"><span data-ttu-id="3ca49-113">かどうか、プールのサイズは、時間の経過と共に自動的に調整する必要があります。</span><span class="sxs-lookup"><span data-stu-id="3ca49-113">Whether the pool size should automatically adjust over time.</span></span></param>
        <param name="autoScaleFormula"><span data-ttu-id="3ca49-114">プール内の計算ノードの必要な数の式。</span><span class="sxs-lookup"><span data-stu-id="3ca49-114">The formula for the desired number of compute nodes in the pool.</span></span></param>
        <param name="autoScaleEvaluationInterval"><span data-ttu-id="3ca49-115">自動スケールの数式に従ってプールのサイズを自動的に調整する時間間隔。</span><span class="sxs-lookup"><span data-stu-id="3ca49-115">The time interval at which to automatically adjust the pool size according to the autoscale formula.</span></span></param>
        <param name="enableInterNodeCommunication"><span data-ttu-id="3ca49-116">かどうか、プールは、ノード間の直接通信を許可します。</span><span class="sxs-lookup"><span data-stu-id="3ca49-116">Whether the pool permits direct communication between nodes.</span></span></param>
        <param name="networkConfiguration"><span data-ttu-id="3ca49-117">プールのネットワーク構成。</span><span class="sxs-lookup"><span data-stu-id="3ca49-117">The network configuration for the pool.</span></span></param>
        <param name="startTask"><span data-ttu-id="3ca49-118">各コンピューティング ノード上で実行するタスクは、プールを結合します。</span><span class="sxs-lookup"><span data-stu-id="3ca49-118">A task to run on each compute node as it joins the pool.</span></span> <span data-ttu-id="3ca49-119">タスクは、プールに、または、ノードが再起動されたときに、ノードが追加されたときに実行されます。</span><span class="sxs-lookup"><span data-stu-id="3ca49-119">The task runs when the node is added to the pool or when the node is restarted.</span></span></param>
        <param name="certificateReferences"><span data-ttu-id="3ca49-120">プール内の各コンピューティング ノードにインストールされている証明書の一覧。</span><span class="sxs-lookup"><span data-stu-id="3ca49-120">A list of certificates to be installed on each compute node in the pool.</span></span></param>
        <param name="applicationPackageReferences"><span data-ttu-id="3ca49-121">プール内の各コンピューティング ノードにインストールされているアプリケーション パッケージの一覧。</span><span class="sxs-lookup"><span data-stu-id="3ca49-121">The list of application packages to be installed on each compute node in the pool.</span></span></param>
        <param name="applicationLicenses"><span data-ttu-id="3ca49-122">アプリケーションの一覧のライセンスは、バッチ サービスは、プール内の各コンピューティング ノードで使用できるようにします。</span><span class="sxs-lookup"><span data-stu-id="3ca49-122">The list of application licenses the Batch service will make available on each compute node in the pool.</span></span></param>
        <param name="userAccounts"><span data-ttu-id="3ca49-123">プール内の各ノード上に作成されるユーザー アカウントの一覧です。</span><span class="sxs-lookup"><span data-stu-id="3ca49-123">The list of user accounts to be created on each node in the pool.</span></span></param>
        <param name="metadata"><span data-ttu-id="3ca49-124">メタデータとしてプールに関連付けられている名前と値のペアの一覧。</span><span class="sxs-lookup"><span data-stu-id="3ca49-124">A list of name-value pairs associated with the pool as metadata.</span></span></param>
        <summary>
            <span data-ttu-id="3ca49-125">PoolSpecification クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3ca49-125">Initializes a new instance of the PoolSpecification class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationLicenses">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ApplicationLicenses { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ApplicationLicenses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.ApplicationLicenses" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationLicenses As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ApplicationLicenses : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.ApplicationLicenses" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="applicationLicenses")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3ca49-126">取得またはアプリケーションのライセンスの一覧をバッチ サービスは、プール内の各コンピューティング ノードで使用できるように設定します。</span><span class="sxs-lookup"><span data-stu-id="3ca49-126">Gets or sets the list of application licenses the Batch service will make available on each compute node in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="3ca49-127">アプリケーションのライセンスの一覧は、使用できる Batch サービス アプリケーションのライセンスのサブセットである必要があります。</span><span class="sxs-lookup"><span data-stu-id="3ca49-127">The list of application licenses must be a subset of available Batch service application licenses.</span></span> <span data-ttu-id="3ca49-128">これはサポートされていない要求されるライセンスと、プールの作成は失敗します。</span><span class="sxs-lookup"><span data-stu-id="3ca49-128">If a license is requested which is not supported, pool creation will fail.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationPackageReferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; ApplicationPackageReferences { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; ApplicationPackageReferences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.ApplicationPackageReferences" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationPackageReferences As IList(Of ApplicationPackageReference)" />
      <MemberSignature Language="F#" Value="member this.ApplicationPackageReferences : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.ApplicationPackageReferences" />
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
            <span data-ttu-id="3ca49-129">取得またはプール内の各コンピューティング ノードにインストールされているアプリケーション パッケージの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="3ca49-129">Gets or sets the list of application packages to be installed on each compute node in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoScaleEvaluationInterval">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; AutoScaleEvaluationInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; AutoScaleEvaluationInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.AutoScaleEvaluationInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoScaleEvaluationInterval As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.AutoScaleEvaluationInterval : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.AutoScaleEvaluationInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="autoScaleEvaluationInterval")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3ca49-130">取得または自動スケールの数式に従ってプールのサイズを自動的に調整するための時間間隔を設定します。</span><span class="sxs-lookup"><span data-stu-id="3ca49-130">Gets or sets the time interval at which to automatically adjust the pool size according to the autoscale formula.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="3ca49-131">既定値は、15 分です。</span><span class="sxs-lookup"><span data-stu-id="3ca49-131">The default value is 15 minutes.</span></span> <span data-ttu-id="3ca49-132">最小値と最大値は、それぞれ 5 分と 168 時間です。</span><span class="sxs-lookup"><span data-stu-id="3ca49-132">The minimum and maximum value are 5 minutes and 168 hours respectively.</span></span> <span data-ttu-id="3ca49-133">小さい値 5 分 168 時間より大きいかを指定すると、バッチ サービスは無効なプロパティ値エラー; で要求を拒否します。REST API を直接呼び出すが、HTTP ステータス コードは 400 (Bad Request) がします。</span><span class="sxs-lookup"><span data-stu-id="3ca49-133">If you specify a value less than 5 minutes or greater than 168 hours, the Batch service rejects the request with an invalid property value error; if you are calling the REST API directly, the HTTP status code is 400 (Bad Request).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoScaleFormula">
      <MemberSignature Language="C#" Value="public string AutoScaleFormula { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AutoScaleFormula" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.AutoScaleFormula" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoScaleFormula As String" />
      <MemberSignature Language="F#" Value="member this.AutoScaleFormula : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.AutoScaleFormula" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="autoScaleFormula")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3ca49-134">取得またはプールに目的のコンピューティング ノードの数の式を設定します。</span><span class="sxs-lookup"><span data-stu-id="3ca49-134">Gets or sets the formula for the desired number of compute nodes in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="3ca49-135">このプロパティがありますいない enableAutoScale が false に設定されているかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="3ca49-135">This property must not be specified if enableAutoScale is set to false.</span></span> <span data-ttu-id="3ca49-136">EnableAutoScale が設定されている場合は、必須を true にします。</span><span class="sxs-lookup"><span data-stu-id="3ca49-136">It is required if enableAutoScale is set to true.</span></span> <span data-ttu-id="3ca49-137">数式は、プールが作成される前に、有効性に対してチェックされます。</span><span class="sxs-lookup"><span data-stu-id="3ca49-137">The formula is checked for validity before the pool is created.</span></span> <span data-ttu-id="3ca49-138">数式が有効でない場合、Batch service は詳細なエラー情報が要求を拒否します。</span><span class="sxs-lookup"><span data-stu-id="3ca49-138">If the formula is not valid, the Batch service rejects the request with detailed error information.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateReferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; CertificateReferences { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; CertificateReferences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.CertificateReferences" />
      <MemberSignature Language="VB.NET" Value="Public Property CertificateReferences As IList(Of CertificateReference)" />
      <MemberSignature Language="F#" Value="member this.CertificateReferences : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.CertificateReferences" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="certificateReferences")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3ca49-139">取得またはプール内の各コンピューティング ノードにインストールされている証明書の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="3ca49-139">Gets or sets a list of certificates to be installed on each compute node in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="3ca49-140">Windows では、ノードを計算するため、バッチ サービスは、場所と指定された証明書ストアに証明書をインストールします。</span><span class="sxs-lookup"><span data-stu-id="3ca49-140">For Windows compute nodes, the Batch service installs the certificates to the specified certificate store and location.</span></span> <span data-ttu-id="3ca49-141">Linux 計算ノードでは、証明書は、タスクの作業ディレクトリと変数 AZ_BATCH_CERTIFICATES_DIR がこの場所にクエリするタスクに指定された環境の内部ディレクトリに保存されます。</span><span class="sxs-lookup"><span data-stu-id="3ca49-141">For Linux compute nodes, the certificates are stored in a directory inside the task working directory and an environment variable AZ_BATCH_CERTIFICATES_DIR is supplied to the task to query for this location.</span></span> <span data-ttu-id="3ca49-142">'RemoteUser' の可視性を持つ証明書は、'certs' ディレクトリは、ユーザーのホーム ディレクトリに作成 (など/home/{ユーザー名}/certs) および証明書はそのディレクトリに配置します。</span><span class="sxs-lookup"><span data-stu-id="3ca49-142">For certificates with visibility of 'remoteUser', a 'certs' directory is created in the user's home directory (e.g., /home/{user-name}/certs) and certificates are placed in that directory.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CloudServiceConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration CloudServiceConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration CloudServiceConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.CloudServiceConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property CloudServiceConfiguration As CloudServiceConfiguration" />
      <MemberSignature Language="F#" Value="member this.CloudServiceConfiguration : Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.CloudServiceConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="cloudServiceConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3ca49-143">取得またはプールをクラウド サービスの構成を設定します。</span><span class="sxs-lookup"><span data-stu-id="3ca49-143">Gets or sets the cloud service configuration for the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="3ca49-144">このプロパティを指定する必要があります指定されたかどうか、プールは PaaS の Azure Vm を作成する必要があります。</span><span class="sxs-lookup"><span data-stu-id="3ca49-144">This property must be specified if the pool needs to be created with Azure PaaS VMs.</span></span> <span data-ttu-id="3ca49-145">このプロパティと virtualMachineConfiguration は相互に排他的とプロパティのいずれかを指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="3ca49-145">This property and virtualMachineConfiguration are mutually exclusive and one of the properties must be specified.</span></span>
            <span data-ttu-id="3ca49-146">どちらも指定されてし、バッチ サービスはエラーを返します。REST API を直接呼び出すが、HTTP ステータス コードは 400 (Bad Request) がします。</span><span class="sxs-lookup"><span data-stu-id="3ca49-146">If neither is specified then the Batch service returns an error; if you are calling the REST API directly, the HTTP status code is 400 (Bad Request).</span></span> <span data-ttu-id="3ca49-147">このプロパティは、Batch アカウントが、poolAllocationMode プロパティ 'UserSubscription' に設定して作成されたかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="3ca49-147">This property cannot be specified if the Batch account was created with its poolAllocationMode property set to 'UserSubscription'.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.DisplayName" />
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
            <span data-ttu-id="3ca49-148">取得またはプールの表示名を設定します。</span><span class="sxs-lookup"><span data-stu-id="3ca49-148">Gets or sets the display name for the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="3ca49-149">表示名は一意でない必要があり、最大で 1,024 の最大長の Unicode 文字を含めることができます。</span><span class="sxs-lookup"><span data-stu-id="3ca49-149">The display name need not be unique and can contain any Unicode characters up to a maximum length of 1024.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableAutoScale">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableAutoScale { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableAutoScale" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.EnableAutoScale" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableAutoScale As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableAutoScale : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.EnableAutoScale" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="enableAutoScale")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3ca49-150">取得または時間の経過と共に、プールのサイズを自動的に調整するかどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="3ca49-150">Gets or sets whether the pool size should automatically adjust over time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="3ca49-151">False の場合、targetDedicateNodes と targetLowPriorityNodes の少なくとも 1 つ指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="3ca49-151">If false, at least one of targetDedicateNodes and targetLowPriorityNodes must be specified.</span></span> <span data-ttu-id="3ca49-152">True の場合、autoScaleFormula 要素が必要です。</span><span class="sxs-lookup"><span data-stu-id="3ca49-152">If true, the autoScaleFormula element is required.</span></span> <span data-ttu-id="3ca49-153">プールは、数式に従って自動的にサイズ変更します。</span><span class="sxs-lookup"><span data-stu-id="3ca49-153">The pool automatically resizes according to the formula.</span></span> <span data-ttu-id="3ca49-154">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="3ca49-154">The default value is false.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableInterNodeCommunication">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableInterNodeCommunication { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableInterNodeCommunication" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.EnableInterNodeCommunication" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableInterNodeCommunication As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableInterNodeCommunication : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.EnableInterNodeCommunication" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="enableInterNodeCommunication")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3ca49-155">取得またはプールがノード間で直接通信を許可するかどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="3ca49-155">Gets or sets whether the pool permits direct communication between nodes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="3ca49-156">ノード間通信を有効にすると、プールのノードの展開の制限により、プールの最大サイズが制限されます。</span><span class="sxs-lookup"><span data-stu-id="3ca49-156">Enabling inter-node communication limits the maximum size of the pool due to deployment restrictions on the nodes of the pool.</span></span> <span data-ttu-id="3ca49-157">これにより、プールが必要なサイズに到達しない可能性があります。</span><span class="sxs-lookup"><span data-stu-id="3ca49-157">This may result in the pool not reaching its desired size.</span></span> <span data-ttu-id="3ca49-158">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="3ca49-158">The default value is false.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxTasksPerNode">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxTasksPerNode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxTasksPerNode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.MaxTasksPerNode" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxTasksPerNode As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxTasksPerNode : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.MaxTasksPerNode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxTasksPerNode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3ca49-159">取得またはプール内の 1 つのコンピューティング ノードで同時に実行できるタスクの最大数を設定します。</span><span class="sxs-lookup"><span data-stu-id="3ca49-159">Gets or sets the maximum number of tasks that can run concurrently on a single compute node in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="3ca49-160">既定値は 1 です。</span><span class="sxs-lookup"><span data-stu-id="3ca49-160">The default value is 1.</span></span> <span data-ttu-id="3ca49-161">この設定の最大値は、(vmSize 設定)、プール内の計算ノードのサイズによって異なります。</span><span class="sxs-lookup"><span data-stu-id="3ca49-161">The maximum value of this setting depends on the size of the compute nodes in the pool (the vmSize setting).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; Metadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public Property Metadata As IList(Of MetadataItem)" />
      <MemberSignature Language="F#" Value="member this.Metadata : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.Metadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="metadata")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3ca49-162">取得またはメタデータとしてプールに関連付けられている名前と値のペアの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="3ca49-162">Gets or sets a list of name-value pairs associated with the pool as metadata.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="3ca49-163">バッチ サービスがメタデータに意味を割り当てませんこれは、ユーザー コードを使用するためだけです。</span><span class="sxs-lookup"><span data-stu-id="3ca49-163">The Batch service does not assign any meaning to metadata; it is solely for the use of user code.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration NetworkConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration NetworkConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.NetworkConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkConfiguration As NetworkConfiguration" />
      <MemberSignature Language="F#" Value="member this.NetworkConfiguration : Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.NetworkConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="networkConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3ca49-164">取得またはプールのネットワーク構成を設定します。</span><span class="sxs-lookup"><span data-stu-id="3ca49-164">Gets or sets the network configuration for the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResizeTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; ResizeTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; ResizeTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.ResizeTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property ResizeTimeout As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.ResizeTimeout : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.ResizeTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resizeTimeout")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3ca49-165">取得またはプールに割り当てるコンピューティング ノードの場合のタイムアウトを設定します。</span><span class="sxs-lookup"><span data-stu-id="3ca49-165">Gets or sets the timeout for allocation of compute nodes to the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="3ca49-166">このタイムアウトは手動スケール; にのみ適用されます。影響を与えません enableAutoScale が設定されている場合に true に設定します。</span><span class="sxs-lookup"><span data-stu-id="3ca49-166">This timeout applies only to manual scaling; it has no effect when enableAutoScale is set to true.</span></span> <span data-ttu-id="3ca49-167">既定値は、15 分です。</span><span class="sxs-lookup"><span data-stu-id="3ca49-167">The default value is 15 minutes.</span></span>
            <span data-ttu-id="3ca49-168">最小値は、5 分です。</span><span class="sxs-lookup"><span data-stu-id="3ca49-168">The minimum value is 5 minutes.</span></span> <span data-ttu-id="3ca49-169">5 分より小さい値を指定する場合、バッチ サービスがエラー; で要求を拒否します。REST API を直接呼び出すが、HTTP ステータス コードは 400 (Bad Request) がします。</span><span class="sxs-lookup"><span data-stu-id="3ca49-169">If you specify a value less than 5 minutes, the Batch service rejects the request with an error; if you are calling the REST API directly, the HTTP status code is 400 (Bad Request).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.StartTask StartTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.StartTask StartTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.StartTask" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTask As StartTask" />
      <MemberSignature Language="F#" Value="member this.StartTask : Microsoft.Azure.Batch.Protocol.Models.StartTask with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.StartTask" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startTask")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.StartTask</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3ca49-170">取得またはプールを結合として各コンピューティング ノード上で実行するタスクを設定します。</span><span class="sxs-lookup"><span data-stu-id="3ca49-170">Gets or sets a task to run on each compute node as it joins the pool.</span></span> <span data-ttu-id="3ca49-171">タスクは、プールに、または、ノードが再起動されたときに、ノードが追加されたときに実行されます。</span><span class="sxs-lookup"><span data-stu-id="3ca49-171">The task runs when the node is added to the pool or when the node is restarted.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetDedicatedNodes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TargetDedicatedNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TargetDedicatedNodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.TargetDedicatedNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetDedicatedNodes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TargetDedicatedNodes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.TargetDedicatedNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetDedicatedNodes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3ca49-172">取得またはプールの目的専用のコンピューティング ノードの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="3ca49-172">Gets or sets the desired number of dedicated compute nodes in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="3ca49-173">このプロパティがありますいない enableAutoScale が設定されているかどうかは指定されたを true にします。</span><span class="sxs-lookup"><span data-stu-id="3ca49-173">This property must not be specified if enableAutoScale is set to true.</span></span> <span data-ttu-id="3ca49-174">EnableAutoScale が false に設定されている場合は、targetDedicatedNodes、targetLowPriorityNodes、またはその両方を設定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="3ca49-174">If enableAutoScale is set to false, then you must set either targetDedicatedNodes, targetLowPriorityNodes, or both.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetLowPriorityNodes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TargetLowPriorityNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TargetLowPriorityNodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.TargetLowPriorityNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetLowPriorityNodes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TargetLowPriorityNodes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.TargetLowPriorityNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetLowPriorityNodes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3ca49-175">取得またはプールに目的の優先度の低いコンピューティング ノードの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="3ca49-175">Gets or sets the desired number of low-priority compute nodes in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="3ca49-176">このプロパティがありますいない enableAutoScale が設定されているかどうかは指定されたを true にします。</span><span class="sxs-lookup"><span data-stu-id="3ca49-176">This property must not be specified if enableAutoScale is set to true.</span></span> <span data-ttu-id="3ca49-177">EnableAutoScale が false に設定されている場合は、targetDedicatedNodes、targetLowPriorityNodes、またはその両方を設定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="3ca49-177">If enableAutoScale is set to false, then you must set either targetDedicatedNodes, targetLowPriorityNodes, or both.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskSchedulingPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskSchedulingPolicy TaskSchedulingPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskSchedulingPolicy TaskSchedulingPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.TaskSchedulingPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property TaskSchedulingPolicy As TaskSchedulingPolicy" />
      <MemberSignature Language="F#" Value="member this.TaskSchedulingPolicy : Microsoft.Azure.Batch.Protocol.Models.TaskSchedulingPolicy with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.TaskSchedulingPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="taskSchedulingPolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskSchedulingPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3ca49-178">取得またはタスクのプール内のコンピューティング ノード間で配分する方法を設定します。</span><span class="sxs-lookup"><span data-stu-id="3ca49-178">Gets or sets how tasks are distributed across compute nodes in a pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserAccounts">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.UserAccount&gt; UserAccounts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.UserAccount&gt; UserAccounts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.UserAccounts" />
      <MemberSignature Language="VB.NET" Value="Public Property UserAccounts As IList(Of UserAccount)" />
      <MemberSignature Language="F#" Value="member this.UserAccounts : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.UserAccount&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.UserAccounts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="userAccounts")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.UserAccount&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3ca49-179">取得またはプール内の各ノード上に作成されるユーザー アカウントの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="3ca49-179">Gets or sets the list of user accounts to be created on each node in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="poolSpecification.Validate " />
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
            <span data-ttu-id="3ca49-180">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="3ca49-180">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="3ca49-181">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="3ca49-181">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration VirtualMachineConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration VirtualMachineConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.VirtualMachineConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualMachineConfiguration As VirtualMachineConfiguration" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineConfiguration : Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.VirtualMachineConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="virtualMachineConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3ca49-182">取得またはプールの仮想マシンの構成を設定します。</span><span class="sxs-lookup"><span data-stu-id="3ca49-182">Gets or sets the virtual machine configuration for the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="3ca49-183">このプロパティを指定する必要があります、プールを Azure IaaS Vm を作成する必要があるかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="3ca49-183">This property must be specified if the pool needs to be created with Azure IaaS VMs.</span></span> <span data-ttu-id="3ca49-184">このプロパティと cloudServiceConfiguration は相互に排他的とプロパティのいずれかを指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="3ca49-184">This property and cloudServiceConfiguration are mutually exclusive and one of the properties must be specified.</span></span>
            <span data-ttu-id="3ca49-185">どちらも指定されてし、バッチ サービスはエラーを返します。REST API を直接呼び出すが、HTTP ステータス コードは 400 (Bad Request) がします。</span><span class="sxs-lookup"><span data-stu-id="3ca49-185">If neither is specified then the Batch service returns an error; if you are calling the REST API directly, the HTTP status code is 400 (Bad Request).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="VmSize">
      <MemberSignature Language="C#" Value="public string VmSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VmSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.VmSize" />
      <MemberSignature Language="VB.NET" Value="Public Property VmSize As String" />
      <MemberSignature Language="F#" Value="member this.VmSize : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolSpecification.VmSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="vmSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3ca49-186">取得またはプール内の仮想マシンのサイズを設定します。</span><span class="sxs-lookup"><span data-stu-id="3ca49-186">Gets or sets the size of the virtual machines in the pool.</span></span> <span data-ttu-id="3ca49-187">プール内の仮想マシンのサイズはすべて同じです。</span><span class="sxs-lookup"><span data-stu-id="3ca49-187">All virtual machines in a pool are the same size.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="3ca49-188">クラウド サービス プール (プール cloudServiceConfiguration で作成された) の仮想マシンの利用可能なサイズについては、クラウド サービス (http://azure.microsoft.com/documentation/articles/cloud-services-sizes-specs/) のサイズを参照してください。</span><span class="sxs-lookup"><span data-stu-id="3ca49-188">For information about available sizes of virtual machines for Cloud Services pools (pools created with cloudServiceConfiguration), see Sizes for Cloud Services (http://azure.microsoft.com/documentation/articles/cloud-services-sizes-specs/).</span></span>
            <span data-ttu-id="3ca49-189">バッチには、ExtraSmall、A1V2 A2V2 を除くすべてのクラウド サービス VM サイズがサポートしています。</span><span class="sxs-lookup"><span data-stu-id="3ca49-189">Batch supports all Cloud Services VM sizes except ExtraSmall, A1V2 and A2V2.</span></span> <span data-ttu-id="3ca49-190">(プール virtualMachineConfiguration で作成した) 仮想マシンのマーケットプ レースからイメージを使用するプールの利用可能な VM サイズについては (Linux) (https://azure.microsoft.com/documentation/articles/ の仮想マシンのサイズを参照してください。仮想マシンの linux-サイズ/) または仮想マシン (Windows) (https://azure.microsoft.com/documentation/articles/virtual-machines-windows-sizes/) のサイズ。</span><span class="sxs-lookup"><span data-stu-id="3ca49-190">For information about available VM sizes for pools using images from the Virtual Machines Marketplace (pools created with virtualMachineConfiguration) see Sizes for Virtual Machines (Linux) (https://azure.microsoft.com/documentation/articles/virtual-machines-linux-sizes/) or Sizes for Virtual Machines (Windows) (https://azure.microsoft.com/documentation/articles/virtual-machines-windows-sizes/).</span></span>
            <span data-ttu-id="3ca49-191">バッチには、STANDARD_A0 と premium storage (STANDARD_GS、STANDARD_DS、および STANDARD_DSV2 シリーズ) でそれらを除くすべての Azure VM サイズがサポートしています。</span><span class="sxs-lookup"><span data-stu-id="3ca49-191">Batch supports all Azure VM sizes except STANDARD_A0 and those with premium storage (STANDARD_GS, STANDARD_DS, and STANDARD_DSV2 series).</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>