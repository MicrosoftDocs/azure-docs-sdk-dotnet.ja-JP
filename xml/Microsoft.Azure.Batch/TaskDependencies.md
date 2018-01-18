<Type Name="TaskDependencies" FullName="Microsoft.Azure.Batch.TaskDependencies">
  <TypeSignature Language="C#" Value="public class TaskDependencies" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskDependencies extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.TaskDependencies" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskDependencies" />
  <TypeSignature Language="F#" Value="type TaskDependencies = class&#xA;    interface ITransportObjectProvider&lt;TaskDependencies&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            <span data-ttu-id="1cb8d-101">タスクの依存関係を指定します。</span><span class="sxs-lookup"><span data-stu-id="1cb8d-101">Specifies any dependencies of a task.</span></span> <span data-ttu-id="1cb8d-102">明示的に指定されているすべてのタスクまたは依存関係内で、範囲を依存タスクがスケジュールされる前に完了する必要があります。</span><span class="sxs-lookup"><span data-stu-id="1cb8d-102">Any task that is explicitly specified or within a dependency range must complete before the dependant task will be scheduled.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskDependencies (System.Collections.Generic.IEnumerable&lt;string&gt; taskIds, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.TaskIdRange&gt; taskIdRanges);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;string&gt; taskIds, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.TaskIdRange&gt; taskIdRanges) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.TaskDependencies.#ctor(System.Collections.Generic.IEnumerable{System.String},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.TaskIdRange})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (taskIds As IEnumerable(Of String), taskIdRanges As IEnumerable(Of TaskIdRange))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.TaskDependencies : seq&lt;string&gt; * seq&lt;Microsoft.Azure.Batch.TaskIdRange&gt; -&gt; Microsoft.Azure.Batch.TaskDependencies" Usage="new Microsoft.Azure.Batch.TaskDependencies (taskIds, taskIdRanges)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="taskIds" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="taskIdRanges" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.TaskIdRange&gt;" />
      </Parameters>
      <Docs>
        <param name="taskIds"><span data-ttu-id="1cb8d-103">このタスクをスケジュールする前に完了する必要がありますのあるタスク id の一覧。</span><span class="sxs-lookup"><span data-stu-id="1cb8d-103">The list of task ids that must complete before this task can be scheduled.</span></span> <span data-ttu-id="1cb8d-104">null は、空のリストとして扱われます。</span><span class="sxs-lookup"><span data-stu-id="1cb8d-104">null is treated as an empty list.</span></span></param>
        <param name="taskIdRanges"><span data-ttu-id="1cb8d-105">このタスクをスケジュールする前に完了する必要がありますのあるタスクの範囲の一覧。</span><span class="sxs-lookup"><span data-stu-id="1cb8d-105">The list of task ranges that must complete before this task can be scheduled.</span></span> <span data-ttu-id="1cb8d-106">null は、空のリストとして扱われます。</span><span class="sxs-lookup"><span data-stu-id="1cb8d-106">null is treated as an empty list.</span></span></param>
        <summary>
            <span data-ttu-id="1cb8d-107"><see cref="T:Microsoft.Azure.Batch.TaskDependencies" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1cb8d-107">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.TaskDependencies" /> class.</span></span>
            </summary>
        <remarks><span data-ttu-id="1cb8d-108">このコンス トラクターは、TaskDependencies オブジェクトの初期化の最も一般的な方法を提供します。</span><span class="sxs-lookup"><span data-stu-id="1cb8d-108">This constructor provides the most general way of initializing a TaskDependencies object.</span></span>
            <span data-ttu-id="1cb8d-109">実際には、依存関係のほとんどは、1 つのタスク、タスク id の一覧または単一のタスクの範囲には。</span><span class="sxs-lookup"><span data-stu-id="1cb8d-109">In practice, most dependencies are on a single task, a list of task ids, or a single range of tasks.</span></span> <span data-ttu-id="1cb8d-110">これらの依存関係をさらに明確に表現できます<see cref="M:Microsoft.Azure.Batch.TaskDependencies.OnId(System.String)" />、 <see cref="M:Microsoft.Azure.Batch.TaskDependencies.OnIds(System.String[])" />、 <see cref="M:Microsoft.Azure.Batch.TaskDependencies.OnTasks(Microsoft.Azure.Batch.CloudTask[])" />、および<see cref="M:Microsoft.Azure.Batch.TaskDependencies.OnIdRange(System.Int32,System.Int32)" />メソッドです。</span><span class="sxs-lookup"><span data-stu-id="1cb8d-110">You can express these dependencies more clearly using <see cref="M:Microsoft.Azure.Batch.TaskDependencies.OnId(System.String)" />, <see cref="M:Microsoft.Azure.Batch.TaskDependencies.OnIds(System.String[])" />, <see cref="M:Microsoft.Azure.Batch.TaskDependencies.OnTasks(Microsoft.Azure.Batch.CloudTask[])" />, and <see cref="M:Microsoft.Azure.Batch.TaskDependencies.OnIdRange(System.Int32,System.Int32)" /> methods.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="OnId">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.TaskDependencies OnId (string id);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.TaskDependencies OnId(string id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.TaskDependencies.OnId(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function OnId (id As String) As TaskDependencies" />
      <MemberSignature Language="F#" Value="static member OnId : string -&gt; Microsoft.Azure.Batch.TaskDependencies" Usage="Microsoft.Azure.Batch.TaskDependencies.OnId id" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.TaskDependencies</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="1cb8d-111">依存するタスクです。</span><span class="sxs-lookup"><span data-stu-id="1cb8d-111">The task to depend on.</span></span></param>
        <summary>
            <span data-ttu-id="1cb8d-112">取得、<see cref="T:Microsoft.Azure.Batch.TaskDependencies" />を表す 1 つのタスクに依存します。</span><span class="sxs-lookup"><span data-stu-id="1cb8d-112">Gets a <see cref="T:Microsoft.Azure.Batch.TaskDependencies" /> representing dependency on a single task.</span></span>
            </summary>
        <returns><span data-ttu-id="1cb8d-113">A<see cref="T:Microsoft.Azure.Batch.TaskDependencies" />を表す 1 つのタスクに依存します。</span><span class="sxs-lookup"><span data-stu-id="1cb8d-113">A <see cref="T:Microsoft.Azure.Batch.TaskDependencies" /> representing dependency on a single task.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnIdRange">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.TaskDependencies OnIdRange (int start, int end);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.TaskDependencies OnIdRange(int32 start, int32 end) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.TaskDependencies.OnIdRange(System.Int32,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function OnIdRange (start As Integer, end As Integer) As TaskDependencies" />
      <MemberSignature Language="F#" Value="static member OnIdRange : int * int -&gt; Microsoft.Azure.Batch.TaskDependencies" Usage="Microsoft.Azure.Batch.TaskDependencies.OnIdRange (start, end)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.TaskDependencies</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="start" Type="System.Int32" />
        <Parameter Name="end" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="start"><span data-ttu-id="1cb8d-114">依存する範囲の最初のタスクの id。</span><span class="sxs-lookup"><span data-stu-id="1cb8d-114">The first task id in the range to depend on.</span></span></param>
        <param name="end"><span data-ttu-id="1cb8d-115">依存する範囲の最後のタスクの id。</span><span class="sxs-lookup"><span data-stu-id="1cb8d-115">The last task id in the range to depend on.</span></span></param>
        <summary>
            <span data-ttu-id="1cb8d-116">取得、<see cref="T:Microsoft.Azure.Batch.TaskDependencies" />を表すタスク id の範囲に依存します。</span><span class="sxs-lookup"><span data-stu-id="1cb8d-116">Gets a <see cref="T:Microsoft.Azure.Batch.TaskDependencies" /> representing dependency on a range of task ids.</span></span>
            </summary>
        <returns><span data-ttu-id="1cb8d-117">A<see cref="T:Microsoft.Azure.Batch.TaskDependencies" />を表すタスクの指定した範囲に依存します。</span><span class="sxs-lookup"><span data-stu-id="1cb8d-117">A <see cref="T:Microsoft.Azure.Batch.TaskDependencies" /> representing dependency on the specified range of tasks.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnIds">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.TaskDependencies OnIds (System.Collections.Generic.IEnumerable&lt;string&gt; ids);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.TaskDependencies OnIds(class System.Collections.Generic.IEnumerable`1&lt;string&gt; ids) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.TaskDependencies.OnIds(System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function OnIds (ids As IEnumerable(Of String)) As TaskDependencies" />
      <MemberSignature Language="F#" Value="static member OnIds : seq&lt;string&gt; -&gt; Microsoft.Azure.Batch.TaskDependencies" Usage="Microsoft.Azure.Batch.TaskDependencies.OnIds ids" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.TaskDependencies</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ids" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="ids"><span data-ttu-id="1cb8d-118">依存するタスク。</span><span class="sxs-lookup"><span data-stu-id="1cb8d-118">The tasks to depend on.</span></span></param>
        <summary>
            <span data-ttu-id="1cb8d-119">取得、<see cref="T:Microsoft.Azure.Batch.TaskDependencies" />タスク id の一覧への依存関係を表すです。</span><span class="sxs-lookup"><span data-stu-id="1cb8d-119">Gets a <see cref="T:Microsoft.Azure.Batch.TaskDependencies" /> representing dependency on a list of task ids.</span></span>
            </summary>
        <returns><span data-ttu-id="1cb8d-120">A<see cref="T:Microsoft.Azure.Batch.TaskDependencies" />指定されたタスクの依存関係を表すです。</span><span class="sxs-lookup"><span data-stu-id="1cb8d-120">A <see cref="T:Microsoft.Azure.Batch.TaskDependencies" /> representing dependency on the specified tasks.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnIds">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.TaskDependencies OnIds (params string[] ids);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.TaskDependencies OnIds(string[] ids) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.TaskDependencies.OnIds(System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function OnIds (ParamArray ids As String()) As TaskDependencies" />
      <MemberSignature Language="F#" Value="static member OnIds : string[] -&gt; Microsoft.Azure.Batch.TaskDependencies" Usage="Microsoft.Azure.Batch.TaskDependencies.OnIds ids" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.TaskDependencies</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ids" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="ids"><span data-ttu-id="1cb8d-121">依存するタスク。</span><span class="sxs-lookup"><span data-stu-id="1cb8d-121">The tasks to depend on.</span></span></param>
        <summary>
            <span data-ttu-id="1cb8d-122">取得、<see cref="T:Microsoft.Azure.Batch.TaskDependencies" />タスク id の一覧への依存関係を表すです。</span><span class="sxs-lookup"><span data-stu-id="1cb8d-122">Gets a <see cref="T:Microsoft.Azure.Batch.TaskDependencies" /> representing dependency on a list of task ids.</span></span>
            </summary>
        <returns><span data-ttu-id="1cb8d-123">A<see cref="T:Microsoft.Azure.Batch.TaskDependencies" />指定されたタスクの依存関係を表すです。</span><span class="sxs-lookup"><span data-stu-id="1cb8d-123">A <see cref="T:Microsoft.Azure.Batch.TaskDependencies" /> representing dependency on the specified tasks.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnTasks">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.TaskDependencies OnTasks (params Microsoft.Azure.Batch.CloudTask[] tasks);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.TaskDependencies OnTasks(class Microsoft.Azure.Batch.CloudTask[] tasks) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.TaskDependencies.OnTasks(Microsoft.Azure.Batch.CloudTask[])" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function OnTasks (ParamArray tasks As CloudTask()) As TaskDependencies" />
      <MemberSignature Language="F#" Value="static member OnTasks : Microsoft.Azure.Batch.CloudTask[] -&gt; Microsoft.Azure.Batch.TaskDependencies" Usage="Microsoft.Azure.Batch.TaskDependencies.OnTasks tasks" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.TaskDependencies</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tasks" Type="Microsoft.Azure.Batch.CloudTask[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="tasks"><span data-ttu-id="1cb8d-124">依存するタスク。</span><span class="sxs-lookup"><span data-stu-id="1cb8d-124">The tasks to depend on.</span></span></param>
        <summary>
            <span data-ttu-id="1cb8d-125">取得、<see cref="T:Microsoft.Azure.Batch.TaskDependencies" />タスクの一覧への依存関係を表すです。</span><span class="sxs-lookup"><span data-stu-id="1cb8d-125">Gets a <see cref="T:Microsoft.Azure.Batch.TaskDependencies" /> representing dependency on a list of tasks.</span></span>
            </summary>
        <returns><span data-ttu-id="1cb8d-126">A<see cref="T:Microsoft.Azure.Batch.TaskDependencies" />指定されたタスクの依存関係を表すです。</span><span class="sxs-lookup"><span data-stu-id="1cb8d-126">A <see cref="T:Microsoft.Azure.Batch.TaskDependencies" /> representing dependency on the specified tasks.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnTasks">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.TaskDependencies OnTasks (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt; tasks);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.TaskDependencies OnTasks(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.CloudTask&gt; tasks) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.TaskDependencies.OnTasks(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function OnTasks (tasks As IEnumerable(Of CloudTask)) As TaskDependencies" />
      <MemberSignature Language="F#" Value="static member OnTasks : seq&lt;Microsoft.Azure.Batch.CloudTask&gt; -&gt; Microsoft.Azure.Batch.TaskDependencies" Usage="Microsoft.Azure.Batch.TaskDependencies.OnTasks tasks" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.TaskDependencies</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tasks" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt;" />
      </Parameters>
      <Docs>
        <param name="tasks"><span data-ttu-id="1cb8d-127">依存するタスク。</span><span class="sxs-lookup"><span data-stu-id="1cb8d-127">The tasks to depend on.</span></span></param>
        <summary>
            <span data-ttu-id="1cb8d-128">取得、<see cref="T:Microsoft.Azure.Batch.TaskDependencies" />タスクの一覧への依存関係を表すです。</span><span class="sxs-lookup"><span data-stu-id="1cb8d-128">Gets a <see cref="T:Microsoft.Azure.Batch.TaskDependencies" /> representing dependency on a list of tasks.</span></span>
            </summary>
        <returns><span data-ttu-id="1cb8d-129">A<see cref="T:Microsoft.Azure.Batch.TaskDependencies" />指定されたタスクの依存関係を表すです。</span><span class="sxs-lookup"><span data-stu-id="1cb8d-129">A <see cref="T:Microsoft.Azure.Batch.TaskDependencies" /> representing dependency on the specified tasks.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskIdRanges">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.TaskIdRange&gt; TaskIdRanges { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Batch.TaskIdRange&gt; TaskIdRanges" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskDependencies.TaskIdRanges" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TaskIdRanges As IReadOnlyList(Of TaskIdRange)" />
      <MemberSignature Language="F#" Value="member this.TaskIdRanges : System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.TaskIdRange&gt;" Usage="Microsoft.Azure.Batch.TaskDependencies.TaskIdRanges" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.TaskIdRange&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1cb8d-130">タスクにこのタスクが依存している Id の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="1cb8d-130">Gets the list of task IDs that this task depends on.</span></span> <span data-ttu-id="1cb8d-131">この一覧のすべてのタスクは、依存タスクをスケジュールする前に正常に完了する必要があります。</span><span class="sxs-lookup"><span data-stu-id="1cb8d-131">All tasks in this list must complete successfully before the dependent task can be scheduled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskIds">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;string&gt; TaskIds { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;string&gt; TaskIds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskDependencies.TaskIds" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TaskIds As IReadOnlyList(Of String)" />
      <MemberSignature Language="F#" Value="member this.TaskIds : System.Collections.Generic.IReadOnlyList&lt;string&gt;" Usage="Microsoft.Azure.Batch.TaskDependencies.TaskIds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1cb8d-132">このタスクが依存しているタスクの ID 範囲の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="1cb8d-132">Gets the list of task ID ranges that this task depends on.</span></span> <span data-ttu-id="1cb8d-133">依存タスクをスケジュールする前にすべての範囲内のすべてのタスクが正常に完了する必要があります。</span><span class="sxs-lookup"><span data-stu-id="1cb8d-133">All tasks in all ranges must complete successfully before the dependent task can be scheduled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>