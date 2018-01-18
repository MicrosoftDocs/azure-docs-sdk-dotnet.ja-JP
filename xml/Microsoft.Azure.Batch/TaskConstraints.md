<Type Name="TaskConstraints" FullName="Microsoft.Azure.Batch.TaskConstraints">
  <TypeSignature Language="C#" Value="public class TaskConstraints" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskConstraints extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.TaskConstraints" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskConstraints" />
  <TypeSignature Language="F#" Value="type TaskConstraints = class&#xA;    interface ITransportObjectProvider&lt;TaskConstraints&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            <span data-ttu-id="0f338-101">特定の Azure Batch タスク上の制約を定義します。</span><span class="sxs-lookup"><span data-stu-id="0f338-101">Defines the constraints on a particular Azure Batch task.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskConstraints (Nullable&lt;TimeSpan&gt; maxWallClockTime = null, Nullable&lt;TimeSpan&gt; retentionTime = null, Nullable&lt;int&gt; maxTaskRetryCount = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; maxWallClockTime, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; retentionTime, valuetype System.Nullable`1&lt;int32&gt; maxTaskRetryCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.TaskConstraints.#ctor(System.Nullable{System.TimeSpan},System.Nullable{System.TimeSpan},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional maxWallClockTime As Nullable(Of TimeSpan) = null, Optional retentionTime As Nullable(Of TimeSpan) = null, Optional maxTaskRetryCount As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.TaskConstraints : Nullable&lt;TimeSpan&gt; * Nullable&lt;TimeSpan&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Batch.TaskConstraints" Usage="new Microsoft.Azure.Batch.TaskConstraints (maxWallClockTime, retentionTime, maxTaskRetryCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="maxWallClockTime" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="retentionTime" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="maxTaskRetryCount" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="maxWallClockTime"><span data-ttu-id="0f338-102">タスクの開始時点からタスクを実行できる最大経過時間が計測されます。</span><span class="sxs-lookup"><span data-stu-id="0f338-102">The maximum elapsed time that the task may run, measured from the time the task starts.</span></span></param>
        <param name="retentionTime"><span data-ttu-id="0f338-103">行く先、実行が完了した時点から、コンピューティング ノード上のタスクの作業ディレクトリを保持する最小期間。</span><span class="sxs-lookup"><span data-stu-id="0f338-103">The minimum time to retain the working directory for the task on the compute node where it ran, from the time it completes execution.</span></span> <span data-ttu-id="0f338-104">この時刻より後は、作業ディレクトリとその内容をすべて、バッチ サービスは削除できます。</span><span class="sxs-lookup"><span data-stu-id="0f338-104">After this time, the Batch service may delete the working directory and all its contents.</span></span></param>
        <param name="maxTaskRetryCount"><span data-ttu-id="0f338-105">タスクの再試行の最大数。</span><span class="sxs-lookup"><span data-stu-id="0f338-105">The maximum number of retries for the task.</span></span></param>
        <summary>
            <span data-ttu-id="0f338-106"><see cref="T:Microsoft.Azure.Batch.TaskConstraints" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0f338-106">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.TaskConstraints" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxTaskRetryCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxTaskRetryCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxTaskRetryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskConstraints.MaxTaskRetryCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxTaskRetryCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxTaskRetryCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.TaskConstraints.MaxTaskRetryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0f338-107">取得またはタスクの再試行の最大数を設定します。</span><span class="sxs-lookup"><span data-stu-id="0f338-107">Gets or sets the maximum number of retries for the task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxWallClockTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; MaxWallClockTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; MaxWallClockTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskConstraints.MaxWallClockTime" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxWallClockTime As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.MaxWallClockTime : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.TaskConstraints.MaxWallClockTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0f338-108">取得またはタスクの開始時点から計測されます、タスクに実行できる最大経過時間を設定します。</span><span class="sxs-lookup"><span data-stu-id="0f338-108">Gets or sets the maximum elapsed time that the task may run, measured from the time the task starts.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; RetentionTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; RetentionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskConstraints.RetentionTime" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionTime As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.RetentionTime : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.TaskConstraints.RetentionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0f338-109">取得または行く先、実行が完了した時点から、コンピューティング ノード上のタスクの作業ディレクトリを保持する時間の最小値を設定します。</span><span class="sxs-lookup"><span data-stu-id="0f338-109">Gets or sets the minimum time to retain the working directory for the task on the compute node where it ran, from the time it completes execution.</span></span> <span data-ttu-id="0f338-110">この時刻より後は、作業ディレクトリとその内容をすべて、バッチ サービスは削除できます。</span><span class="sxs-lookup"><span data-stu-id="0f338-110">After this time, the Batch service may delete the working directory and all its contents.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>