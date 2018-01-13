<Type Name="JobPatchParameter" FullName="Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter">
  <TypeSignature Language="C#" Value="public class JobPatchParameter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobPatchParameter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter" />
  <TypeSignature Language="VB.NET" Value="Public Class JobPatchParameter" />
  <TypeSignature Language="F#" Value="type JobPatchParameter = class" />
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
            <span data-ttu-id="c8349-101">ジョブに対する変更のセット。</span><span class="sxs-lookup"><span data-stu-id="c8349-101">The set of changes to be made to a job.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobPatchParameter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter.#ctor" />
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
            <span data-ttu-id="c8349-102">JobPatchParameter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c8349-102">Initializes a new instance of the JobPatchParameter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobPatchParameter (Nullable&lt;int&gt; priority = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; onAllTasksComplete = null, Microsoft.Azure.Batch.Protocol.Models.JobConstraints constraints = null, Microsoft.Azure.Batch.Protocol.Models.PoolInformation poolInfo = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; metadata = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; priority, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; onAllTasksComplete, class Microsoft.Azure.Batch.Protocol.Models.JobConstraints constraints, class Microsoft.Azure.Batch.Protocol.Models.PoolInformation poolInfo, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; metadata) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter.#ctor(System.Nullable{System.Int32},System.Nullable{Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete},Microsoft.Azure.Batch.Protocol.Models.JobConstraints,Microsoft.Azure.Batch.Protocol.Models.PoolInformation,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.MetadataItem})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional priority As Nullable(Of Integer) = null, Optional onAllTasksComplete As Nullable(Of OnAllTasksComplete) = null, Optional constraints As JobConstraints = null, Optional poolInfo As PoolInformation = null, Optional metadata As IList(Of MetadataItem) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter : Nullable&lt;int&gt; * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; * Microsoft.Azure.Batch.Protocol.Models.JobConstraints * Microsoft.Azure.Batch.Protocol.Models.PoolInformation * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter" Usage="new Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter (priority, onAllTasksComplete, constraints, poolInfo, metadata)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="priority" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="onAllTasksComplete" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt;" />
        <Parameter Name="constraints" Type="Microsoft.Azure.Batch.Protocol.Models.JobConstraints" />
        <Parameter Name="poolInfo" Type="Microsoft.Azure.Batch.Protocol.Models.PoolInformation" />
        <Parameter Name="metadata" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt;" />
      </Parameters>
      <Docs>
        <param name="priority"><span data-ttu-id="c8349-103">ジョブの優先度です。</span><span class="sxs-lookup"><span data-stu-id="c8349-103">The priority of the job.</span></span></param>
        <param name="onAllTasksComplete"><span data-ttu-id="c8349-104">アクション、バッチ サービスは必要があります、ジョブ内のすべてのタスクが完了した状態となります。</span><span class="sxs-lookup"><span data-stu-id="c8349-104">The action the Batch service should take when all tasks in the job are in the completed state.</span></span></param>
        <param name="constraints"><span data-ttu-id="c8349-105">ジョブの実行制約。</span><span class="sxs-lookup"><span data-stu-id="c8349-105">The execution constraints for the job.</span></span></param>
        <param name="poolInfo"><span data-ttu-id="c8349-106">バッチ サービスがジョブのタスクを実行するプールです。</span><span class="sxs-lookup"><span data-stu-id="c8349-106">The pool on which the Batch service runs the job's tasks.</span></span></param>
        <param name="metadata"><span data-ttu-id="c8349-107">ジョブにメタデータとして関連付けられた名前と値のペアの一覧。</span><span class="sxs-lookup"><span data-stu-id="c8349-107">A list of name-value pairs associated with the job as metadata.</span></span></param>
        <summary>
            <span data-ttu-id="c8349-108">JobPatchParameter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c8349-108">Initializes a new instance of the JobPatchParameter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Constraints">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.JobConstraints Constraints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.JobConstraints Constraints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter.Constraints" />
      <MemberSignature Language="VB.NET" Value="Public Property Constraints As JobConstraints" />
      <MemberSignature Language="F#" Value="member this.Constraints : Microsoft.Azure.Batch.Protocol.Models.JobConstraints with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter.Constraints" />
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
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobConstraints</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c8349-109">取得またはジョブの実行の制約を設定します。</span><span class="sxs-lookup"><span data-stu-id="c8349-109">Gets or sets the execution constraints for the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="c8349-110">省略した場合、制約のままにする既存の実行は変更されません。</span><span class="sxs-lookup"><span data-stu-id="c8349-110">If omitted, the existing execution constraints are left unchanged.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; Metadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public Property Metadata As IList(Of MetadataItem)" />
      <MemberSignature Language="F#" Value="member this.Metadata : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter.Metadata" />
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
            <span data-ttu-id="c8349-111">取得またはメタデータとしてジョブに関連付けられている名前と値のペアの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="c8349-111">Gets or sets a list of name-value pairs associated with the job as metadata.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="c8349-112">既存のジョブ メタデータが左で省略すると、変更されません。</span><span class="sxs-lookup"><span data-stu-id="c8349-112">If omitted, the existing job metadata is left unchanged.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAllTasksComplete">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; OnAllTasksComplete { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; OnAllTasksComplete" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter.OnAllTasksComplete" />
      <MemberSignature Language="VB.NET" Value="Public Property OnAllTasksComplete As Nullable(Of OnAllTasksComplete)" />
      <MemberSignature Language="F#" Value="member this.OnAllTasksComplete : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter.OnAllTasksComplete" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="onAllTasksComplete")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c8349-113">取得またはバッチ ジョブ内のすべてのタスクが完了の状態でサービスが行うアクションを設定します。</span><span class="sxs-lookup"><span data-stu-id="c8349-113">Gets or sets the action the Batch service should take when all tasks in the job are in the completed state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="c8349-114">補完の動作が左を省略すると、変更されません。</span><span class="sxs-lookup"><span data-stu-id="c8349-114">If omitted, the completion behavior is left unchanged.</span></span> <span data-ttu-id="c8349-115">NoAction に terminateJob から値を変更することがありますされません - は、ジョブの自動終了が関与して、一度を有効にできません再度オフします。</span><span class="sxs-lookup"><span data-stu-id="c8349-115">You may not change the value from terminateJob to noAction - that is, once you have engaged automatic job termination, you cannot turn it off again.</span></span> <span data-ttu-id="c8349-116">これを実行しようとすると、要求は '無効なプロパティ値' エラー応答; が失敗します。REST API を直接呼び出すが、HTTP ステータス コードは 400 (Bad Request) がします。</span><span class="sxs-lookup"><span data-stu-id="c8349-116">If you try to do this, the request fails with an 'invalid property value' error response; if you are calling the REST API directly, the HTTP status code is 400 (Bad Request).</span></span> <span data-ttu-id="c8349-117">使用可能な値が含まれます: 'noAction'、'terminateJob'</span><span class="sxs-lookup"><span data-stu-id="c8349-117">Possible values include: 'noAction', 'terminateJob'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PoolInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.PoolInformation PoolInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.PoolInformation PoolInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter.PoolInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property PoolInfo As PoolInformation" />
      <MemberSignature Language="F#" Value="member this.PoolInfo : Microsoft.Azure.Batch.Protocol.Models.PoolInformation with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter.PoolInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="poolInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.PoolInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c8349-118">取得またはバッチ サービスがジョブのタスクを実行するプールを設定します。</span><span class="sxs-lookup"><span data-stu-id="c8349-118">Gets or sets the pool on which the Batch service runs the job's tasks.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="c8349-119">ジョブが無効になっている場合にのみ、ジョブのプールを変更することがあります。</span><span class="sxs-lookup"><span data-stu-id="c8349-119">You may change the pool for a job only when the job is disabled.</span></span>
            <span data-ttu-id="c8349-120">PoolInfo 要素を含めるし、ジョブが無効になっていない更新プログラムのジョブの呼び出しは失敗します。</span><span class="sxs-lookup"><span data-stu-id="c8349-120">The Patch Job call will fail if you include the poolInfo element and the job is not disabled.</span></span> <span data-ttu-id="c8349-121">KeepAlive プロパティのみを更新できる場合は、poolInfo で autoPoolSpecification 仕様を指定すると、し、自動プールのジョブの poolLifetimeOption がある場合のみです。</span><span class="sxs-lookup"><span data-stu-id="c8349-121">If you specify an autoPoolSpecification specification in the poolInfo, only the keepAlive property can be updated, and then only if the auto pool has a poolLifetimeOption of job.</span></span> <span data-ttu-id="c8349-122">省略した場合、ジョブは引き続き、現在のプールで実行されます。</span><span class="sxs-lookup"><span data-stu-id="c8349-122">If omitted, the job continues to run on its current pool.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Priority">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Priority { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Priority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter.Priority" />
      <MemberSignature Language="VB.NET" Value="Public Property Priority As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Priority : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter.Priority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="priority")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c8349-123">取得またはジョブの優先順位を設定します。</span><span class="sxs-lookup"><span data-stu-id="c8349-123">Gets or sets the priority of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="c8349-124">優先順位の値の範囲は -1000 から 1000、-1000 が最も低い優先度と 1000 中優先順位が高いです。</span><span class="sxs-lookup"><span data-stu-id="c8349-124">Priority values can range from -1000 to 1000, with -1000 being the lowest priority and 1000 being the highest priority.</span></span> <span data-ttu-id="c8349-125">ジョブの優先度が左で省略すると、変更されません。</span><span class="sxs-lookup"><span data-stu-id="c8349-125">If omitted, the priority of the job is left unchanged.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="jobPatchParameter.Validate " />
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
            <span data-ttu-id="c8349-126">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="c8349-126">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c8349-127">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c8349-127">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>