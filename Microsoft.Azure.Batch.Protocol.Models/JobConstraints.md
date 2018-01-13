<Type Name="JobConstraints" FullName="Microsoft.Azure.Batch.Protocol.Models.JobConstraints">
  <TypeSignature Language="C#" Value="public class JobConstraints" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobConstraints extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.JobConstraints" />
  <TypeSignature Language="VB.NET" Value="Public Class JobConstraints" />
  <TypeSignature Language="F#" Value="type JobConstraints = class" />
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
            <span data-ttu-id="950ea-101">ジョブの実行制約。</span><span class="sxs-lookup"><span data-stu-id="950ea-101">The execution constraints for a job.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobConstraints ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobConstraints.#ctor" />
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
            <span data-ttu-id="950ea-102">JobConstraints クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="950ea-102">Initializes a new instance of the JobConstraints class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobConstraints (Nullable&lt;TimeSpan&gt; maxWallClockTime = null, Nullable&lt;int&gt; maxTaskRetryCount = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; maxWallClockTime, valuetype System.Nullable`1&lt;int32&gt; maxTaskRetryCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobConstraints.#ctor(System.Nullable{System.TimeSpan},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional maxWallClockTime As Nullable(Of TimeSpan) = null, Optional maxTaskRetryCount As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.JobConstraints : Nullable&lt;TimeSpan&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.JobConstraints" Usage="new Microsoft.Azure.Batch.Protocol.Models.JobConstraints (maxWallClockTime, maxTaskRetryCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="maxWallClockTime" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="maxTaskRetryCount" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="maxWallClockTime"><span data-ttu-id="950ea-103">ジョブの実行は、最大の経過時間は、ジョブが作成された時点から計測されます。</span><span class="sxs-lookup"><span data-stu-id="950ea-103">The maximum elapsed time that the job may run, measured from the time the job is created.</span></span></param>
        <param name="maxTaskRetryCount"><span data-ttu-id="950ea-104">各タスクが再試行される最大回数。</span><span class="sxs-lookup"><span data-stu-id="950ea-104">The maximum number of times each task may be retried.</span></span> <span data-ttu-id="950ea-105">Batch サービスは、終了コードが 0 以外の場合にタスクを再試行します。</span><span class="sxs-lookup"><span data-stu-id="950ea-105">The Batch service retries a task if its exit code is nonzero.</span></span></param>
        <summary>
            <span data-ttu-id="950ea-106">JobConstraints クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="950ea-106">Initializes a new instance of the JobConstraints class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxTaskRetryCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxTaskRetryCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxTaskRetryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobConstraints.MaxTaskRetryCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxTaskRetryCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxTaskRetryCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobConstraints.MaxTaskRetryCount" />
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
            <span data-ttu-id="950ea-107">取得または、各タスクが再試行される最大回数を設定します。</span><span class="sxs-lookup"><span data-stu-id="950ea-107">Gets or sets the maximum number of times each task may be retried.</span></span>
            <span data-ttu-id="950ea-108">Batch サービスは、終了コードが 0 以外の場合にタスクを再試行します。</span><span class="sxs-lookup"><span data-stu-id="950ea-108">The Batch service retries a task if its exit code is nonzero.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="950ea-109">この値によって再試行の回数が限定されますのでご注意ください。</span><span class="sxs-lookup"><span data-stu-id="950ea-109">Note that this value specifically controls the number of retries.</span></span>
            <span data-ttu-id="950ea-110">バッチ サービスでは、タスクごとに 1 回試みます、可能性があります、この上限に達するまで再試行してください。</span><span class="sxs-lookup"><span data-stu-id="950ea-110">The Batch service will try each task once, and may then retry up to this limit.</span></span> <span data-ttu-id="950ea-111">たとえば、最大再試行回数が 3 の場合、Batch はタスクを最大 4 回試行します (初回試行 1 回と再試行 3 回)。</span><span class="sxs-lookup"><span data-stu-id="950ea-111">For example, if the maximum retry count is 3, Batch tries a task up to 4 times (one initial try and 3 retries).</span></span> <span data-ttu-id="950ea-112">最大再試行回数が 0 の場合、Batch サービスはタスクを再試行しません。</span><span class="sxs-lookup"><span data-stu-id="950ea-112">If the maximum retry count is 0, the Batch service does not retry tasks.</span></span>
            <span data-ttu-id="950ea-113">最大再試行回数が -1 の場合、Batch サービスはタスクを無制限に再試行します。</span><span class="sxs-lookup"><span data-stu-id="950ea-113">If the maximum retry count is -1, the Batch service retries tasks without limit.</span></span> <span data-ttu-id="950ea-114">既定値は 0 (再試行なし) です。</span><span class="sxs-lookup"><span data-stu-id="950ea-114">The default value is 0 (no retries).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxWallClockTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; MaxWallClockTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; MaxWallClockTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobConstraints.MaxWallClockTime" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxWallClockTime As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.MaxWallClockTime : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobConstraints.MaxWallClockTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxWallClockTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="950ea-115">取得またはジョブが作成された時点から計測されます、ジョブに実行できる最大経過時間を設定します。</span><span class="sxs-lookup"><span data-stu-id="950ea-115">Gets or sets the maximum elapsed time that the job may run, measured from the time the job is created.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="950ea-116">制限時間内にジョブが完了しない場合、Batch service は、まだ実行しているすべてのタスクを終了します。</span><span class="sxs-lookup"><span data-stu-id="950ea-116">If the job does not complete within the time limit, the Batch service terminates it and any tasks that are still running.</span></span> <span data-ttu-id="950ea-117">この場合、MaxWallClockTimeExpiry 終了の理由になります。</span><span class="sxs-lookup"><span data-stu-id="950ea-117">In this case, the termination reason will be MaxWallClockTimeExpiry.</span></span> <span data-ttu-id="950ea-118">このプロパティが指定されていない場合がある制限はありません時間、ジョブの実行がどのくらいの時間です。</span><span class="sxs-lookup"><span data-stu-id="950ea-118">If this property is not specified, there is no time limit on how long the job may run.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>