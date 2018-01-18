<Type Name="PoolAddParameter" FullName="Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter">
  <TypeSignature Language="C#" Value="public class PoolAddParameter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PoolAddParameter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter" />
  <TypeSignature Language="VB.NET" Value="Public Class PoolAddParameter" />
  <TypeSignature Language="F#" Value="type PoolAddParameter = class" />
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
            <span data-ttu-id="41738-101">Azure Batch サービスを追加するにプールします。</span><span class="sxs-lookup"><span data-stu-id="41738-101">A pool in the Azure Batch service to add.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolAddParameter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.#ctor" />
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
            <span data-ttu-id="41738-102">PoolAddParameter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="41738-102">Initializes a new instance of the PoolAddParameter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolAddParameter (string id, string vmSize, string displayName = null, Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration cloudServiceConfiguration = null, Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration virtualMachineConfiguration = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, Nullable&lt;int&gt; targetDedicatedNodes = null, Nullable&lt;int&gt; targetLowPriorityNodes = null, Nullable&lt;bool&gt; enableAutoScale = null, string autoScaleFormula = null, Nullable&lt;TimeSpan&gt; autoScaleEvaluationInterval = null, Nullable&lt;bool&gt; enableInterNodeCommunication = null, Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration networkConfiguration = null, Microsoft.Azure.Batch.Protocol.Models.StartTask startTask = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; certificateReferences = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; applicationPackageReferences = null, System.Collections.Generic.IList&lt;string&gt; applicationLicenses = null, Nullable&lt;int&gt; maxTasksPerNode = null, Microsoft.Azure.Batch.Protocol.Models.TaskSchedulingPolicy taskSchedulingPolicy = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.UserAccount&gt; userAccounts = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; metadata = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string vmSize, string displayName, class Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration cloudServiceConfiguration, class Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration virtualMachineConfiguration, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, valuetype System.Nullable`1&lt;int32&gt; targetDedicatedNodes, valuetype System.Nullable`1&lt;int32&gt; targetLowPriorityNodes, valuetype System.Nullable`1&lt;bool&gt; enableAutoScale, string autoScaleFormula, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; autoScaleEvaluationInterval, valuetype System.Nullable`1&lt;bool&gt; enableInterNodeCommunication, class Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration networkConfiguration, class Microsoft.Azure.Batch.Protocol.Models.StartTask startTask, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; certificateReferences, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; applicationPackageReferences, class System.Collections.Generic.IList`1&lt;string&gt; applicationLicenses, valuetype System.Nullable`1&lt;int32&gt; maxTasksPerNode, class Microsoft.Azure.Batch.Protocol.Models.TaskSchedulingPolicy taskSchedulingPolicy, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.UserAccount&gt; userAccounts, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; metadata) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.#ctor(System.String,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration,Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration,System.Nullable{System.TimeSpan},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Boolean},System.String,System.Nullable{System.TimeSpan},System.Nullable{System.Boolean},Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration,Microsoft.Azure.Batch.Protocol.Models.StartTask,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.CertificateReference},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference},System.Collections.Generic.IList{System.String},System.Nullable{System.Int32},Microsoft.Azure.Batch.Protocol.Models.TaskSchedulingPolicy,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.UserAccount},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.MetadataItem})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter : string * string * string * Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration * Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration * Nullable&lt;TimeSpan&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;bool&gt; * string * Nullable&lt;TimeSpan&gt; * Nullable&lt;bool&gt; * Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration * Microsoft.Azure.Batch.Protocol.Models.StartTask * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;int&gt; * Microsoft.Azure.Batch.Protocol.Models.TaskSchedulingPolicy * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.UserAccount&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter" Usage="new Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter (id, vmSize, displayName, cloudServiceConfiguration, virtualMachineConfiguration, resizeTimeout, targetDedicatedNodes, targetLowPriorityNodes, enableAutoScale, autoScaleFormula, autoScaleEvaluationInterval, enableInterNodeCommunication, networkConfiguration, startTask, certificateReferences, applicationPackageReferences, applicationLicenses, maxTasksPerNode, taskSchedulingPolicy, userAccounts, metadata)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="vmSize" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="cloudServiceConfiguration" Type="Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration" />
        <Parameter Name="virtualMachineConfiguration" Type="Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration" />
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
        <Parameter Name="maxTasksPerNode" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="taskSchedulingPolicy" Type="Microsoft.Azure.Batch.Protocol.Models.TaskSchedulingPolicy" />
        <Parameter Name="userAccounts" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.UserAccount&gt;" />
        <Parameter Name="metadata" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="41738-103">アカウント内のプールを一意に識別する文字列。</span><span class="sxs-lookup"><span data-stu-id="41738-103">A string that uniquely identifies the pool within the account.</span></span></param>
        <param name="vmSize"><span data-ttu-id="41738-104">プール内の仮想マシンのサイズ。</span><span class="sxs-lookup"><span data-stu-id="41738-104">The size of virtual machines in the pool.</span></span> <span data-ttu-id="41738-105">プール内の仮想マシンのサイズはすべて同じです。</span><span class="sxs-lookup"><span data-stu-id="41738-105">All virtual machines in a pool are the same size.</span></span></param>
        <param name="displayName"><span data-ttu-id="41738-106">プールの表示名。</span><span class="sxs-lookup"><span data-stu-id="41738-106">The display name for the pool.</span></span></param>
        <param name="cloudServiceConfiguration"><span data-ttu-id="41738-107">プールのクラウドサービス構成。</span><span class="sxs-lookup"><span data-stu-id="41738-107">The cloud service configuration for the pool.</span></span></param>
        <param name="virtualMachineConfiguration"><span data-ttu-id="41738-108">プールの仮想マシン構成。</span><span class="sxs-lookup"><span data-stu-id="41738-108">The virtual machine configuration for the pool.</span></span></param>
        <param name="resizeTimeout"><span data-ttu-id="41738-109">プールにコンピューティング ノードの割り当てのタイムアウト。</span><span class="sxs-lookup"><span data-stu-id="41738-109">The timeout for allocation of compute nodes to the pool.</span></span></param>
        <param name="targetDedicatedNodes"><span data-ttu-id="41738-110">専用の目的の数は、プール内のノードを計算します。</span><span class="sxs-lookup"><span data-stu-id="41738-110">The desired number of dedicated compute nodes in the pool.</span></span></param>
        <param name="targetLowPriorityNodes"><span data-ttu-id="41738-111">目的の優先度の低い数は、プール内のノードを計算します。</span><span class="sxs-lookup"><span data-stu-id="41738-111">The desired number of low-priority compute nodes in the pool.</span></span></param>
        <param name="enableAutoScale"><span data-ttu-id="41738-112">かどうか、プールのサイズは、時間の経過と共に自動的に調整する必要があります。</span><span class="sxs-lookup"><span data-stu-id="41738-112">Whether the pool size should automatically adjust over time.</span></span></param>
        <param name="autoScaleFormula"><span data-ttu-id="41738-113">プール内の計算ノードの必要な数の式。</span><span class="sxs-lookup"><span data-stu-id="41738-113">A formula for the desired number of compute nodes in the pool.</span></span></param>
        <param name="autoScaleEvaluationInterval"><span data-ttu-id="41738-114">自動スケールの数式に従ってプールのサイズを自動的に調整する時間間隔。</span><span class="sxs-lookup"><span data-stu-id="41738-114">The time interval at which to automatically adjust the pool size according to the autoscale formula.</span></span></param>
        <param name="enableInterNodeCommunication"><span data-ttu-id="41738-115">かどうか、プールは、ノード間の直接通信を許可します。</span><span class="sxs-lookup"><span data-stu-id="41738-115">Whether the pool permits direct communication between nodes.</span></span></param>
        <param name="networkConfiguration"><span data-ttu-id="41738-116">プールのネットワーク構成。</span><span class="sxs-lookup"><span data-stu-id="41738-116">The network configuration for the pool.</span></span></param>
        <param name="startTask"><span data-ttu-id="41738-117">各コンピューティング ノードで、プールに参加を実行する指定されたタスク。</span><span class="sxs-lookup"><span data-stu-id="41738-117">A task specified to run on each compute node as it joins the pool.</span></span></param>
        <param name="certificateReferences"><span data-ttu-id="41738-118">プール内の各コンピューティング ノードにインストールされている証明書の一覧です。</span><span class="sxs-lookup"><span data-stu-id="41738-118">The list of certificates to be installed on each compute node in the pool.</span></span></param>
        <param name="applicationPackageReferences"><span data-ttu-id="41738-119">プール内の各コンピューティング ノードにインストールされているアプリケーション パッケージの一覧。</span><span class="sxs-lookup"><span data-stu-id="41738-119">The list of application packages to be installed on each compute node in the pool.</span></span></param>
        <param name="applicationLicenses"><span data-ttu-id="41738-120">アプリケーションの一覧のライセンスは、バッチ サービスは、プール内の各コンピューティング ノードで使用できるようにします。</span><span class="sxs-lookup"><span data-stu-id="41738-120">The list of application licenses the Batch service will make available on each compute node in the pool.</span></span></param>
        <param name="maxTasksPerNode"><span data-ttu-id="41738-121">プール内の単一コンピューティング ノードで同時に実行できるタスクの最大数。</span><span class="sxs-lookup"><span data-stu-id="41738-121">The maximum number of tasks that can run concurrently on a single compute node in the pool.</span></span></param>
        <param name="taskSchedulingPolicy"><span data-ttu-id="41738-122">どのタスクはプール内のコンピューティング ノード間で分散されます。</span><span class="sxs-lookup"><span data-stu-id="41738-122">How tasks are distributed across compute nodes in a pool.</span></span></param>
        <param name="userAccounts"><span data-ttu-id="41738-123">プール内の各ノード上に作成されるユーザー アカウントの一覧です。</span><span class="sxs-lookup"><span data-stu-id="41738-123">The list of user accounts to be created on each node in the pool.</span></span></param>
        <param name="metadata"><span data-ttu-id="41738-124">メタデータとしてプールに関連付けられている名前と値のペアの一覧。</span><span class="sxs-lookup"><span data-stu-id="41738-124">A list of name-value pairs associated with the pool as metadata.</span></span></param>
        <summary>
            <span data-ttu-id="41738-125">PoolAddParameter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="41738-125">Initializes a new instance of the PoolAddParameter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationLicenses">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ApplicationLicenses { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ApplicationLicenses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.ApplicationLicenses" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationLicenses As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ApplicationLicenses : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.ApplicationLicenses" />
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
            <span data-ttu-id="41738-126">取得またはアプリケーションのライセンスの一覧をバッチ サービスは、プール内の各コンピューティング ノードで使用できるように設定します。</span><span class="sxs-lookup"><span data-stu-id="41738-126">Gets or sets the list of application licenses the Batch service will make available on each compute node in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="41738-127">アプリケーションのライセンスの一覧は、使用できる Batch サービス アプリケーションのライセンスのサブセットである必要があります。</span><span class="sxs-lookup"><span data-stu-id="41738-127">The list of application licenses must be a subset of available Batch service application licenses.</span></span> <span data-ttu-id="41738-128">これはサポートされていない要求されるライセンスと、プールの作成は失敗します。</span><span class="sxs-lookup"><span data-stu-id="41738-128">If a license is requested which is not supported, pool creation will fail.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationPackageReferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; ApplicationPackageReferences { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; ApplicationPackageReferences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.ApplicationPackageReferences" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationPackageReferences As IList(Of ApplicationPackageReference)" />
      <MemberSignature Language="F#" Value="member this.ApplicationPackageReferences : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.ApplicationPackageReferences" />
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
            <span data-ttu-id="41738-129">取得またはプール内の各コンピューティング ノードにインストールされているアプリケーション パッケージの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="41738-129">Gets or sets the list of application packages to be installed on each compute node in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoScaleEvaluationInterval">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; AutoScaleEvaluationInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; AutoScaleEvaluationInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.AutoScaleEvaluationInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoScaleEvaluationInterval As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.AutoScaleEvaluationInterval : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.AutoScaleEvaluationInterval" />
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
            <span data-ttu-id="41738-130">取得または自動スケールの数式に従ってプールのサイズを自動的に調整するための時間間隔を設定します。</span><span class="sxs-lookup"><span data-stu-id="41738-130">Gets or sets the time interval at which to automatically adjust the pool size according to the autoscale formula.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="41738-131">既定値は、15 分です。</span><span class="sxs-lookup"><span data-stu-id="41738-131">The default value is 15 minutes.</span></span> <span data-ttu-id="41738-132">最小値と最大値は、それぞれ 5 分と 168 時間です。</span><span class="sxs-lookup"><span data-stu-id="41738-132">The minimum and maximum value are 5 minutes and 168 hours respectively.</span></span> <span data-ttu-id="41738-133">小さい値 5 分 168 時間より大きいかを指定すると、バッチ サービスは; エラーを返しますREST API を直接呼び出すが、HTTP ステータス コードは 400 (Bad Request) がします。</span><span class="sxs-lookup"><span data-stu-id="41738-133">If you specify a value less than 5 minutes or greater than 168 hours, the Batch service returns an error; if you are calling the REST API directly, the HTTP status code is 400 (Bad Request).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoScaleFormula">
      <MemberSignature Language="C#" Value="public string AutoScaleFormula { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AutoScaleFormula" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.AutoScaleFormula" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoScaleFormula As String" />
      <MemberSignature Language="F#" Value="member this.AutoScaleFormula : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.AutoScaleFormula" />
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
            <span data-ttu-id="41738-134">取得またはプール内の式の目的のコンピューティング ノードの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="41738-134">Gets or sets a formula for the desired number of compute nodes in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="41738-135">このプロパティがありますいない enableAutoScale が false に設定されているかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="41738-135">This property must not be specified if enableAutoScale is set to false.</span></span> <span data-ttu-id="41738-136">EnableAutoScale が設定されている場合は、必須を true にします。</span><span class="sxs-lookup"><span data-stu-id="41738-136">It is required if enableAutoScale is set to true.</span></span> <span data-ttu-id="41738-137">数式は、プールが作成される前に、有効性に対してチェックされます。</span><span class="sxs-lookup"><span data-stu-id="41738-137">The formula is checked for validity before the pool is created.</span></span> <span data-ttu-id="41738-138">数式が有効でない場合、Batch service は詳細なエラー情報が要求を拒否します。</span><span class="sxs-lookup"><span data-stu-id="41738-138">If the formula is not valid, the Batch service rejects the request with detailed error information.</span></span> <span data-ttu-id="41738-139">この式の指定に関する詳細については、'自動的に Azure Batch プール内のノードをコンピューティング スケール' を参照してください (https://azure.microsoft.com/documentation/articles/batch-automatic-scaling/)。</span><span class="sxs-lookup"><span data-stu-id="41738-139">For more information about specifying this formula, see 'Automatically scale compute nodes in an Azure Batch pool' (https://azure.microsoft.com/documentation/articles/batch-automatic-scaling/).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateReferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; CertificateReferences { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; CertificateReferences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.CertificateReferences" />
      <MemberSignature Language="VB.NET" Value="Public Property CertificateReferences As IList(Of CertificateReference)" />
      <MemberSignature Language="F#" Value="member this.CertificateReferences : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.CertificateReferences" />
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
            <span data-ttu-id="41738-140">取得またはプール内の各コンピューティング ノードにインストールされている証明書の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="41738-140">Gets or sets the list of certificates to be installed on each compute node in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="41738-141">Windows では、ノードを計算するため、バッチ サービスは、場所と指定された証明書ストアに証明書をインストールします。</span><span class="sxs-lookup"><span data-stu-id="41738-141">For Windows compute nodes, the Batch service installs the certificates to the specified certificate store and location.</span></span> <span data-ttu-id="41738-142">Linux 計算ノードでは、証明書は、タスクの作業ディレクトリと変数 AZ_BATCH_CERTIFICATES_DIR がこの場所にクエリするタスクに指定された環境の内部ディレクトリに保存されます。</span><span class="sxs-lookup"><span data-stu-id="41738-142">For Linux compute nodes, the certificates are stored in a directory inside the task working directory and an environment variable AZ_BATCH_CERTIFICATES_DIR is supplied to the task to query for this location.</span></span> <span data-ttu-id="41738-143">'RemoteUser' の可視性を持つ証明書は、'certs' ディレクトリは、ユーザーのホーム ディレクトリに作成 (など/home/{ユーザー名}/certs) および証明書はそのディレクトリに配置します。</span><span class="sxs-lookup"><span data-stu-id="41738-143">For certificates with visibility of 'remoteUser', a 'certs' directory is created in the user's home directory (e.g., /home/{user-name}/certs) and certificates are placed in that directory.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CloudServiceConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration CloudServiceConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration CloudServiceConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.CloudServiceConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property CloudServiceConfiguration As CloudServiceConfiguration" />
      <MemberSignature Language="F#" Value="member this.CloudServiceConfiguration : Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.CloudServiceConfiguration" />
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
            <span data-ttu-id="41738-144">取得またはプールをクラウド サービスの構成を設定します。</span><span class="sxs-lookup"><span data-stu-id="41738-144">Gets or sets the cloud service configuration for the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="41738-145">このプロパティと virtualMachineConfiguration は相互に排他的とプロパティのいずれかを指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="41738-145">This property and virtualMachineConfiguration are mutually exclusive and one of the properties must be specified.</span></span> <span data-ttu-id="41738-146">このプロパティは、Batch アカウントが、poolAllocationMode プロパティ 'UserSubscription' に設定して作成されたかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="41738-146">This property cannot be specified if the Batch account was created with its poolAllocationMode property set to 'UserSubscription'.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.DisplayName" />
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
            <span data-ttu-id="41738-147">取得またはプールの表示名を設定します。</span><span class="sxs-lookup"><span data-stu-id="41738-147">Gets or sets the display name for the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="41738-148">表示名は一意でない必要があり、最大で 1,024 の最大長の Unicode 文字を含めることができます。</span><span class="sxs-lookup"><span data-stu-id="41738-148">The display name need not be unique and can contain any Unicode characters up to a maximum length of 1024.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableAutoScale">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableAutoScale { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableAutoScale" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.EnableAutoScale" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableAutoScale As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableAutoScale : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.EnableAutoScale" />
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
            <span data-ttu-id="41738-149">取得または時間の経過と共に、プールのサイズを自動的に調整するかどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="41738-149">Gets or sets whether the pool size should automatically adjust over time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="41738-150">False の場合、targetDedicateNodes と targetLowPriorityNodes の少なくとも 1 つ指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="41738-150">If false, at least one of targetDedicateNodes and targetLowPriorityNodes must be specified.</span></span> <span data-ttu-id="41738-151">True の場合は、autoScaleFormula プロパティは必須と数式に従ってプールが自動的にサイズ変更します。</span><span class="sxs-lookup"><span data-stu-id="41738-151">If true, the autoScaleFormula property is required and the pool automatically resizes according to the formula.</span></span> <span data-ttu-id="41738-152">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="41738-152">The default value is false.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableInterNodeCommunication">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableInterNodeCommunication { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableInterNodeCommunication" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.EnableInterNodeCommunication" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableInterNodeCommunication As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableInterNodeCommunication : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.EnableInterNodeCommunication" />
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
            <span data-ttu-id="41738-153">取得またはプールがノード間で直接通信を許可するかどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="41738-153">Gets or sets whether the pool permits direct communication between nodes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="41738-154">ノード間通信を有効にすると、プールのノードの展開の制限により、プールの最大サイズが制限されます。</span><span class="sxs-lookup"><span data-stu-id="41738-154">Enabling inter-node communication limits the maximum size of the pool due to deployment restrictions on the nodes of the pool.</span></span> <span data-ttu-id="41738-155">これにより、プールが必要なサイズに到達しない可能性があります。</span><span class="sxs-lookup"><span data-stu-id="41738-155">This may result in the pool not reaching its desired size.</span></span> <span data-ttu-id="41738-156">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="41738-156">The default value is false.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.Id" />
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
            <span data-ttu-id="41738-157">取得またはアカウント内のプールを一意に識別する文字列を設定します。</span><span class="sxs-lookup"><span data-stu-id="41738-157">Gets or sets a string that uniquely identifies the pool within the account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="41738-158">ID は、ハイフン、アンダー スコアを含む、英数字の任意の組み合わせを含めることができ、64 を超える文字を含めることはできません。</span><span class="sxs-lookup"><span data-stu-id="41738-158">The ID can contain any combination of alphanumeric characters including hyphens and underscores, and cannot contain more than 64 characters.</span></span> <span data-ttu-id="41738-159">ID は大文字と小文字を区別 (つまり、大文字小文字によってのみが異なる 2 つのプール Id アカウント内ではありません必要があります)。</span><span class="sxs-lookup"><span data-stu-id="41738-159">The ID is case-preserving and case-insensitive (that is, you may not have two pool IDs within an account that differ only by case).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxTasksPerNode">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxTasksPerNode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxTasksPerNode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.MaxTasksPerNode" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxTasksPerNode As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxTasksPerNode : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.MaxTasksPerNode" />
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
            <span data-ttu-id="41738-160">取得またはプール内の 1 つのコンピューティング ノードで同時に実行できるタスクの最大数を設定します。</span><span class="sxs-lookup"><span data-stu-id="41738-160">Gets or sets the maximum number of tasks that can run concurrently on a single compute node in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="41738-161">既定値は 1 です。</span><span class="sxs-lookup"><span data-stu-id="41738-161">The default value is 1.</span></span> <span data-ttu-id="41738-162">この設定の最大値は、(vmSize 設定)、プール内の計算ノードのサイズによって異なります。</span><span class="sxs-lookup"><span data-stu-id="41738-162">The maximum value of this setting depends on the size of the compute nodes in the pool (the vmSize setting).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; Metadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public Property Metadata As IList(Of MetadataItem)" />
      <MemberSignature Language="F#" Value="member this.Metadata : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.Metadata" />
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
            <span data-ttu-id="41738-163">取得またはメタデータとしてプールに関連付けられている名前と値のペアの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="41738-163">Gets or sets a list of name-value pairs associated with the pool as metadata.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="41738-164">バッチ サービスがメタデータに意味を割り当てませんこれは、ユーザー コードを使用するためだけです。</span><span class="sxs-lookup"><span data-stu-id="41738-164">The Batch service does not assign any meaning to metadata; it is solely for the use of user code.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration NetworkConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration NetworkConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.NetworkConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkConfiguration As NetworkConfiguration" />
      <MemberSignature Language="F#" Value="member this.NetworkConfiguration : Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.NetworkConfiguration" />
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
            <span data-ttu-id="41738-165">取得またはプールのネットワーク構成を設定します。</span><span class="sxs-lookup"><span data-stu-id="41738-165">Gets or sets the network configuration for the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResizeTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; ResizeTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; ResizeTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.ResizeTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property ResizeTimeout As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.ResizeTimeout : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.ResizeTimeout" />
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
            <span data-ttu-id="41738-166">取得またはプールに割り当てるコンピューティング ノードの場合のタイムアウトを設定します。</span><span class="sxs-lookup"><span data-stu-id="41738-166">Gets or sets the timeout for allocation of compute nodes to the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="41738-167">このタイムアウトは手動スケール; にのみ適用されます。影響を与えません enableAutoScale が設定されている場合に true に設定します。</span><span class="sxs-lookup"><span data-stu-id="41738-167">This timeout applies only to manual scaling; it has no effect when enableAutoScale is set to true.</span></span> <span data-ttu-id="41738-168">既定値は、15 分です。</span><span class="sxs-lookup"><span data-stu-id="41738-168">The default value is 15 minutes.</span></span>
            <span data-ttu-id="41738-169">最小値は、5 分です。</span><span class="sxs-lookup"><span data-stu-id="41738-169">The minimum value is 5 minutes.</span></span> <span data-ttu-id="41738-170">5 分より小さい値を指定する場合、Batch service が; エラーを返しますREST API を直接呼び出すが、HTTP ステータス コードは 400 (Bad Request) がします。</span><span class="sxs-lookup"><span data-stu-id="41738-170">If you specify a value less than 5 minutes, the Batch service returns an error; if you are calling the REST API directly, the HTTP status code is 400 (Bad Request).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.StartTask StartTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.StartTask StartTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.StartTask" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTask As StartTask" />
      <MemberSignature Language="F#" Value="member this.StartTask : Microsoft.Azure.Batch.Protocol.Models.StartTask with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.StartTask" />
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
            <span data-ttu-id="41738-171">取得または各コンピューティング ノードで、プールに参加を実行する指定されたタスクを設定します。</span><span class="sxs-lookup"><span data-stu-id="41738-171">Gets or sets a task specified to run on each compute node as it joins the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="41738-172">タスクは、プールに、または、ノードが再起動されたときに、ノードが追加されたときに実行されます。</span><span class="sxs-lookup"><span data-stu-id="41738-172">The task runs when the node is added to the pool or when the node is restarted.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetDedicatedNodes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TargetDedicatedNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TargetDedicatedNodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.TargetDedicatedNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetDedicatedNodes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TargetDedicatedNodes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.TargetDedicatedNodes" />
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
            <span data-ttu-id="41738-173">取得またはプールの目的専用のコンピューティング ノードの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="41738-173">Gets or sets the desired number of dedicated compute nodes in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="41738-174">このプロパティがありますいない enableAutoScale が設定されているかどうかは指定されたを true にします。</span><span class="sxs-lookup"><span data-stu-id="41738-174">This property must not be specified if enableAutoScale is set to true.</span></span> <span data-ttu-id="41738-175">EnableAutoScale が false に設定されている場合は、targetDedicatedNodes、targetLowPriorityNodes、またはその両方を設定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="41738-175">If enableAutoScale is set to false, then you must set either targetDedicatedNodes, targetLowPriorityNodes, or both.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetLowPriorityNodes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TargetLowPriorityNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TargetLowPriorityNodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.TargetLowPriorityNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetLowPriorityNodes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TargetLowPriorityNodes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.TargetLowPriorityNodes" />
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
            <span data-ttu-id="41738-176">取得またはプールに目的の優先度の低いコンピューティング ノードの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="41738-176">Gets or sets the desired number of low-priority compute nodes in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="41738-177">このプロパティがありますいない enableAutoScale が設定されているかどうかは指定されたを true にします。</span><span class="sxs-lookup"><span data-stu-id="41738-177">This property must not be specified if enableAutoScale is set to true.</span></span> <span data-ttu-id="41738-178">EnableAutoScale が false に設定されている場合は、targetDedicatedNodes、targetLowPriorityNodes、またはその両方を設定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="41738-178">If enableAutoScale is set to false, then you must set either targetDedicatedNodes, targetLowPriorityNodes, or both.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskSchedulingPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskSchedulingPolicy TaskSchedulingPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskSchedulingPolicy TaskSchedulingPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.TaskSchedulingPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property TaskSchedulingPolicy As TaskSchedulingPolicy" />
      <MemberSignature Language="F#" Value="member this.TaskSchedulingPolicy : Microsoft.Azure.Batch.Protocol.Models.TaskSchedulingPolicy with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.TaskSchedulingPolicy" />
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
            <span data-ttu-id="41738-179">取得またはタスクのプール内のコンピューティング ノード間で配分する方法を設定します。</span><span class="sxs-lookup"><span data-stu-id="41738-179">Gets or sets how tasks are distributed across compute nodes in a pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserAccounts">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.UserAccount&gt; UserAccounts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.UserAccount&gt; UserAccounts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.UserAccounts" />
      <MemberSignature Language="VB.NET" Value="Public Property UserAccounts As IList(Of UserAccount)" />
      <MemberSignature Language="F#" Value="member this.UserAccounts : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.UserAccount&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.UserAccounts" />
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
            <span data-ttu-id="41738-180">取得またはプール内の各ノード上に作成されるユーザー アカウントの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="41738-180">Gets or sets the list of user accounts to be created on each node in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="poolAddParameter.Validate " />
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
            <span data-ttu-id="41738-181">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="41738-181">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="41738-182">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="41738-182">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration VirtualMachineConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration VirtualMachineConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.VirtualMachineConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualMachineConfiguration As VirtualMachineConfiguration" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineConfiguration : Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.VirtualMachineConfiguration" />
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
            <span data-ttu-id="41738-183">取得またはプールの仮想マシンの構成を設定します。</span><span class="sxs-lookup"><span data-stu-id="41738-183">Gets or sets the virtual machine configuration for the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="41738-184">このプロパティと cloudServiceConfiguration は相互に排他的とプロパティのいずれかを指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="41738-184">This property and cloudServiceConfiguration are mutually exclusive and one of the properties must be specified.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="VmSize">
      <MemberSignature Language="C#" Value="public string VmSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VmSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.VmSize" />
      <MemberSignature Language="VB.NET" Value="Public Property VmSize As String" />
      <MemberSignature Language="F#" Value="member this.VmSize : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.VmSize" />
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
            <span data-ttu-id="41738-185">取得またはプール内の仮想マシンのサイズを設定します。</span><span class="sxs-lookup"><span data-stu-id="41738-185">Gets or sets the size of virtual machines in the pool.</span></span> <span data-ttu-id="41738-186">プール内の仮想マシンのサイズはすべて同じです。</span><span class="sxs-lookup"><span data-stu-id="41738-186">All virtual machines in a pool are the same size.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="41738-187">クラウド サービス プール (プール cloudServiceConfiguration で作成された) の仮想マシンの利用可能なサイズについては、クラウド サービス (http://azure.microsoft.com/documentation/articles/cloud-services-sizes-specs/) のサイズを参照してください。</span><span class="sxs-lookup"><span data-stu-id="41738-187">For information about available sizes of virtual machines for Cloud Services pools (pools created with cloudServiceConfiguration), see Sizes for Cloud Services (http://azure.microsoft.com/documentation/articles/cloud-services-sizes-specs/).</span></span>
            <span data-ttu-id="41738-188">バッチには、ExtraSmall、A1V2 A2V2 を除くすべてのクラウド サービス VM サイズがサポートしています。</span><span class="sxs-lookup"><span data-stu-id="41738-188">Batch supports all Cloud Services VM sizes except ExtraSmall, A1V2 and A2V2.</span></span> <span data-ttu-id="41738-189">(プール virtualMachineConfiguration で作成した) 仮想マシンのマーケットプ レースからイメージを使用するプールの利用可能な VM サイズについては (Linux) (https://azure.microsoft.com/documentation/articles/ の仮想マシンのサイズを参照してください。仮想マシンの linux-サイズ/) または仮想マシン (Windows) (https://azure.microsoft.com/documentation/articles/virtual-machines-windows-sizes/) のサイズ。</span><span class="sxs-lookup"><span data-stu-id="41738-189">For information about available VM sizes for pools using images from the Virtual Machines Marketplace (pools created with virtualMachineConfiguration) see Sizes for Virtual Machines (Linux) (https://azure.microsoft.com/documentation/articles/virtual-machines-linux-sizes/) or Sizes for Virtual Machines (Windows) (https://azure.microsoft.com/documentation/articles/virtual-machines-windows-sizes/).</span></span>
            <span data-ttu-id="41738-190">バッチには、STANDARD_A0 と premium storage (STANDARD_GS、STANDARD_DS、および STANDARD_DSV2 シリーズ) でそれらを除くすべての Azure VM サイズがサポートしています。</span><span class="sxs-lookup"><span data-stu-id="41738-190">Batch supports all Azure VM sizes except STANDARD_A0 and those with premium storage (STANDARD_GS, STANDARD_DS, and STANDARD_DSV2 series).</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>