<Type Name="JobUpdateParameter" FullName="Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter">
  <TypeSignature Language="C#" Value="public class JobUpdateParameter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobUpdateParameter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter" />
  <TypeSignature Language="VB.NET" Value="Public Class JobUpdateParameter" />
  <TypeSignature Language="F#" Value="type JobUpdateParameter = class" />
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
            <span data-ttu-id="1770c-101">ジョブに対する変更のセット。</span><span class="sxs-lookup"><span data-stu-id="1770c-101">The set of changes to be made to a job.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobUpdateParameter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter.#ctor" />
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
            <span data-ttu-id="1770c-102">JobUpdateParameter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1770c-102">Initializes a new instance of the JobUpdateParameter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobUpdateParameter (Microsoft.Azure.Batch.Protocol.Models.PoolInformation poolInfo, Nullable&lt;int&gt; priority = null, Microsoft.Azure.Batch.Protocol.Models.JobConstraints constraints = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; metadata = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; onAllTasksComplete = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.Protocol.Models.PoolInformation poolInfo, valuetype System.Nullable`1&lt;int32&gt; priority, class Microsoft.Azure.Batch.Protocol.Models.JobConstraints constraints, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; metadata, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; onAllTasksComplete) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter.#ctor(Microsoft.Azure.Batch.Protocol.Models.PoolInformation,System.Nullable{System.Int32},Microsoft.Azure.Batch.Protocol.Models.JobConstraints,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.MetadataItem},System.Nullable{Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (poolInfo As PoolInformation, Optional priority As Nullable(Of Integer) = null, Optional constraints As JobConstraints = null, Optional metadata As IList(Of MetadataItem) = null, Optional onAllTasksComplete As Nullable(Of OnAllTasksComplete) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter : Microsoft.Azure.Batch.Protocol.Models.PoolInformation * Nullable&lt;int&gt; * Microsoft.Azure.Batch.Protocol.Models.JobConstraints * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter" Usage="new Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter (poolInfo, priority, constraints, metadata, onAllTasksComplete)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="poolInfo" Type="Microsoft.Azure.Batch.Protocol.Models.PoolInformation" />
        <Parameter Name="priority" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="constraints" Type="Microsoft.Azure.Batch.Protocol.Models.JobConstraints" />
        <Parameter Name="metadata" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt;" />
        <Parameter Name="onAllTasksComplete" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt;" />
      </Parameters>
      <Docs>
        <param name="poolInfo"><span data-ttu-id="1770c-103">バッチ サービスがジョブのタスクを実行するプールです。</span><span class="sxs-lookup"><span data-stu-id="1770c-103">The pool on which the Batch service runs the job's tasks.</span></span></param>
        <param name="priority"><span data-ttu-id="1770c-104">ジョブの優先度です。</span><span class="sxs-lookup"><span data-stu-id="1770c-104">The priority of the job.</span></span></param>
        <param name="constraints"><span data-ttu-id="1770c-105">ジョブの実行制約。</span><span class="sxs-lookup"><span data-stu-id="1770c-105">The execution constraints for the job.</span></span></param>
        <param name="metadata"><span data-ttu-id="1770c-106">ジョブにメタデータとして関連付けられた名前と値のペアの一覧。</span><span class="sxs-lookup"><span data-stu-id="1770c-106">A list of name-value pairs associated with the job as metadata.</span></span></param>
        <param name="onAllTasksComplete"><span data-ttu-id="1770c-107">アクション、バッチ サービスは必要があります、ジョブ内のすべてのタスクが完了した状態となります。</span><span class="sxs-lookup"><span data-stu-id="1770c-107">The action the Batch service should take when all tasks in the job are in the completed state.</span></span></param>
        <summary>
            <span data-ttu-id="1770c-108">JobUpdateParameter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1770c-108">Initializes a new instance of the JobUpdateParameter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Constraints">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.JobConstraints Constraints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.JobConstraints Constraints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter.Constraints" />
      <MemberSignature Language="VB.NET" Value="Public Property Constraints As JobConstraints" />
      <MemberSignature Language="F#" Value="member this.Constraints : Microsoft.Azure.Batch.Protocol.Models.JobConstraints with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter.Constraints" />
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
            <span data-ttu-id="1770c-109">取得またはジョブの実行の制約を設定します。</span><span class="sxs-lookup"><span data-stu-id="1770c-109">Gets or sets the execution constraints for the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="1770c-110">省略した場合、制約はクリアされます。</span><span class="sxs-lookup"><span data-stu-id="1770c-110">If omitted, the constraints are cleared.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; Metadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public Property Metadata As IList(Of MetadataItem)" />
      <MemberSignature Language="F#" Value="member this.Metadata : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter.Metadata" />
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
            <span data-ttu-id="1770c-111">取得またはメタデータとしてジョブに関連付けられている名前と値のペアの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="1770c-111">Gets or sets a list of name-value pairs associated with the job as metadata.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="1770c-112">省略すると、一覧が空の既定値になります実際には、既存のメタデータが削除されます。</span><span class="sxs-lookup"><span data-stu-id="1770c-112">If omitted, it takes the default value of an empty list; in effect, any existing metadata is deleted.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAllTasksComplete">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; OnAllTasksComplete { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; OnAllTasksComplete" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter.OnAllTasksComplete" />
      <MemberSignature Language="VB.NET" Value="Public Property OnAllTasksComplete As Nullable(Of OnAllTasksComplete)" />
      <MemberSignature Language="F#" Value="member this.OnAllTasksComplete : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter.OnAllTasksComplete" />
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
            <span data-ttu-id="1770c-113">取得またはバッチ ジョブ内のすべてのタスクが完了の状態でサービスが行うアクションを設定します。</span><span class="sxs-lookup"><span data-stu-id="1770c-113">Gets or sets the action the Batch service should take when all tasks in the job are in the completed state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="1770c-114">省略した場合は、補完の動作は noAction に設定されます。</span><span class="sxs-lookup"><span data-stu-id="1770c-114">If omitted, the completion behavior is set to noAction.</span></span> <span data-ttu-id="1770c-115">現在の値が terminateJob の場合は、これは、エラーのため noAction に terminateJob から、ジョブの完了動作が変更されません可能性があります。</span><span class="sxs-lookup"><span data-stu-id="1770c-115">If the current value is terminateJob, this is an error because a job's completion behavior may not be changed from terminateJob to noAction.</span></span> <span data-ttu-id="1770c-116">Noaction に terminatejob から値を変更することがありますされません - は、ジョブの自動終了が関与して、一度を有効にできません再度オフします。</span><span class="sxs-lookup"><span data-stu-id="1770c-116">You may not change the value from terminatejob to noaction - that is, once you have engaged automatic job termination, you cannot turn it off again.</span></span> <span data-ttu-id="1770c-117">これを行うしようとすると、要求が失敗してバッチを返します。 ステータス コード 400 (Bad Request) と '無効なプロパティ値' エラー応答。</span><span class="sxs-lookup"><span data-stu-id="1770c-117">If you try to do this, the request fails and Batch returns status code 400 (Bad Request) and an 'invalid property value' error response.</span></span> <span data-ttu-id="1770c-118">PUT 要求でこの要素を指定しない場合は、noaction を渡すことと同じです。</span><span class="sxs-lookup"><span data-stu-id="1770c-118">If you do not specify this element in a PUT request, it is equivalent to passing noaction.</span></span> <span data-ttu-id="1770c-119">これは、現在の値が terminatejob 場合のエラーです。</span><span class="sxs-lookup"><span data-stu-id="1770c-119">This is an error if the current value is terminatejob.</span></span>
            <span data-ttu-id="1770c-120">使用可能な値が含まれます: 'noAction'、'terminateJob'</span><span class="sxs-lookup"><span data-stu-id="1770c-120">Possible values include: 'noAction', 'terminateJob'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PoolInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.PoolInformation PoolInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.PoolInformation PoolInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter.PoolInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property PoolInfo As PoolInformation" />
      <MemberSignature Language="F#" Value="member this.PoolInfo : Microsoft.Azure.Batch.Protocol.Models.PoolInformation with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter.PoolInfo" />
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
            <span data-ttu-id="1770c-121">取得またはバッチ サービスがジョブのタスクを実行するプールを設定します。</span><span class="sxs-lookup"><span data-stu-id="1770c-121">Gets or sets the pool on which the Batch service runs the job's tasks.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="1770c-122">ジョブが無効になっている場合にのみ、ジョブのプールを変更することがあります。</span><span class="sxs-lookup"><span data-stu-id="1770c-122">You may change the pool for a job only when the job is disabled.</span></span>
            <span data-ttu-id="1770c-123">PoolInfo 要素を含めるし、ジョブが無効になっていない場合、更新ジョブの呼び出しは失敗します。</span><span class="sxs-lookup"><span data-stu-id="1770c-123">The Update Job call will fail if you include the poolInfo element and the job is not disabled.</span></span> <span data-ttu-id="1770c-124">KeepAlive プロパティのみを更新できる場合は、poolInfo で autoPoolSpecification 仕様を指定すると、し、自動プールのジョブの poolLifetimeOption がある場合のみです。</span><span class="sxs-lookup"><span data-stu-id="1770c-124">If you specify an autoPoolSpecification specification in the poolInfo, only the keepAlive property can be updated, and then only if the auto pool has a poolLifetimeOption of job.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Priority">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Priority { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Priority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter.Priority" />
      <MemberSignature Language="VB.NET" Value="Public Property Priority As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Priority : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter.Priority" />
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
            <span data-ttu-id="1770c-125">取得またはジョブの優先順位を設定します。</span><span class="sxs-lookup"><span data-stu-id="1770c-125">Gets or sets the priority of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="1770c-126">優先順位の値の範囲は -1000 から 1000、-1000 が最も低い優先度と 1000 中優先順位が高いです。</span><span class="sxs-lookup"><span data-stu-id="1770c-126">Priority values can range from -1000 to 1000, with -1000 being the lowest priority and 1000 being the highest priority.</span></span> <span data-ttu-id="1770c-127">省略した場合、既定値 0 に設定されます。</span><span class="sxs-lookup"><span data-stu-id="1770c-127">If omitted, it is set to the default value 0.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="jobUpdateParameter.Validate " />
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
            <span data-ttu-id="1770c-128">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="1770c-128">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1770c-129">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1770c-129">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>